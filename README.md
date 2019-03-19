- [前端小白也能快速学会的博客园博客美化全攻略](#前端小白也能快速学会的博客园博客美化全攻略)
  * [美化方法论简介](#美化方法论简介)
  * [准备工作](#准备工作)
    + [js权限申请](#js权限申请)
  * [如何模仿一个博客园的自定义风格(样式css+动态效果js)?](#如何模仿一个博客园的自定义风格样式css动态效果js)
  * [markdown样式自定义](#markdown样式自定义)
  * [在页面顶部添加"自定义搜索"功能](#在页面顶部添加自定义搜索功能)
  * [在页面顶部添加"音乐播放器"(Flash)播放背景音乐](#在页面顶部添加音乐播放器Flash播放背景音乐)
  * [在页面顶部添加"Fork me on Github"图标](#在页面顶部添加fork-me-on-github图标)
  * [为导航栏设置渐变背景色](#为导航栏设置渐变背景色)
  * [在公告栏添加滚动文字](#在公告栏添加滚动文字)
  * [在公告栏加入自己的社交网络账号 - 图片链接](#在公告栏加入自己的社交网络账号---图片链接)
  * [在公告栏添加一个能旋转的rss图标](#在公告栏添加一个能旋转的rss图标)
  * [在公共栏添加"小人时钟"(Flash)](#在公共栏添加小人时钟(Flash))
  * [在公共栏添加"站点统计"功能](#在公共栏添加站点统计功能)
  * [在公告栏中加入"自定义搜索"(PopUp弹窗)](#在公告栏中加入自定义搜索PopUp弹窗)
  * [页面底部添加"回到顶部" + "收藏" + "快速评论"功能](#页面底部添加回到顶部--收藏--快速评论功能)
  * ["自动移动的目录"功能](#自动移动的目录功能)
  * [改进评论的显示样式](#改进评论的显示样式)
  * [在公告栏添加"友情链接"](#在公告栏添加友情链接)
  * ["博客签名"功能](#博客签名功能)
  * [禁用页面的"选中复制"功能](#禁用页面的选中复制功能)
  * [不显示底部广告](#不显示底部广告)
  * [修改导航栏(修改部分链接的文字 + 增加下拉菜单)](#修改导航栏修改部分链接的文字--增加下拉菜单)
  * [微博秀的嵌入(支持http/https访问)](#微博秀的嵌入支持httphttps访问)
  * [分享组件的嵌入(支持http/https访问)](#分享组件的嵌入支持httphttps访问)
  * [打赏功能](#打赏功能)
  * [复制文字时自动加版权](#复制文字时自动加版权)
  * [隐藏博文右下角的"反对"](#隐藏博文右下角的反对)

# cnblogs-theme-xSimple
博客园主题-Extremely Simple(极简)

这是一款前端小白也能快速上手的给力博客园主题~

[本人博客园博客](https://www.cnblogs.com/enjoy233/)的所有代码在此github项目的[src文件夹](https://github.com/yanglr/cnblogs-theme-xSimple/tree/master/src)中~

## 准备工作

1. 首先你得有个cnblogs博客
2. 申请js权限


**源码使用步骤：**

1. 打开 博客后台管理 → “设置”
2. 在博客皮肤选项卡中将博客皮肤设置为： `LessIsMore`
3. 将`src`文件夹下的页面定制.css 复制到 页面定制CSS代码 代码框内
4. 将同一文件夹下的 页首.html 复制到 页首Html代码 代码框内
5. 将同一文件夹下的 页尾.html 复制到 页脚Html代码 代码框内
6. 保存，即可见效。

### js权限申请

登陆后依次点击“我的博客” → “管理” → “设置”，在下拉后找到“博客侧边栏公告”，后方有一个“申请js权限”。

![Apply_js](https://www.cnblogs.com/images/cnblogs_com/enjoy233/1389971/o_Apply-js-with-Content.jpg)

或者也可进博客园园子页面(<https://home.cnblogs.com/feed/all/>)，发状态@博客园团队，申请开通js权限。

也可发个邮件到[contact@cnblogs.com](mailto:contact@cnblogs.com)申请js权限。


**申请时内容模板已为你备好:**

> 尊敬的博客园管理员：
>
> 本人请求申请开通js权限，希望能够把博客修饰的漂亮点，点缀自定义js插件效果，希望管理员可以批准，多谢~


提交完申请，会弹出提示:

`JS权限申请已提交，待审核。`

剩下的就是耐心等待了，一般来说挺快就会通过。如果设置页面上公告栏标题右侧不存在“申请js权限”，说明已成功开通js权限。



## 如何模仿一个博客园的自定义风格(样式css+动态效果js)?

模仿一个cnblogs的全局css，只需打开Chrome浏览器，按下F12，找里面的skin css和custom css。


## markdown样式自定义

默认markdown状态下，代码中的字比较小。



## 在页面顶部添加"自定义搜索"功能


效果图:

![customSearch1](https://files.cnblogs.com/files/enjoy233/customSearch1.bmp)



## 在页面顶部添加"音乐播放器"(Flash)播放背景音乐


![163music_palyer](https://raw.githubusercontent.com/yanglr/Beautify-cnblogs/master/images/163music_player.bmp)



**表现形式一：单曲播放** (type = 1)

**表现形式二：列表播放** (type = 0)

![playList](https://raw.githubusercontent.com/yanglr/Beautify-cnblogs/master/images/163playList.bmp)


效果图: 

![163music_player](https://files.cnblogs.com/files/enjoy233/163music_player.gif)


## 在页面顶部添加"Fork me on Github"图标


效果见[本页面](https://www.cnblogs.com/enjoy233/p/10328361.html)右上角。


如果想对该图标进行更多颜色或位置的设置，请参考：[GitHub Ribbons - The GitHub Blog](https://github.blog/2008-12-19-github-ribbons/).



## 为导航栏设置渐变背景色



## 在公告栏添加滚动文字


效果图:

![slide_words](https://files.cnblogs.com/files/enjoy233/slide_words.gif)




## 在公告栏加入自己的社交网络账号 - 图片链接

效果图:

![socialLinks](https://files.cnblogs.com/files/enjoy233/socialLinks.gif)



## 在公告栏添加一个能旋转的rss图标

效果图:

![rss_roate](https://files.cnblogs.com/files/enjoy233/rss_rotate.gif)



## 在公共栏添加"小人时钟"(Flash)

效果图: 

![clock_result](https://files.cnblogs.com/files/enjoy233/clock_run.gif)



## 在公共栏添加"站点统计"功能


## 在公告栏中加入"自定义搜索"(PopUp弹窗)


效果图:

![customSearch2](https://raw.githubusercontent.com/yanglr/Beautify-cnblogs/master/images/custom_search2.bmp)





## 页面底部添加"回到顶部" + "收藏" + "快速评论"功能



效果图:

![custom_Tool_Bar](https://files.cnblogs.com/files/enjoy233/CustomtoolBar.gif)


## "自动移动的目录"功能

效果图: 

![autoMoveContents](https://files.cnblogs.com/files/enjoy233/autoMoveContents.gif)



## 改进评论的显示样式
这里我索性改成了熟悉的微信聊天的样式。

**效果图:**

![custom_comments](https://files.cnblogs.com/files/enjoy233/custom_comments.bmp)




## 在公告栏添加"友情链接"

**设置方法(见下图):**

编辑分类 -> 添加链接，设置好后公告栏上会显示相关内容，不过可能会有延时，需要等一会。


![friend_links](https://files.cnblogs.com/files/enjoy233/cnblogs-Link.bmp)

效果图:

![friend_link_result](https://files.cnblogs.com/files/enjoy233/friendLink.bmp)



## "博客签名"功能

虽然cnblogs博客后台提供了"博客签名"功能，测试发现该该方法实现的博客签名在IE中打开时不显示，只好改为用跨浏览器的JQuery来实现了。


## 禁用页面的"选中复制"功能

综合考虑后，采用了后文中的"复制博客内容时自动加版权说明"。



## 不显示底部广告




## 修改导航栏(修改部分链接的文字 + 增加下拉菜单)

效果图:

![custom-nav](https://raw.githubusercontent.com/yanglr/Beautify-cnblogs/master/images/custom-navigate.bmp)

## 微博秀的嵌入(支持http/https访问)

效果图(见本博客左侧公告栏):

![weibo_show](https://files.cnblogs.com/files/enjoy233/weibo_show.gif)



## 分享组件的嵌入(支持http/https访问)

效果图:

![baiduShare](https://files.cnblogs.com/files/enjoy233/BaiduShareTool.gif)



## 打赏功能

本博客基于开源插件 [tctip](<https://github.com/greedying/tctip>) v1.0.3 来实现~

效果图:

![custom-nav](https://files.cnblogs.com/files/enjoy233/reward.gif)

还看到过一个不错的方法，亲测有效：[自制简易打赏功能 - EritPang](https://www.cnblogs.com/eritpang/p/7465484.html) .


## 复制文字时自动加版权

**效果图:**

![copy-With-Copyright](https://raw.githubusercontent.com/yanglr/Beautify-cnblogs/master/images/copyWithCopyright.bmp)



##  隐藏博文右下角的"反对"按钮

效果请见[本人博客页面](https://www.cnblogs.com/enjoy233/p/10328361.html)右下角。
