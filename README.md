# 我开发的一些macOS系统实用插件

-----------------

## 1. Alfred Workflow
- [优越加速](https://www.kycloud.co)Workflow

  优越加速Alfred Workflow，自动获取服务器信息，支持服务器ping值排序，支持热键生成对应条目的ss/ssr二维码，支持surge配置信息自动生成，支持自动/手动获取插件更新。

  下载地址: [Release](https://github.com/wizyoung/workflows.kyoyue/releases)

  操作GIF示意：

  ![](https://github.com/wizyoung/workflows.kyoyue/blob/master/gofree.gif?raw=true)


  ![](https://github.com/wizyoung/workflows.kyoyue/blob/master/ping.gif?raw=true)


  ![](https://github.com/wizyoung/workflows.kyoyue/blob/master/update.gif?raw=true)

  **使用说明**：
  - 首次使用键入`yyset`输入优越加速email和登录密码
  - `gofree`  自动获取服务器IP信息等, 该指令设定为查询一次后，信息缓存在本地10分钟，10分钟内再次查询从缓存中读取信息
  - `gofree ping` 对所有服务器进行ping 3 次，去平均值排序，超过1000ms的直接判断为超时

  以上两条指令，按下`cmd`或者`option`可弹出指定服务器的ss或者ssr二维码

  - `gofree surge` 将服务器信息配置成surge所需格式，根据用户指令(按下`fn`或者`ctrl`)复制到剪切板
  - `gofree update` 手动检查更新，有新版本时选择是否自动下载更新安装。workflow每3天自动检查更新一次

## 2. Popclip
- 谷歌翻译

  鼠标划中待翻译句子，点击翻译图标，右上角弹出翻译。中译外和外译中翻译，支持自主选择外语语种。支持选择谷歌翻译服务器[translate.google.cn或translate.google.com]，墙内外均可使用。可选右上角bubble弹出翻译，或者屏幕正中弹出翻译结果窗。可选翻译结果是否复制到系统剪贴板。
  
  更多详情和下载地址, [点击前往](https://github.com/wizyoung/googletranslate.popclipext)
  
  操作GIF示意：
  
  ![](https://raw.githubusercontent.com/wizyoung/googletranslate.popclipext/master/3.gif)
  
  ![](https://raw.githubusercontent.com/wizyoung/googletranslate.popclipext/master/4.gif)
  
- 去除文本中不必要的换行和空格

  “借鉴”文案或者做笔记的时候喜欢去一些网站如百度文库拷贝文字，经常发现拷贝下来的文字中被插入了很多空格或者换行，非常烦人。本插件就是为了解决这个问题。
  
  下载地址: [点击下载]()
  
  操作GIF示意:
  
  pass
  
- 
  
