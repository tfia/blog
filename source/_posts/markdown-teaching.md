---
title: Markdown简单扫盲
date: 2020-08-15 19:21:12
tags: 
	- 技术
thumbnail: https://i.loli.net/2020/09/19/MEmNU2WJeqzGnd3.png
---

天下苦富文本久矣！
<!--more-->

Markdown是一种轻量级标记语言， 它允许人们使用易读易写的纯文本格式编写文档，然后转换成有效的XHTML（或者HTML）文档。

Markdown彻底解放了写作生产力，彻底省去了费心费力排版的时间，让作者可以专注内容本身。所有博客平台，像是知乎、简书、CSDN，以至于电子邮件，基本都支持markdown语法写作，微信公众号的消息也可以由markdown源码生成。

以下是Markdown代码的一些示例：

---

# 标题部分

*注意#和内容之间有一个空格*

# 一级标题
```markdown
# 这是一个一级标题
```

## 二级标题
```markdown
## 这是一个二级标题
```

### 三级标题
```markdown
### 这是一个三级标题
```

#### 四级标题
```markdown
#### 这是一个四级标题
```

##### 五级标题
```markdown
##### 这是一个五级标题
```

# 字体

**粗体**
```markdown
**这是粗体**
```

*斜体*
```markdown
*这是斜体*
```

# 其他

> 引用
```markdown
>这是一段被引用的文字
```

[链接](d.grassfield.xyz)

```markdown
[这是一个链接](d.grassfield.xyz)
```

![图片](https://i.loli.net/2020/09/19/MEmNU2WJeqzGnd3.png)

```markdown
![这是图片名称](这是图片地址)
```

```c++
//代码
//这是一段c++代码
#include<iostream>
using namespace std;
int main()
{
    cout << "Hello World."<<endl;
    return 0;
}
```

```markdown

使用```来包裹一个代码块。


```

