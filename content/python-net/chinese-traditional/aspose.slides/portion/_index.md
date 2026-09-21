---
title: Portion class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/portion/
---
## Portion 類別

表示文字段落中一段文字的部分。

Portion 類型公開以下成員：

## 建構子

| 建構子 | 說明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides/portion/__init__/#) | 初始化 Portion 類別的新執行個體。 |
| [`__init__(self, str)`](/slides/python-net/zh-hant/aspose.slides/portion/__init__/#str) | 初始化 Portion 類別的新執行個體。 |
| [`__init__(self, portion)`](/slides/python-net/zh-hant/aspose.slides/portion/__init__/#portion) | 初始化 Portion 類別的新執行個體。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`portion_format`](/slides/python-net/zh-hant/aspose.slides/portion/portion_format/) | 返回一個格式化物件，此物件包含已明確設定的文字部分格式屬性，且不套用繼承。<br/>            只讀 [`IPortionFormat`](/slides/python-net/zh-hant/aspose.slides/iportionformat)。 |
| [`text`](/slides/python-net/zh-hant/aspose.slides/portion/text/) | 取得或設定部分的純文字。<br/>            可讀寫 **str**。 |
| [`field`](/slides/python-net/zh-hant/aspose.slides/portion/field/) | 返回此部分的欄位。<br/>            只讀 [`IField`](/slides/python-net/zh-hant/aspose.slides/ifield)。 |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/portion/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/portion/presentation/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/zh-hant/aspose.slides/portion/add_field/#ifieldtype) | 將此部分轉換為自動更新的欄位。 |
| [`add_field(self, internal_string)`](/slides/python-net/zh-hant/aspose.slides/portion/add_field/#str) | 將此部分轉換為自動更新的欄位。 |
| [`remove_field(self)`](/slides/python-net/zh-hant/aspose.slides/portion/remove_field/#) | 將此欄位部分轉換為一般部分。 |
| [`get_rect(self)`](/slides/python-net/zh-hant/aspose.slides/portion/get_rect/#) | 取得界定部分的矩形座標。該矩形包含部分中所有文字行，包括空白行。 |
| [`get_coordinates(self)`](/slides/python-net/zh-hant/aspose.slides/portion/get_coordinates/#) | 取得部分起始點的座標。點的 X 座標表示從第一個字元起、包括左側留白的部分起始位置。Y 座標包括上側留白。 |


### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)