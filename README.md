# Big-2-Automatic-Dealer-System-

Using python language, using max-min method and alpha-beta pruning to predict the opponent's card play. The team played dozens of rounds of battles with other groups, and finally won the 2nd place in the class, which is more stable and has a higher winning rate than other groups. The main advantages are: the search algorithm tree's long-term consideration of the situation; pruning effectively improves the efficiency of the search algorithm; the incorporation of empirical rules, prioritizing the search for the best empirical solution can effectively improve efficiency and accuracy, and in order to reduce calculation time, experience can also be used to do some more subjective pruning.

使用python语言，运用最大最小值法、alpha-beta剪枝进行对方的出牌预测。 与其他组进行数十轮对战，最终获班级第2名，稳定性、胜率远超其他组。主要优点为：搜索算法树对局面的长远考虑；剪枝有效提高搜索算法效率；经验规则的融入，优先搜索经验上的最优解可以有效提高效率和准确率，同时为了减少计算时间，也可以用经验做一些较为主观的剪枝。

The main program big2.py, referee dialer.py, team1.py, which only knows how to play a single card, and team2.py, which plays cards manually, are implemented. team3 has the same Player implementation as team1.py, but the Player code is managed in the directory. The referee now has only two cards.
How to run the program: python3 big2.py -a <attacker> -d <defender> -g <game> attacker is the code of the first hand, defender is the code of the second hand, and game is the referee's dealing number.
For example: python3 big2.py -a Team1 -d team2 -g 1 is to use the 1st deck (preceded by the 0th deck) and have team1 and team2 play. python3 big2.py -a Team1 -d team3 -g 1 is to use the 1st deck of cards and have Team1 and Team3 play a match.
I provided the code of my team : alphapoker.py

实现了主程序big2.py、裁判员dealer.py、只知道出单张牌的Team1.py、人工出牌Team2.py team3放了同Team1.py一样的Player实现，只不过采用目录的方式管理Player代码。 裁判员现在只存了两幅牌。
程序运行方式： python3 big2.py -a <attacker> -d <defender> -g <game> attacker是先手方的代码，defender是后手方的代码，game是裁判员的发牌序号
比如： python3 big2.py -a Team1 -d Team2 -g 1 就是用第1副牌（前面还有第0副牌），让Team1和Team2打比赛。 python3 big2.py -a Team1 -d team3 -g 1 用第1副牌，让Team1和team3打比赛。
我提供的是本队的代码 alphapoker.py
