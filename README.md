# 豆瓣fm 192k mp3下载器

## 缘由

首先声明，我非常喜欢豆瓣fm以及依赖它。尽管大部分时间我都可以在有网络的环境下进行工作，但是，有时会去到没有网络的地方。但是我还是想听一下我的红心音乐。于是我就想下载我的红心音乐。

尽管现在已经有很多红心音乐的下载器，不过它们都是通过<http://douban.fm/mine?type=liked>来获取红心列表，在根据列表进行下载。通过这样下载的音乐都是64kbps的码率，压缩太大了。

我开通了douban.fm Pro，发现192kbps码率的音乐听起来确实比64kbps的好很多。于是我需要下载192kbps的mp3，以便我在没网络的时候也能够听音乐。

于是就有了这段javascript。

## 需求

首先你需要一个Chrome或者Firefox，然后安装插件[豆瓣FM-Hacker](https://chrome.google.com/webstore/detail/豆瓣fm-hacker/pjpdhffcchclaedfnlkmpacghddkpgjh)。我的工作大部分是直接基于这个插件。懒得重复造轮子，直接站在巨人的肩膀上。

## 使用

1. 打开<http://douban.fm>
1. 在douban.fm的页面打开console。
1. 将这段下载192kbps mp3的javascript粘贴进入console，按下回车

好，剩下的就是等待完成了。
