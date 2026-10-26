---
title: MathPortion class
second_title: Aspose.Slides 用於 Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/mathportion/
---
## MathPortion 類別

表示具有數學上下文的內容部分。

**繼承關係：**[`MathPortion`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathportion) → [`Portion`](/slides/python-net/zh-hant/aspose.slides/portion)

MathPortion 類型公開以下成員：

## 建構函式

| 建構式 | 說明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathportion/__init__/#) | 初始化 MathPortion 類別的新執行個體。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`portion_format`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathportion/portion_format/) | 返回格式化對象，該對象包含未套用繼承的文字部分明確設定的格式屬性。<br/>            唯讀 [`IPortionFormat`](/slides/python-net/zh-hant/aspose.slides/iportionformat)。 |
| [`text`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathportion/text/) | 取得或設定部分的純文字。<br/>            可讀寫 **str**。 |
| [`field`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathportion/field/) | 返回此部分的欄位。<br/>            唯讀 [`IField`](/slides/python-net/zh-hant/aspose.slides/ifield)。 |
| [`math_paragraph`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathportion/math_paragraph/) | 數學段落 |
| [`slide`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathportion/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathportion/presentation/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathportion/add_field/#ifieldtype) | 將此部分轉換為自動更新的欄位。 |
| [`add_field(self, internal_string)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathportion/add_field/#str) | 將此部分轉換為自動更新的欄位。 |
| [`remove_field(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathportion/remove_field/#) | 將此欄位部分轉換為簡單部分。 |
| [`get_rect(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathportion/get_rect/#) | 取得界定部分的矩形座標。該矩形包含部分中所有文字行，<br/>            包含空白行。 |
| [`get_coordinates(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathportion/get_coordinates/#) | 取得部分起始點的座標。點的 X 座標代表從包括左側留白的第一個字元開始的部分起始位置。<br/>            Y 座標包括上側留白。 |

### 另見
* 類別 [`MathPortion`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathportion)
* 類別 [`Portion`](/slides/python-net/zh-hant/aspose.slides/portion)
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 函式庫 [`Aspose.Slides`](/slides/python-net)