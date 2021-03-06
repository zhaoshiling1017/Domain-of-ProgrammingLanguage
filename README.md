> [我应该从哪一门编程语言上车?](https://segmentfault.com/a/1190000007398287)翻译自[what-programming-language-should-i-learn-first](https://medium.freecodecamp.com/what-programming-language-should-i-learn-first-%CA%87d%C4%B1%C9%B9%C9%94s%C9%90%CA%8C%C9%90%C9%BE-%C9%B9%C7%9D%CA%8Dsu%C9%90-19a33b0a467d#.v4f8nwci1)。作者开宗明义，直指结果，JavaScript是最适合初学者的语言。
> 本文从属于笔者的[程序员知识图谱与体系结构](https://github.com/wxyyxc1992/Coder-Knowledge-Graph)。此外推荐阅读[我的编程之路——知识管理与知识体系](https://segmentfault.com/a/1190000004612590)与[前端入门与最佳实践](https://github.com/wxyyxc1992/Web-Develop-Introduction-And-Best-Practices/tree/master/Frontend)。

![](https://coding.net/u/hoteam/p/Cache/git/raw/master/2016/11/2/1-1XEF9NuNQy0rSu4kVdbb6A.jpeg)

很多人的代码之路可能从某个Google搜索开始，譬如`如何学习xxx`，不过又该决定从哪个语言开始这一段旅程呢？如果你问身边朋友的建议，可能会听到这些建议:
- 硅谷里的小伙伴经常调笑Java，我觉得我可以先学这个。
- Haskell，现在这么热，肯定要学这个。
- Go语言的Logo好可爱。

![](https://coding.net/u/hoteam/p/Cache/git/raw/master/2016/11/2/1-7kbd-tVk3co-9RiilFN1TA.png)
不过还有很多人估计会选择直接搜索，我应该学习啥语言呢？我们的思考过程可以总结在下面这张图中:
![](https://coding.net/u/hoteam/p/Cache/git/raw/master/2016/11/2/1-OF594B5qtCJR9MFSRTI-5g.png)
这个过程真的是纠结而又快乐，估计如果是强迫症的处女座会更痛苦。从我的角度来看，我们考虑学哪一门语言应该从以下几个方面进行考虑:
- 这门语言的市场需求量如何
- 这门语言的未来前景如何
- 这门语言是否容易上手
- 你计划用这门语言构建如何的项目

编程语言的这片红海也是英雄辈出，每年都会有新的编程语言出现，我们先来看一幅漫画:

![](https://coding.net/u/hoteam/p/Cache/git/raw/master/2016/11/2/xasadscdsavasdvasx.png)

当我们现在考虑应该选择哪一门入门语言时，我们也要来看看这些年里别人的选择，下图是12年里各个语言的搜索量排行:
![](https://coding.net/u/hoteam/p/Cache/git/raw/master/2016/11/2/1-znaagCC5fn0-Dqy43ILeqQ.png)
Java本身有其优势与劣势，而Python正在逐步成长为最受欢迎的选择之一。不过这两年随着Web技术的迅猛发展，JavaScript正成为日益受欢迎的选择之一。在正式阐述之前，我首先澄清一下:
- 我并不想引起圣战，并没有强调哪一门语言就比其他的好
- 我认为每个人不应该拘泥于某一门语言
- 我推荐才入门的同学可以从JavaScript开始

现在我们来看看学校里是怎么教编程语言的。

# Computer Science 101

![](https://coding.net/u/hoteam/p/Cache/git/raw/master/2016/11/2/1-eu4cWRZXUt3ybNFzeT-q8Q.png)

大学里经常在计算机科学与技术的系列课程中开设某一门编程课，并且常常看做数学或者电子课程的扩展。估计你也经常会听到如下的论述:计算机科学与技术的课程并不能让你成为编程大拿，就像刷墙的并不能成为美术大师一样。而在2016年里，还是有很多大学像教数学一样教授计算机科学与技术。在这种背景下，很多编程入门级的课程都关注与C这样的底层抽象语言，或者专注于数学的类似于MATLAB这样的语言。
![](https://coding.net/u/hoteam/p/Cache/git/raw/master/2016/11/2/1-8yWwh_UrWeoxYSVsWTnEBA.png)
上图就是TIOBE对于编程流行度的排行榜，而在2014年里Python逐步代替Java成为最广泛的美国计算机科学与技术语言:
![](https://coding.net/u/hoteam/p/Cache/git/raw/master/2016/11/2/1-728HWv2YP3PjY1_QmGQg1g.png)
而如果我们专注于工程应用领域的语言流行度，则有些不同:
![](https://coding.net/u/hoteam/p/Cache/git/raw/master/2016/11/2/1-fUxhG3xtbuyAH-NCPYs4lQ.png)
超过一半的开发者在使用JavaScript，JavaScript的浪潮从前端开始逐步席卷到后端，并且逐步发展到游戏开发与物联网等领域。而对于JavaScript开发者需求量也仅次于Java:
![](https://coding.net/u/hoteam/p/Cache/git/raw/master/2016/11/2/1-Nju6ZEORusBE-4UB290Ftw.png)

在过去的两年中，超过5000名开发者在Free Code Camp的帮助下寻找到了合适的开发工作。我并不是因为我本身负责教授JavaScript就去推广它，而是因为JavaScript是最易于找到第一份工作的语言所以我选择去教授他。

# Factor #1:The Job Market
如果你是完全处于个人的兴趣爱好而学习编程，那么你可以跳过本节。不过[绝大部分](https://medium.freecodecamp.com/we-asked-15-000-people-who-they-are-and-how-theyre-learning-to-code-4104e29b2781#.30hlfqj32)学习编程的人都希望能够获得一份不错的工作。就像我早前提及的，Java是目前看来最受雇主欢迎的语言，而JavaScript紧随其后。不过这其中有个很大的因素就是Java已经流行了20多年，很大一部分岗位来源于对于旧系统的维护需求。
![](https://coding.net/u/hoteam/p/Cache/git/raw/master/2016/11/2/1-EanhlHoMIsF-By0gRrAcYQ.png)

从上图可以看出现在大概2.7个Java开发者竞争一个岗位，而PHP与iOS差不多是两个人竞争一个岗位。

# Factor #2:The long term prospects
差不多现在开源项目中，每个JavaScript项目的Pull Request请求数是Java、Python、Ruby平均数的两倍，从这一点看来，JavaScript比其他任何的流行语言都要发展迅速。
![](https://coding.net/u/hoteam/p/Cache/git/raw/master/2016/11/2/1--GxMW33X9Gb5lboyN02hKw.png)
而JavaScript生态圈也不断受益于来自Google、Microsoft、Facebook以及Netflix等公司的投资，譬如JavaScript生态圈中的著名的静态扩展TypeScript有超过100位的开源贡献者，其中很多都是来自于Microsoft或者Google的雇员。目前收购了Sun的Oracle也在寻求利用这种社区参与度扩大Java的影响力。

# Factor #3:Difficulty To Learn
![](https://coding.net/u/hoteam/p/Cache/git/raw/master/2016/11/2/1-d8TITW3skawGd-ioyHh2nQ.png)

估计大部分开发者都同意相对高层的脚本式语言相对易于学习，JavaScript、Python以及Ruby就是属于这个范畴。虽然不少学校在教Java或者C++，不过它们是真的不容易学啊。

# Factor #4:Projects you can build with it
这一点正是JavaScript耀眼之处，JavaScript可以运行在任何支持浏览器的设备上，你可以用JavaScript构建任何应用，然后随处分享。正如Stack Overflow的合伙人Jeff Atwood所说:所有能够用JavaScript实现的应用最终都会转到JavaScript中。Java曾经也是主打一次编译，到处运行，估计你还记得[Java Applets](http://motherboard.vice.com/read/a-brief-history-of-the-java-applet)，近两年才被Oracle去掉这一特性。而Python也面临同样的问题，这里我们列举几个好玩的用JavaScript构建的游戏:
- [1970s style Simon game](http://s.codepen.io/adambeagle/debug/qOamaz)
![](https://coding.net/u/hoteam/p/Cache/git/raw/master/2016/11/2/1-i-bre5pF0rk6Wgz5yjugjw.png)

- [Conway’s Game of Life](http://s.codepen.io/safx/debug/Ewcym)
![](https://coding.net/u/hoteam/p/Cache/git/raw/master/2016/11/2/1-GtVQI4LUU0-_Soyhi93LBg.png)

- [Star Wars-themed Wikipedia Search](http://s.codepen.io/duttakapil/debug/BKGjOa) 
![](https://coding.net/u/hoteam/p/Cache/git/raw/master/2016/11/2/1-jkx-Vf8esZ0GYv_L6S2i9A.png)

- [A roguelike dungeon crawler game](http://s.codepen.io/Megabyteceer/debug/qbXJMQ)
![](https://coding.net/u/hoteam/p/Cache/git/raw/master/2016/11/2/1-PiI9yXaUNJANSffWvdotDQ.png)

# Objection #1:JavaScript不是运行的很慢吗？
JavaScript其实是一个非常高效的语言，NodeJS本身是比Python、Ruby以及PHP要快的，它也近似于C++、Java以及Go这些编译语言。
![](https://coding.net/u/hoteam/p/Cache/git/raw/master/2016/11/2/1-h91cfcE8NlgyHfm4CLbV6w.png)

# Objection #2:But JavaScript isn't statically typed
类似于Python或者Ruby，JavaScript同样是一门动态类型语言，很方便，不过很容易引起动态类型转化与验证的问题。譬如我以为我操作的是一个数组:
```
exampleArray = [1, 2]
-> [1, 2]
exampleArray.length
-> 2
```
然后如果一不小心转化为了字符串，那就糟了:
```
exampleArray = “text”
-> “text”
exampleArray.length
-> 4
```

# Objection #3:我打算写个移动应用来着

[Angular Cordova](http://ngcordova.com/)与[React Native ](https://facebook.github.io/react-native/)都是不错的选择。
![](https://coding.net/u/hoteam/p/Cache/git/raw/master/2016/11/2/1-6RsFHNgrzFyX-9p37FVtpA.jpeg)































