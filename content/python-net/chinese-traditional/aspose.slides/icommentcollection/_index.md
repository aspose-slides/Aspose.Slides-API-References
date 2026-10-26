---
title: ICommentCollection class
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/icommentcollection/
---
## ICommentCollection 類別

表示單一作者的評論集合。

ICommentCollection 類型公開以下成員：

取得指定索引處的元素。  
唯讀 [`IComment`](/slides/python-net/zh-hant/aspose.slides/icomment)。

## 索引子

| 名稱 | 說明 |
| :- | :- |
| [`[index]`](/slides/python-net/zh-hant/aspose.slides/icommentcollection/__getitem__/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`to_array(self)`](/slides/python-net/zh-hant/aspose.slides/icommentcollection/to_array/#) | 建立並傳回包含所有評論的陣列。 |
| [`to_array(self, start_index, count)`](/slides/python-net/zh-hant/aspose.slides/icommentcollection/to_array/#int-int) | 建立並傳回指定範圍內的所有評論的陣列。 |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/zh-hant/aspose.slides/icommentcollection/add_comment/#str-islide-asposeslidespointf-datetime) | 在集合的末端新增評論。 |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/zh-hant/aspose.slides/icommentcollection/add_modern_comment/#str-islide-ishape-asposeslidespointf-datetime) | 在集合的末端新增現代評論。 |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/zh-hant/aspose.slides/icommentcollection/insert_comment/#int-str-islide-asposeslidespointf-datetime) | 在指定索引處將新評論插入集合。 |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/zh-hant/aspose.slides/icommentcollection/insert_modern_comment/#int-str-islide-ishape-asposeslidespointf-datetime) | 在指定索引處將新現代評論插入集合。 |
| [`remove_at(self, index)`](/slides/python-net/zh-hant/aspose.slides/icommentcollection/remove_at/#int) | 移除集合中指定索引的元素。 |
| [`remove(self, comment)`](/slides/python-net/zh-hant/aspose.slides/icommentcollection/remove/#icomment) | 移除集合中指定評論的第一次出現。 |
| [`clear(self)`](/slides/python-net/zh-hant/aspose.slides/icommentcollection/clear/#) | 移除集合中所有評論。 |

### 另請參閱
* 類別 [`IComment`](/slides/python-net/zh-hant/aspose.slides/icomment)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)