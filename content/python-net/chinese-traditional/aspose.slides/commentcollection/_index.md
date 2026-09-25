---
title: CommentCollection class
second_title: Aspose.Slides 用於 Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/commentcollection/
---
## CommentCollection 類別

表示單一作者的評論集合。

CommentCollection 型別提供以下成員：

取得指定索引處的元素。  
唯讀 [`Comment`](/slides/python-net/zh-hant/aspose.slides/comment)。

## 索引器

| 名稱 | 說明 |
| :- | :- |
| [`[index]`](/slides/python-net/zh-hant/aspose.slides/commentcollection/__getitem__/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`to_array(self)`](/slides/python-net/zh-hant/aspose.slides/commentcollection/to_array/#) | 建立並傳回包含所有評論的陣列。 |
| [`to_array(self, start_index, count)`](/slides/python-net/zh-hant/aspose.slides/commentcollection/to_array/#int-int) | 建立並傳回指定範圍內所有評論的陣列。 |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/zh-hant/aspose.slides/commentcollection/add_comment/#str-islide-asposeslidespointf-datetime) | 在集合的末端新增評論。 |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/zh-hant/aspose.slides/commentcollection/add_modern_comment/#str-islide-ishape-asposeslidespointf-datetime) | 在集合的末端新增現代評論。 |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/zh-hant/aspose.slides/commentcollection/insert_comment/#int-str-islide-asposeslidespointf-datetime) | 在集合的指定索引處插入新評論。 |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/zh-hant/aspose.slides/commentcollection/insert_modern_comment/#int-str-islide-ishape-asposeslidespointf-datetime) | 在集合的指定索引處插入新現代評論。 |
| [`remove_at(self, index)`](/slides/python-net/zh-hant/aspose.slides/commentcollection/remove_at/#int) | 移除集合中指定索引處的元素。 |
| [`remove(self, comment)`](/slides/python-net/zh-hant/aspose.slides/commentcollection/remove/#icomment) | 移除集合中指定評論的首次出現。 |
| [`clear(self)`](/slides/python-net/zh-hant/aspose.slides/commentcollection/clear/#) | 從集合中移除所有評論。 |
| [`find_comment_by_idx(self, idx)`](/slides/python-net/zh-hant/aspose.slides/commentcollection/find_comment_by_idx/#int) | 依索引在集合中尋找評論。 |


### 另見
* 類別 [`Comment`](/slides/python-net/zh-hant/aspose.slides/comment)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)