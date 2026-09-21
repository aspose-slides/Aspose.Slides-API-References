---
title: ISectionCollection class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/isectioncollection/
---
## ISectionCollection 類別

表示一組節。

ISectionCollection 類型公開以下成員：

取得指定索引處的元素。唯讀 [`ISection`](/slides/python-net/zh-hant/aspose.slides/isection)。

## 索引器

| 名稱 | 說明 |
| :- | :- |
| [`[index]`](/slides/python-net/zh-hant/aspose.slides/isectioncollection/__getitem__/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`add_section(self, name, started_from_slide)`](/slides/python-net/zh-hant/aspose.slides/isectioncollection/add_section/#str-islide) | 新增從特定投影片開始的新節。 |
| [`add_empty_section(self, name, index)`](/slides/python-net/zh-hant/aspose.slides/isectioncollection/add_empty_section/#str-int) | 在集合的指定位置新增空節。 |
| [`remove_section_with_slides(self, section)`](/slides/python-net/zh-hant/aspose.slides/isectioncollection/remove_section_with_slides/#isection) | 移除節及其所包含的投影片。 |
| [`remove_section(self, section)`](/slides/python-net/zh-hant/aspose.slides/isectioncollection/remove_section/#isection) | 移除節。節中包含的投影片將合併至前一節。 |
| [`reorder_section_with_slides(self, section, index)`](/slides/python-net/zh-hant/aspose.slides/isectioncollection/reorder_section_with_slides/#isection-int) | 將節及其投影片從集合移動到指定位置。 |
| [`append_empty_section(self, name)`](/slides/python-net/zh-hant/aspose.slides/isectioncollection/append_empty_section/#str) | 在集合末端新增空節。 |
| [`index_of(self, section)`](/slides/python-net/zh-hant/aspose.slides/isectioncollection/index_of/#isection) | 回傳集合中指定節的索引。 |
| [`clear(self)`](/slides/python-net/zh-hant/aspose.slides/isectioncollection/clear/#) | 移除集合中的所有節。 |

### 另請參閱
* 類別 [`ISection`](/slides/python-net/zh-hant/aspose.slides/isection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)