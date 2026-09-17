---
title: Portion class
second_title: Aspose.Slides 在 .NET 环境下的 Python API 参考
description: 
type: docs
url: /zh/aspose.slides/portion/
---
## Portion 类

表示文本段落中的 Portion。

Portion 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides/portion/__init__/#) | Initializes a new instance of the Portion class. |
| [`__init__(self, str)`](/slides/python-net/zh/aspose.slides/portion/__init__/#str) | Initializes a new instance of the Portion class. |
| [`__init__(self, portion)`](/slides/python-net/zh/aspose.slides/portion/__init__/#portion) | Initializes a new instance of the Portion class. |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`portion_format`](/slides/python-net/zh/aspose.slides/portion/portion_format/) | 返回一个格式对象，其中包含文本段落的 Portion 的显式设置的格式属性，且不应用继承。<br/>            只读 [`IPortionFormat`](/slides/python-net/zh/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/zh/aspose.slides/portion/text/) | 获取或设置 Portion 的纯文本。<br/>            读/写 **str**. |
| [`field`](/slides/python-net/zh/aspose.slides/portion/field/) | 返回此 Portion 的字段。<br/>            只读 [`IField`](/slides/python-net/zh/aspose.slides/ifield). |
| [`slide`](/slides/python-net/zh/aspose.slides/portion/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides/portion/presentation/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/zh/aspose.slides/portion/add_field/#ifieldtype) | 将此 Portion 转换为自动更新的字段。 |
| [`add_field(self, internal_string)`](/slides/python-net/zh/aspose.slides/portion/add_field/#str) | 将此 Portion 转换为自动更新的字段。 |
| [`remove_field(self)`](/slides/python-net/zh/aspose.slides/portion/remove_field/#) | 将此字段 Portion 转换为普通 Portion。 |
| [`get_rect(self)`](/slides/python-net/zh/aspose.slides/portion/get_rect/#) | 获取包围 Portion 的矩形坐标。该矩形包括该 Portion 中的所有行<br/>             文本，包括空行。 |
| [`get_coordinates(self)`](/slides/python-net/zh/aspose.slides/portion/get_coordinates/#) | 获取 Portion 起始位置的坐标。点的 X 坐标表示从第一个字符（包括左侧间距）开始的 Portion 起点。Y 坐标包括上侧间距。 |

### 另见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)