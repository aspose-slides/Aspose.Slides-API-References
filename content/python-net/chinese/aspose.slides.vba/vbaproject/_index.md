---
title: VbaProject class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.vba/vbaproject/
---
## VbaProject 类

表示具有演示宏的 VBA 项目。

VbaProject 类型公开以下成员：

## 构造函数

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides.vba/vbaproject/__init__/#) | 此构造函数从头创建新的 VBA 项目。<br/>            项目将在 1252 Windows Latin 1 (ANSI) 代码页中创建 |
| [`__init__(self, data)`](/slides/python-net/zh/aspose.slides.vba/vbaproject/__init__/#bytes) | 此构造函数从 OLE 容器的二进制表示加载 VBA 项目。 |

## 属性

| Property | Description |
| :- | :- |
| [`name`](/slides/python-net/zh/aspose.slides.vba/vbaproject/name/) | 返回 VBA 项目的名称。<br/>            只读 **str**。 |
| [`modules`](/slides/python-net/zh/aspose.slides.vba/vbaproject/modules/) | 返回 VBA 项目中包含的所有模块的列表。<br/>            只读 [`IVbaModuleCollection`](/slides/python-net/zh/aspose.slides.vba/ivbamodulecollection)。 |
| [`references`](/slides/python-net/zh/aspose.slides.vba/vbaproject/references/) | 返回 VBA 项目中包含的所有引用的列表。<br/>            只读 [`IVbaReferenceCollection`](/slides/python-net/zh/aspose.slides.vba/ivbareferencecollection)。 |
| [`is_password_protected`](/slides/python-net/zh/aspose.slides.vba/vbaproject/is_password_protected/) | 指示 VBAProject 是否受密码保护以查看项目属性。<br/>            只读 **bool**。 |

## 方法

| Method | Description |
| :- | :- |
| [`to_binary(self)`](/slides/python-net/zh/aspose.slides.vba/vbaproject/to_binary/#) | 返回 VBA 项目的二进制表示（OLE 容器） |

### 参见
* 模块 [`aspose.slides.vba`](/slides/python-net/zh/aspose.slides.vba)
* 库 [`Aspose.Slides`](/slides/python-net)