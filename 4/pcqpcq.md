
[小丑](https://github.com/pcqpcq) 的 2014 -> 2015
-------------  
### 一. 2014 总结
我有预感这会是一篇很长的总结。  
我有预感我每次总结都会想骂人。  
作为一个对产品技术和美术都有追求的程序员，这一年貌似仍然真的只是在追求……  

#### 技术
1. 在我自己研究答题卡识别的时候，很高兴接触到了 [OpenCV](http://www.opencv.org/) 这样一个到现在我都觉得很伟大的图形图像处理项目，它的文档完整性和本身的技术性都让我很佩服，特别是在看到它连Java版本里的注释文档都是认真写过的之后。再回头看看Apache老大哥的 [POI项目](http://poi.apache.org/) 的代码和注释，我只能呵呵了。特别感谢CSDN专栏 [【OpenCV】入门教程](http://blog.csdn.net/column/details/opencv-tutorial.html)，从原理上理解了很多东西，深入浅出。  
    文档和代码规范其实是非常重要的东西，太多人都忽视了。  
2. 工作需要，让我认识了两个平时不太会接触到的技术。其中一个是做按键精灵，从这篇博文 [Recording and replaying events with Android](http://code.lardcave.net/entries/2009/08/01/160953/) 里学到不少原理，虽然文章不长，但是已经足够。而且主要是 ["Talk is cheap, show me the code"](https://github.com/torvalds) ——他给了代码:)  
3. 另外一个是内存修改，也就是所谓的金手指。刚开始自己根据网上说的原理尝试了不少时间却一直有问题，便放在一边。后来某天晚上玩个游戏一直玩不过，一个不爽，发誓一定要把它内存改了，于是就发现了这个神奇的项目 [ScanMem](https://github.com/coolwanglu/scanmem) 以及它的Android实现 [aScanMem](http://sourceforge.net/projects/ascanmem/)，才发现原来我离成功就差那么一点点，无奈对Linux下C编程的API确实不熟悉，走了个大弯路。这期间也接触到所谓 [Android应用程序永久获取root权限方法](http://hold-on.iteye.com/blog/1901152) ，虽然我大学里自学的Linux知识终于能用上一些了，但是深深感概也只有国内这种不自觉的环境里才会有这种“在用户手机上永久root”的想法存在，开放的Android真的太不安全了，看看 [RootTools](https://github.com/Stericson/RootTools) 的做法多好，只是用类似session的方法暂时保留root授权，哪像那帮人啊，都去申请专利了。  
    总结起来，相比直接获得开源项目然后就拿来用而言，自己动手尝试实现过会更好，理解也更深，虽然这个过程可能会花费你不少时间。简单的拿来主义并不会让人成长，莫伸手，伸手必被抓。  
4. 其他的收获就不深了，今年新接触到的东西里，相比 [RxJava](https://github.com/ReactiveX/RxJava) 和 [RxAndroid](https://github.com/ReactiveX/RxAndroid) 以及 [Scale](https://github.com/lauris/awesome-scala) 这种我觉得更多的只是一种思维的转变而言，在 [Kotlin, the Swift of Android](http://blog.gouline.net/2014/08/31/kotlin-the-swift-of-android/) 里介绍的被称为比肩Swift的 [Kotlin](https://github.com/JetBrains/kotlin) ，所带来的改变会更有实质意义一点，现在也处在发展阶段，感觉会是值得关注的。  
5. 另外，执续集成 [Travis CI](https://travis-ci.org/) 以更自动化更快的 [提高Android程序质量](https://github.com/stephanenicolas/Quality-Tools-for-Android) , 还有动态加载，这些应该已经开始疯狂使用了吧，开源方案也做得挺好的，像 [AndroidDynamicLoader](https://github.com/mmin18/AndroidDynamicLoader) 和 [dynamic-load-apk](https://github.com/singwhatiwanna/dynamic-load-apk)。  
6. 接触了一段时间WindowsPhone，发现按微软的尿性果然封装了所有能封装的东西。特别是那个Blend for Virsual Studio 啊！Google你怎么不搞一个啊！搞什么svg啊！能不能不要这么技术向啊！虽然也有开源方案能向下兼容，比如 [MrVector](https://github.com/telly/MrVector) 和 [svg2android](https://github.com/inloop/svg2android)，但是感觉这样做动画还是没有Blend来得优雅啊！  
7. 一年下来，自然也少不了每周阅读 [Android Weekly](http://androidweekly.net/)，非常感谢他们的无私奉献！

#### 产品  
和去年一样，这一年看了很多的产品，留下的不多，有印象的就更少了。  
1. [知乎](http://www.zhihu.com/)，从创立起初就关注到现在发展得确实不错，果然没有看错它，也从社区里的其他人身上学到不少知识，虽然最初创意是来自国外的。  
2. [Morning Routing](https://play.google.com/store/apps/details?id=net.havchr.mr2)，一直在用，体验确实做得很好，虽然只是个闹钟。除了关闹钟界面居然不给出时间变相逼我起床以外，都挺好的……现在做个App真不容易，除了功能要差异化，还得把“脸”做好看，“身材”还不能比别人差。这已经不是以前那个“能用就行”的年代了。  
3. [豆瓣东西](http://dongxi.douban.com/) 和 [酷安](http://www.coolapk.com/)，关注并从它们身上学到一种做社区的新方法，比较有成就感。  
4. [Sky Force](https://play.google.com/store/apps/details?id=pl.idreams.skyforcehd)，做得真好，顺便感谢它让我不爽因而有动力去实现内存修改。  
5. [Next](http://next.36kr.com/posts)，虽然创意也是来自国外的。  

#### 美术  
美术其实是个非常重要的东西，虽然现在是写程序，但是任何人多少都还是要培养下自己的艺术细胞的，万一哪天不小心成了代码艺术家。    
1. [Sketch](http://sketchcn.com/) 确实是个很棒的工具，要是大家都用它该有多好啊，别老是来问到底要多少像素。  
2. [Material Design](http://www.materialup.com/) 是个很棒的设计语言，亮瞎了都，Google这把干得漂亮。  

#### 生活
1. 一团糟。
2. 除去戴了眼镜换了手表买了Kindle然后发现这玩意确实不是用来盖泡面的但是阅读体验却超棒并且深深觉得不错因而看了不少书以外，准备把头发留长然后换个帅帅的发型无奈发现原来自己长得还没有帅到掉渣的地步啊！  
    其实这不是个看脸的世界，它只是越来越注重审美。
3. 认识了一群朋友，发现 ~~[Trinea](https://github.com/trinea)   居然初三就开始编程，尼玛。~~什么东西都应该要赢在起跑线上啊，我高二家里才有电脑啊我去！不到一个月还花30块大洋找人重装了啊！至此走上360安全卫士的不归路啊你妹！(然后现在发现原来初三就开始编程的是 [代码家](https://github.com/daimajia) ……让我一个人安静会儿……）
4. 羽毛球水平上涨不少，感觉自信了许多。

### 二. 2015 展望
我就不说什么新的一年新的开始不再熬夜好好做人孝敬爸妈之类的话了，因为说了反而不会做。生活是一天一天走出来的，过好当下，365天太久，只争朝夕。

1. 把自己的时间按周为单位分配好，有节奏的前进。  
    每周有一天找些朋友坐下来聊聊天，周末出去走一走玩一玩，看看这个世界又发生了什么新鲜事。曾经有个人说程序员的世界观决定了这个世界会变成什么样子，因为他们才是真正改变世界的人吧。
2. 把剩下的没看完的几本书和一些其他资料都看完吧，特别是[《浪潮之颠》](http://book.douban.com/subject/24738302/) —— 就像去年看电子游戏的历史一样，了解历史是为了让自己不要成为历史。
3. [Android Wear](http://wearui.co/) 的想像空间很大，还是可以关注的，争取年前把做的表盘上架。
4. 一直以来我从这个世界获得了太多太多，我总觉得应该为这个世界留下点什么。慢慢把我的所学和心得都记录下来并分享出去，希望能帮助到别人。一直在追求，是到了开始创造的时候了吧。
5. 最后，博观而约取，厚积而薄发，一直作为座右铭并实践着，来年也一样。
6. 最最后，诺兰电影作品中的小丑Joker有句“名言”，Why so serious? —— 不要太较真。来年要不断提醒自己。
