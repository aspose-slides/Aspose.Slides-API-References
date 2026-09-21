---
title: IParagraphFormat class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/iparagraphformat/
---
## IParagraphFormat 類別

此類別包含段落格式屬性。Unlike [`IParagraphFormatEffectiveData`](/slides/python-net/zh-hant/aspose.slides/iparagraphformateffectivedata)，此類別的所有屬性皆可寫入。

The IParagraphFormat type exposes the following members:

## 屬性

| 屬性 | 描述 |
| :- | :- |
| [`bullet`](/slides/python-net/zh-hant/aspose.slides/iparagraphformat/bullet/) | 返回段落的項目符號格式。<br/>            只讀 [`IBulletFormat`](/slides/python-net/zh-hant/aspose.slides/ibulletformat)。 |
| [`depth`](/slides/python-net/zh-hant/aspose.slides/iparagraphformat/depth/) | 返回或設定段落的深度。<br/>            值 0 表示未定義值。<br/>            可讀寫 **int**。 |
| [`alignment`](/slides/python-net/zh-hant/aspose.slides/iparagraphformat/alignment/) | 返回或設定段落中未繼承的文字對齊方式。<br/>            可讀寫 [`TextAlignment`](/slides/python-net/zh-hant/aspose.slides/textalignment)。 |
| [`space_within`](/slides/python-net/zh-hant/aspose.slides/iparagraphformat/space_within/) | 返回或設定段落中基線之間的間距。正值表示百分比，負值表示點數大小。未套用繼承。<br/>            可讀寫 **float**。 |
| [`space_before`](/slides/python-net/zh-hant/aspose.slides/iparagraphformat/space_before/) | 返回或設定段落中未繼承的第一行之前的空白間距。<br/>            正值指定應為字型大小的百分比。<br/>            負值指定空白的點數大小。<br/>            可讀寫 **float**。 |
| [`space_after`](/slides/python-net/zh-hant/aspose.slides/iparagraphformat/space_after/) | 返回或設定段落中未繼承的最後一行之後的空白間距。<br/>            正值指定應為字型大小的百分比。<br/>            負值指定空白的點數大小。<br/>            可讀寫 **float**。 |
| [`east_asian_line_break`](/slides/python-net/zh-hant/aspose.slides/iparagraphformat/east_asian_line_break/) | 判斷段落是否使用東亞斷行。未套用繼承。<br/>            可讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool)。 |
| [`right_to_left`](/slides/python-net/zh-hant/aspose.slides/iparagraphformat/right_to_left/) | 判斷段落是否使用從右到左書寫。未套用繼承。<br/>            可讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool)。 |
| [`latin_line_break`](/slides/python-net/zh-hant/aspose.slides/iparagraphformat/latin_line_break/) | 判斷段落是否使用拉丁斷行。未套用繼承。<br/>            可讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool)。 |
| [`hanging_punctuation`](/slides/python-net/zh-hant/aspose.slides/iparagraphformat/hanging_punctuation/) | 判斷段落是否使用懸掛標點。未套用繼承。<br/>            可讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool)。 |
| [`margin_left`](/slides/python-net/zh-hant/aspose.slides/iparagraphformat/margin_left/) | 返回或設定段落中未繼承的左側邊界。<br/>            可讀寫 **float**。 |
| [`margin_right`](/slides/python-net/zh-hant/aspose.slides/iparagraphformat/margin_right/) | 返回或設定段落中未繼承的右側邊界。<br/>            可讀寫 **float**。 |
| [`indent`](/slides/python-net/zh-hant/aspose.slides/iparagraphformat/indent/) | 返回或設定段落中未繼承的首行縮排/懸掛縮排。負值可定義懸掛縮排。<br/>            可讀寫 **float**。 |
| [`default_tab_size`](/slides/python-net/zh-hant/aspose.slides/iparagraphformat/default_tab_size/) | 返回或設定段落中未繼承的預設定位大小。<br/>            可讀寫 **float**。 |
| [`tabs`](/slides/python-net/zh-hant/aspose.slides/iparagraphformat/tabs/) | 返回段落的定位。未套用繼承。<br/>            只讀 [`ITabCollection`](/slides/python-net/zh-hant/aspose.slides/itabcollection)。 |
| [`font_alignment`](/slides/python-net/zh-hant/aspose.slides/iparagraphformat/font_alignment/) | 返回或設定段落中未繼承的字型對齊方式。<br/>            可讀寫 [`FontAlignment`](/slides/python-net/zh-hant/aspose.slides/fontalignment)。 |
| [`default_portion_format`](/slides/python-net/zh-hant/aspose.slides/iparagraphformat/default_portion_format/) | 返回段落的預設段落格式。未套用繼承。<br/>            只讀 [`IPortionFormat`](/slides/python-net/zh-hant/aspose.slides/iportionformat)。 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/zh-hant/aspose.slides/iparagraphformat/get_effective/#) | 取得套用繼承後的有效段落格式資料。 |

### 備註

此類別用於返回和操作針對特定段落定義的段落格式屬性。這表示在取得值時未套用繼承，因此在大多數情況下您會取得「未定義」的值。

若要取得包括繼承在內的有效格式參數值，您需要使用 [`IParagraphFormat.get_effective`](/slides/python-net/zh-hant/aspose.slides/iparagraphformat/get_effective) 方法，它會回傳一個 [`IParagraphFormatEffectiveData`](/slides/python-net/zh-hant/aspose.slides/iparagraphformateffectivedata) 實例。

### 另見
* 類別 [`IParagraphFormatEffectiveData`](/slides/python-net/zh-hant/aspose.slides/iparagraphformateffectivedata)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)