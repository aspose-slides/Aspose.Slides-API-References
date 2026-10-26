---
title: HtmlExternalResolver class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.importing/htmlexternalresolver/
---
## HtmlExternalResolver 类

回调对象，由 HTML 导入例程使用，以获取诸如图像等引用的对象。使用此解析器可能会产生漏洞，当客户端提供的 HTML 文件导致服务器软件获取本地或网络文件时。请谨慎使用。建议根本不要指定 HtmlExternalResolver（只会读取嵌入的对象），或创建一个子类来检查指定的 URI 是否有效。

HtmlExternalResolver 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides.importing/htmlexternalresolver/__init__/#) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/zh/aspose.slides.importing/htmlexternalresolver/resolve_uri/#str-str) | 从基路径和相对路径解析出绝对 URI。 |
| [`get_entity(self, absolute_uri)`](/slides/python-net/zh/aspose.slides.importing/htmlexternalresolver/get_entity/#str) | 将 URI 映射到包含实际资源的对象。 |

### 另请参见
* 模块 [`aspose.slides.importing`](/slides/python-net/zh/aspose.slides.importing)
* 库 [`Aspose.Slides`](/slides/python-net)