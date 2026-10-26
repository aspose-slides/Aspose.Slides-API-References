---
title: IPortion class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/iportion/
---
## IPortion 类

表示文本段落中一段文字。

IPortion 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`portion_format`](/slides/python-net/zh/aspose.slides/iportion/portion_format/) | 返回格式对象，包含此文字段落的显式设置的格式属性，未应用继承。<br/>只读 [`IPortionFormat`](/slides/python-net/zh/aspose.slides/iportionformat)。 |
| [`text`](/slides/python-net/zh/aspose.slides/iportion/text/) | 获取或设置段落的一段纯文本。<br/>读/写 **str**。 |
| [`field`](/slides/python-net/zh/aspose.slides/iportion/field/) | 返回此段的字段。<br/>只读 [`IField`](/slides/python-net/zh/aspose.slides/ifield)。 |
| [`slide`](/slides/python-net/zh/aspose.slides/iportion/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides/iportion/presentation/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/zh/aspose.slides/iportion/add_field/#ifieldtype) | 将此段转换为自动更新的字段。 |
| [`add_field(self, internal_string)`](/slides/python-net/zh/aspose.slides/iportion/add_field/#str) | 将此段转换为自动更新的字段。 |
| [`remove_field(self)`](/slides/python-net/zh/aspose.slides/iportion/remove_field/#) | 将此字段段转换为普通段落。 |
| [`get_rect(self)`](/slides/python-net/zh/aspose.slides/iportion/get_rect/#) | 获取界定段落的矩形坐标。矩形包括段落中所有行的文本，包括空行。 |
| [`get_coordinates(self)`](/slides/python-net/zh/aspose.slides/iportion/get_coordinates/#) | 获取段落起始位置的坐标。点的 X 坐标表示从包括左侧间距的第一个字符开始的段落起始位置。Y 坐标包括顶部间距。 |


### 另请参见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)