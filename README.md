Write-and-Black-Chess
====
Need
----
* python3.5
* tensorflow >= 0.12.1
* tensorlayer >= 1.2.8 注：如果要打比赛请进入源码注释掉其中的print，再从源码安装

Usage
----

First,train models with:

    $ python train.py

Next:play the game
 
    $ python game.py

Else
----

Use：

    $ python game_cnn.py or python game_nn.py

enjoy the game

Notice
----
因为输入输出流的原因，自己训练出来的model请手动读入到代码中，像game_cnn.py那样
