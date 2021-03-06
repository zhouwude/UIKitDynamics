#UIKitDynamics

[![LICENSE](https://img.shields.io/badge/license-MIT-green.svg?style=flat)](https://raw.githubusercontent.com/xiaofei86/UIKitDynamics/master/LICENSE)&nbsp;
[![PLATFORM](https://img.shields.io/cocoapods/p/LPNetworking.svg?style=flat)](https://developer.apple.com/library/ios/navigation/)&nbsp;
[![SUPPORT](https://img.shields.io/badge/support-iOS%207%2B%20-blue.svg?style=flat)](https://en.wikipedia.org/wiki/IOS_7)&nbsp;
[![BLOG](https://img.shields.io/badge/blog-xuyafei.cn-orange.svg?style=flat)](http://xuyafei.cn)&nbsp;

学习UIKitDynamics时做的Demo，把UIKitDynamics的所有Behavior都进行了实践，还有三个实际场景的应用和一个独立项目。UIKitDynamics是iOS7新加入UIKIt家族的动画，使用场景比较少。由于是基于UIView的动画，效率肯定不会有CoreAnimation高。但是借此可以做出来复杂的仿真动画效果，甚至可以算是简单的2D物理引擎了。

* 由于GIF图片较多，首次加载的时候播放很卡，可以等所有图片加载完再看。

#独立项目（LPSolarSystem）

独立项目使用UIKitDynamics模拟太阳系制作随机数生成器。图片由于GIF帧数过低，效果很差，可以在[这里](https://github.com/xiaofei86/UIKit-Dynamics/raw/master/Images/11.mov)下载视频或者在项目找到Images/11.mov观看。

<img src = "https://github.com/xiaofei86/UIKit-Dynamics/raw/master/Images/11.gif">

##重力行为（UIGravityBehavior）
[图片备用链接](http://g.picphotos.baidu.com/album/s%3D680%3Bq%3D90/sign=9090b90bc81b9d168ec79969c3e5c5b2/a8773912b31bb0511e4f98fc307adab44bede0ff.jpg)

<img src = "https://github.com/xiaofei86/UIKit-Dynamics/raw/master/Images/1.gif">
##碰撞行为（UICollisionBehavior）
[图片备用链接](http://d.picphotos.baidu.com/album/s%3D680%3Bq%3D90/sign=8902b8faaed3fd1f3209a13200755422/63d0f703918fa0ec03734fd9209759ee3c6ddba9.jpg)

<img src = "https://github.com/xiaofei86/UIKit-Dynamics/raw/master/Images/2.gif">
##连接行为（UIAttachmentBehavior）
[图片备用链接](http://g.picphotos.baidu.com/album/s%3D680%3Bq%3D90/sign=9ed898fc307adab439d0184bbbefc221/8435e5dde71190ef1007b90bc81b9d16fcfa6061.jpg)

<img src = "https://github.com/xiaofei86/UIKit-Dynamics/raw/master/Images/3.gif">
##吸附行为（UISnapBehavior）
[图片备用链接](http://g.picphotos.baidu.com/album/s%3D680%3Bq%3D90/sign=627e8a0af61f3a295ec8d6c6a91ecd0c/4bed2e738bd4b31c692bbf6f81d6277f9f2ff8cb.jpg)

<img src = "https://github.com/xiaofei86/UIKit-Dynamics/raw/master/Images/4.gif">
##推动行为（UIPushBehavior）
[图片备用链接](http://a.picphotos.baidu.com/album/s%3D680%3Bq%3D90/sign=82d0f7b4332ac65c6305657bcbc9c32c/80cb39dbb6fd5266684117c0ad18972bd50736ff.jpg)

<img src = "https://github.com/xiaofei86/UIKit-Dynamics/raw/master/Images/5.gif">
##仿真行为（UIDynamicItemBehavior）
[图片备用链接](http://g.picphotos.baidu.com/album/s%3D680%3Bq%3D90/sign=62de8a0af61f3a295ec8d6c6a91ecd0c/4bed2e738bd4b31c698bbf6f81d6277f9f2ff8ab.jpg)

<img src = "https://github.com/xiaofei86/UIKit-Dynamics/raw/master/Images/6.gif">
##综合应用（UIPendulumViewController）
[图片备用链接](http://h.picphotos.baidu.com/album/s%3D680%3Bq%3D90/sign=65edcef20f24ab18e416e23f05c197f0/14ce36d3d539b6000d782463ef50352ac75cb7ab.jpg)

<img src = "https://github.com/xiaofei86/UIKit-Dynamics/raw/master/Images/7.gif">
##场景应用（UIPhotoWallViewController）
[图片备用链接](http://b.picphotos.baidu.com/album/s%3D680%3Bq%3D90/sign=35cd70e21b950a7b71354dcc3aea13e4/bd315c6034a85edff474d5f74f540923dc54756d.jpg)

<img src = "https://github.com/xiaofei86/UIKit-Dynamics/raw/master/Images/8.gif">
##场景应用（UITransformViewController）
[图片备用链接](http://g.picphotos.baidu.com/album/s%3D680%3Bq%3D90/sign=d07917139652982201333acbe7f10af6/241f95cad1c8a7865f4d61da6109c93d71cf50fa.jpg)

<img src = "https://github.com/xiaofei86/UIKit-Dynamics/raw/master/Images/9.gif">
##场景应用（UIAlertViewController）
[图片备用链接](http://g.picphotos.baidu.com/album/s%3D680%3Bq%3D90/sign=9e4298fc307adab439d0184bbbefc221/8435e5dde71190ef109db90bc81b9d16fcfa60fb.jpg)

<img src = "https://github.com/xiaofei86/UIKit-Dynamics/raw/master/Images/10.gif">
