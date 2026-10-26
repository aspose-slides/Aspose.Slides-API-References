---
title: SectionCollection class
second_title: Aspose.Slides for Python via .NET API 参考文档
description: 
type: docs
url: /zh/aspose.slides/sectioncollection/
---
## SectionCollection 类

表示一个章节集合。

SectionCollection 类型公开以下成员：

获取指定索引处的元素。
只读 [`ISection`](/slides/python-net/zh/aspose.slides/isection)。

## 索引器

| 名称 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides/sectioncollection/__getitem__/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`add_section(self, name, started_from_slide)`](/slides/python-net/zh/aspose.slides/sectioncollection/add_section/#str-islide) | 添加从特定幻灯片开始的幻灯片章节。 |
| [`append_empty_section(self, name)`](/slides/python-net/zh/aspose.slides/sectioncollection/append_empty_section/#str) | 向集合末尾添加空章节。 |
| [`add_empty_section(self, name, index)`](/slides/python-net/zh/aspose.slides/sectioncollection/add_empty_section/#str-int) | 向集合的指定位置添加空章节。 |
| [`index_of(self, section)`](/slides/python-net/zh/aspose.slides/sectioncollection/index_of/#isection) | 返回集合中指定章节的索引。 |
| [`remove_section_with_slides(self, section)`](/slides/python-net/zh/aspose.slides/sectioncollection/remove_section_with_slides/#isection) | 移除章节及其包含的幻灯片。 |
| [`remove_section(self, section)`](/slides/python-net/zh/aspose.slides/sectioncollection/remove_section/#isection) | 移除章节。该章节包含的幻灯片将合并到前一个章节。 |
| [`reorder_section_with_slides(self, section, index)`](/slides/python-net/zh/aspose.slides/sectioncollection/reorder_section_with_slides/#isection-int) | 将章节及其幻灯片从集合中移动到指定位置。 |
| [`clear(self)`](/slides/python-net/zh/aspose.slides/sectioncollection/clear/#) | 从集合中移除所有章节。 |

### 另见
* 类 [`ISection`](/slides/python-net/zh/aspose.slides/isection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)