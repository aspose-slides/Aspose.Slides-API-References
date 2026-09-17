---
title: IParagraphCollection class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/iparagraphcollection/
---
## IParagraphCollection 类

表示一组段落。

IParagraphCollection 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`count`](/slides/python-net/zh/aspose.slides/iparagraphcollection/count/) | 获取集合实际包含的元素数量。<br/>            只读 **int**. |
| [`slide`](/slides/python-net/zh/aspose.slides/iparagraphcollection/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides/iparagraphcollection/presentation/) |  |

获取指定索引处的元素。

## 索引器

| 名称 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides/iparagraphcollection/__getitem__/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`add(self, value)`](/slides/python-net/zh/aspose.slides/iparagraphcollection/add/#iparagraph) | 将 Paragraph 添加到集合的末尾。 |
| [`add(self, value)`](/slides/python-net/zh/aspose.slides/iparagraphcollection/add/#iparagraphcollection) | 将 ParagraphCollection 的内容添加到集合的末尾。 |
| [`insert(self, index, value)`](/slides/python-net/zh/aspose.slides/iparagraphcollection/insert/#int-iparagraph) | 在指定索引处将 Paragraph 插入到集合中。 |
| [`insert(self, index, value)`](/slides/python-net/zh/aspose.slides/iparagraphcollection/insert/#int-iparagraphcollection) | 在指定索引处将 ParagraphCollection 的内容插入到集合中。 |
| [`add_from_html(self, text)`](/slides/python-net/zh/aspose.slides/iparagraphcollection/add_from_html/#str) | 将指定的 html 字符串中的文本添加到集合中。 |
| [`add_from_html(self, text, resolver, uri)`](/slides/python-net/zh/aspose.slides/iparagraphcollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | 将指定的 html 字符串中的文本添加到集合中。 |
| [`clear(self)`](/slides/python-net/zh/aspose.slides/iparagraphcollection/clear/#) | 从集合中移除所有元素。 |
| [`remove_at(self, index)`](/slides/python-net/zh/aspose.slides/iparagraphcollection/remove_at/#int) | 移除集合中指定索引处的元素。 |
| [`remove(self, item)`](/slides/python-net/zh/aspose.slides/iparagraphcollection/remove/#iparagraph) | 移除特定段落的第一次出现。 |
| [`export_to_html(self, first_paragraph_index, paragraphs_count, options)`](/slides/python-net/zh/aspose.slides/iparagraphcollection/export_to_html/#int-int-asposeslidesexportitexttohtmlconversionoptions) | 将指定的段落转换为 HTML 并返回为 String 对象。 |


### 另请参阅
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)