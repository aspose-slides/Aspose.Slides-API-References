---
title: IParagraphCollection class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/iparagraphcollection/
---
## IParagraphCollection 類別

表示段落的集合。

IParagraphCollection 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`count`](/slides/python-net/zh-hant/aspose.slides/iparagraphcollection/count/) | 取得集合實際包含的元素數量。<br/>            唯讀 **int**。 |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/iparagraphcollection/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/iparagraphcollection/presentation/) |  |

取得指定索引處的元素。

## 索引器

| 名稱 | 說明 |
| :- | :- |
| [`[index]`](/slides/python-net/zh-hant/aspose.slides/iparagraphcollection/__getitem__/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`add(self, value)`](/slides/python-net/zh-hant/aspose.slides/iparagraphcollection/add/#iparagraph) | 將 Paragraph 新增至集合的末端。 |
| [`add(self, value)`](/slides/python-net/zh-hant/aspose.slides/iparagraphcollection/add/#iparagraphcollection) | 將 ParagraphCollection 的內容新增至集合的末端。 |
| [`insert(self, index, value)`](/slides/python-net/zh-hant/aspose.slides/iparagraphcollection/insert/#int-iparagraph) | 在指定索引處將 Paragraph 插入集合。 |
| [`insert(self, index, value)`](/slides/python-net/zh-hant/aspose.slides/iparagraphcollection/insert/#int-iparagraphcollection) | 在指定索引處將 ParagraphCollection 的內容插入集合。 |
| [`add_from_html(self, text)`](/slides/python-net/zh-hant/aspose.slides/iparagraphcollection/add_from_html/#str) | 將指定 html 字串的文字新增至集合。 |
| [`add_from_html(self, text, resolver, uri)`](/slides/python-net/zh-hant/aspose.slides/iparagraphcollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | 將指定 html 字串的文字新增至集合。 |
| [`clear(self)`](/slides/python-net/zh-hant/aspose.slides/iparagraphcollection/clear/#) | 從集合中移除所有元素。 |
| [`remove_at(self, index)`](/slides/python-net/zh-hant/aspose.slides/iparagraphcollection/remove_at/#int) | 移除集合中指定索引處的元素。 |
| [`remove(self, item)`](/slides/python-net/zh-hant/aspose.slides/iparagraphcollection/remove/#iparagraph) | 移除特定段落的第一次出現。 |
| [`export_to_html(self, first_paragraph_index, paragraphs_count, options)`](/slides/python-net/zh-hant/aspose.slides/iparagraphcollection/export_to_html/#int-int-asposeslidesexportitexttohtmlconversionoptions) | 將指定的段落轉換為 HTML 並以 String 物件返回。 |


### 參見
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)