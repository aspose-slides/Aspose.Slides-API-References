---
title: ISectionCollection class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/isectioncollection/
---
## ISectionCollection 类

表示一个章节集合。

ISectionCollection 类型公开以下成员：

获取指定索引处的元素。  
只读 [`ISection`](/slides/python-net/zh/aspose.slides/isection)。

## 索引器

| 名称 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides/isectioncollection/__getitem__/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`add_section(self, name, started_from_slide)`](/slides/python-net/zh/aspose.slides/isectioncollection/add_section/#str-islide) | 添加从特定幻灯片开始的新章节。 |
| [`add_empty_section(self, name, index)`](/slides/python-net/zh/aspose.slides/isectioncollection/add_empty_section/#str-int) | 在集合的指定位置添加空章节。 |
| [`remove_section_with_slides(self, section)`](/slides/python-net/zh/aspose.slides/isectioncollection/remove_section_with_slides/#isection) | 删除章节及其中包含的幻灯片。 |
| [`remove_section(self, section)`](/slides/python-net/zh/aspose.slides/isectioncollection/remove_section/#isection) | 删除章节。章节中包含的幻灯片将合并到前一章节。 |
| [`reorder_section_with_slides(self, section, index)`](/slides/python-net/zh/aspose.slides/isectioncollection/reorder_section_with_slides/#isection-int) | 将章节及其幻灯片从集合中移动到指定位置。 |
| [`append_empty_section(self, name)`](/slides/python-net/zh/aspose.slides/isectioncollection/append_empty_section/#str) | 在集合末尾添加空章节。 |
| [`index_of(self, section)`](/slides/python-net/zh/aspose.slides/isectioncollection/index_of/#isection) | 返回集合中指定章节的索引。 |
| [`clear(self)`](/slides/python-net/zh/aspose.slides/isectioncollection/clear/#) | 删除集合中的所有章节。 |

### 另请参见
* 类 [`ISection`](/slides/python-net/zh/aspose.slides/isection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)