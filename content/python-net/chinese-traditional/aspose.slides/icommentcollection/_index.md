---
title: ICommentCollection class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/icommentcollection/
---
## ICommentCollection 類別

表示單一作者的註解集合。

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
| [`to_array(self)`](/slides/python-net/zh-hant/aspose.slides/icommentcollection/to_array/#) | 建立並傳回包含所有註解的陣列。 |
| [`to_array(self, start_index, count)`](/slides/python-net/zh-hant/aspose.slides/icommentcollection/to_array/#int-int) | 建立並傳回包含指定範圍內所有註解的陣列。 |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/zh-hant/aspose.slides/icommentcollection/add_comment/#str-islide-asposepydrawingpointf-datetime) | 在集合的末端新增註解。 |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/zh-hant/aspose.slides/icommentcollection/add_modern_comment/#str-islide-ishape-asposepydrawingpointf-datetime) | 在集合的末端新增現代註解。 |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/zh-hant/aspose.slides/icommentcollection/insert_comment/#int-str-islide-asposepydrawingpointf-datetime) | 在集合的指定索引處插入新註解。 |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/zh-hant/aspose.slides/icommentcollection/insert_modern_comment/#int-str-islide-ishape-asposepydrawingpointf-datetime) | 在集合的指定索引處插入新現代註解。 |
| [`remove_at(self, index)`](/slides/python-net/zh-hant/aspose.slides/icommentcollection/remove_at/#int) | 移除集合中指定索引處的元素。 |
| [`remove(self, comment)`](/slides/python-net/zh-hant/aspose.slides/icommentcollection/remove/#icomment) | 移除集合中第一個出現的指定註解。 |
| [`clear(self)`](/slides/python-net/zh-hant/aspose.slides/icommentcollection/clear/#) | 移除集合中的所有註解。 |

### 另見
* 類別 [`IComment`](/slides/python-net/zh-hant/aspose.slides/icomment)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)