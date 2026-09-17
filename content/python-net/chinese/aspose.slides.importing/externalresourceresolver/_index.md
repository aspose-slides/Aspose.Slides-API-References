---
title: ExternalResourceResolver class
second_title: Aspose.Slides（适用于 Python）的 .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.importing/externalresourceresolver/
---
## ExternalResourceResolver 类

用于在 Html、Svg 文档导入期间解析外部资源的回调类。 使用此解析器可能会在客户端提供的 HTML 或 SVG 文件使服务器软件获取本地或网络文件时产生漏洞。 请谨慎使用。 建议根本不要指定 ExternalResourceResolver（仅读取嵌入的对象），或创建某个子类来检查指定的 uri 是否有效。

ExternalResourceResolver 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides.importing/externalresourceresolver/__init__/#) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/zh/aspose.slides.importing/externalresourceresolver/resolve_uri/#str-str) | 从基 URI 和相对 URI 解析出绝对 URI。 |
| [`get_entity(self, absolute_uri)`](/slides/python-net/zh/aspose.slides.importing/externalresourceresolver/get_entity/#str) | 将 URI 映射到包含实际资源的对象。 |


### 另请参阅
* 模块 [`aspose.slides.importing`](/slides/python-net/zh/aspose.slides.importing)
* 库 [`Aspose.Slides`](/slides/python-net)