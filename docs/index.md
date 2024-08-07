# **写在前面**

在抒情之前我想先介绍一下这个项目会囊括的内容，如果你有建议和补充，欢迎提出 issue 或 PR：

- 信息的搜索与整理：找/读/存 论文/教程/书籍/博客/视频/项目/工具/资源
- 开发环境：关于计算机你应该知道的，以及配环境经验、我的开发环境配置
- 编程入门：快速上手编程与 AI
- 地球物理相关（地震学）：数理基础的学习、学习资源、软件使用以及若干杂项
- 给本科生的碎碎念：思考你的学习与生活

## **为什么会开始这个项目**

这一切都要回到一年多之前我刚开始本科生科研项目的时候。虽然有着师兄师姐的帮助，再加上高中信息奥赛经历积累的一些经验，但我还是感觉自己陷入了一个陌生的漩涡。安装WSL、配置远程软件、整理论文、以及埋头做完了半本地震学的习题……我在一个又一个经验帖中寻找答案，在苦恼看不明白论文的同时，也在被技术性问题不断拷打着。我当时就想，如果有一个这样的教程把各位师兄师姐的传承和自己的经验都整理出来，会省下多少事。我当时就决定既然没有，那就自己写一个吧，尤其是在树洞中的 [CSDIY](https://csdiy.wiki/) 项目更是让我深受鼓舞。后来与身边其他专业的同学交流时，发现他们也对一些本来应该是很基本的问题云里雾里，而对绝大多数人来说，自己啃一遍 CSAPP 这样的大部头或是画大量的时间来理清这些基础都有点浪费和不太现实。所以我更下定决心要把自己的些许经验分享出来，让大家少走一点弯路，哪怕只帮到了一个人，也是极好的。

## **这个项目适合谁**

在众多高效工具流行的现代，做科研几乎可以分离为架子（技术知识）和里子（学科知识）。而我只是一个刚刚看到学术门槛的新手，没有什么学术水平。所以我会更多专注于分享一些科研工具，也就不会让你的学术水平产生飞跃，只是能节省一点时间。这个项目希望帮助到本科低年级的同学，建立起一些基本概念，不要像黑盒一样使用电脑。在不涉及地球物理相关知识的部分，我会力求内容通用一点，尽量适用所有做干实验的学科。不过鉴于我开始接触科研时已经有了一些积累，再加上这也算是一种回顾，难免会有疏漏或想当然地以为某些部分不是问题，还望见谅。但我能注意到的点都会尽力事无巨细，Windows（WSL）和 Mac OS 尽量都提供一份，所以有些部分可能比较琐碎和显而易见，可能你早已掌握，还望见谅。

另外，互联网上已经充满了各种各样的经验帖，其中有很多质量都非常高。所以本着避免重复造轮子的理念，我在介绍时会穿插一些引用或链接，或者只是简单地提及某个工具。这个项目的首要目的在于提醒大家思考某些可能性，然后才是提供解决方案。善用百度/谷歌/知乎，可能你会得到更好的答案。

## **如何使用这个项目**

除了每个部分的若干小节之外，点击左边每个部分的总标题，还会有开始正文之前的漫谈，感兴趣的可以看我啰嗦两句。入门介绍的内容仅供参考，很多地方不会保证严谨，如果你有深入了解的兴趣，务必搜索相关书籍或请教科班人士纠正认识（虽然我也在修计算机双学位）；配置开发环境的部分建议一气呵成，放在动手实操的最开始。地球物理相关知识的部分或许对相近学科也有些帮助。碎碎念则是我对本科生活的一些想法，如果你还是一个有些迷茫或懵懂的新生，也许某些点可以帮到你。

如果你只是初入校园的新生，请不必焦虑和急躁。我的建议是根据这个项目的各个主题尝试自行搜索了解一下相关知识，这样会更加专业和深刻。可以放心打好基础（大部分是通用的），借此机会多多探索自己的兴趣。一定要打破高中埋头做题的惯性，暂时放下功利性的考虑，去积极主动探索自己的未来。也许你最后会改变当初的想法，觉得自己应该放弃做学术（或者还是应该回去做学术）。

如果你已经开始接触科研，可以根据自己的需要选择性地阅读，并且可以把注意力放在相关经典书籍的学习上。即使工具学得再多再好，如果一点知识都没有，也不可能做出什么有价值的发现。

另外，我强烈建议同时按需查看 [CSDIY](https://csdiy.wiki/)，和计算机打交道，多少应该了解一些相关知识。

## **特别鸣谢**

感谢大学以来所有老师和师兄师姐对我的指导和帮助，一个人的力量是有限的，我希望把我感受到的帮助传递给大家。

感谢 [CSDIY](https://csdiy.wiki/) 项目，感谢所有分享自己经验的人，感谢开源社区的贡献者。

感谢 @、@、@在我写作过程中的建议和反馈，在他们的帮助下，我离白居易写诗时老妪能解的境界[^1]接近了不少。

## **表达支持**

如果你觉得这个项目对你有帮助，请点个 star 支持一下吧。

[^1]: “白乐天每作诗，问曰解否？妪口解，则录之；不解，则易之。” —— 宋·释惠洪《冷斋夜话》卷一
