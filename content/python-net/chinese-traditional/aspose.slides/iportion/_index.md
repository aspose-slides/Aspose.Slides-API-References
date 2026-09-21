---
title: IPortion class
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/iportion/
---
## IPortion 類別

Represents a portion of text inside a text paragraph.

The IPortion type exposes the following members:

## 屬性

| Property | Description |
| :- | :- |
| [`portion_format`](/slides/python-net/zh-hant/aspose.slides/iportion/portion_format/) | Returns formatting object which contains explicitly set formatting properties of the text portion with no inheritance applied.<br/>            Read-only [`IPortionFormat`](/slides/python-net/zh-hant/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/zh-hant/aspose.slides/iportion/text/) | Gets or sets the plain text of a portion.<br/>            Read/write **str**. |
| [`field`](/slides/python-net/zh-hant/aspose.slides/iportion/field/) | Returns a field of this portion.<br/>            Read-only [`IField`](/slides/python-net/zh-hant/aspose.slides/ifield). |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/iportion/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/iportion/presentation/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/zh-hant/aspose.slides/iportion/add_field/#ifieldtype) | Converts this portion to the automaticaly updated field. |
| [`add_field(self, internal_string)`](/slides/python-net/zh-hant/aspose.slides/iportion/add_field/#str) | Converts this portion to the automaticaly updated field. |
| [`remove_field(self)`](/slides/python-net/zh-hant/aspose.slides/iportion/remove_field/#) | Converts this field portion to the simple portion. |
| [`get_rect(self)`](/slides/python-net/zh-hant/aspose.slides/iportion/get_rect/#) | Get coordinates of rect that bounds portion. The rect includes all the lines of<br/>             text in portion, including empty ones. |
| [`get_coordinates(self)`](/slides/python-net/zh-hant/aspose.slides/iportion/get_coordinates/#) | Get coordinates of the beginning of the portion. The X coordinate of point represents the <br/>            portion beginning from the first character including left side bearing. The Y coordinate <br/>            includes top side bearing. |


### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)