---
title: CommentCollection class
second_title: Aspose.Slides 用於 Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/commentcollection/
---
## CommentCollection 類別

表示單一作者的註解集合。

CommentCollection 類型公開以下成員：

取得指定索引處的元素。  
            唯讀 [`Comment`](/slides/python-net/zh-hant/aspose.slides/comment)。

## 索引子

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/zh-hant/aspose.slides/commentcollection/__getitem__/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`to_array(self)`](/slides/python-net/zh-hant/aspose.slides/commentcollection/to_array/#) | 建立並回傳包含所有註解的陣列。 |
| [`to_array(self, start_index, count)`](/slides/python-net/zh-hant/aspose.slides/commentcollection/to_array/#int-int) | 建立並回傳指定範圍內所有註解的陣列。 |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/zh-hant/aspose.slides/commentcollection/add_comment/#str-islide-asposepydrawingpointf-datetime) | 在集合末端新增註解。 |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/zh-hant/aspose.slides/commentcollection/add_modern_comment/#str-islide-ishape-asposepydrawingpointf-datetime) | 在集合末端新增現代註解。 |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/zh-hant/aspose.slides/commentcollection/insert_comment/#int-str-islide-asposepydrawingpointf-datetime) | 在指定索引處將新註解插入集合。 |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/zh-hant/aspose.slides/commentcollection/insert_modern_comment/#int-str-islide-ishape-asposepydrawingpointf-datetime) | 在指定索引處將新現代註解插入集合。 |
| [`remove_at(self, index)`](/slides/python-net/zh-hant/aspose.slides/commentcollection/remove_at/#int) | 移除集合中指定索引處的元素。 |
| [`remove(self, comment)`](/slides/python-net/zh-hant/aspose.slides/commentcollection/remove/#icomment) | 移除集合中第一次出現的指定註解。 |
| [`clear(self)`](/slides/python-net/zh-hant/aspose.slides/commentcollection/clear/#) | 移除集合中所有註解。 |
| [`find_comment_by_idx(self, idx)`](/slides/python-net/zh-hant/aspose.slides/commentcollection/find_comment_by_idx/#int) | 依索引在集合中尋找註解。 |

### 另請參閱
* 類別 [`Comment`](/slides/python-net/zh-hant/aspose.slides/comment)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)