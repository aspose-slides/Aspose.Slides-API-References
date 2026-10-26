---
title: ParagraphFormat class
second_title: Aspose.Slides 用於 Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/paragraphformat/
---
## ParagraphFormat 類別

此類別包含段落格式屬性。與 [`IParagraphFormatEffectiveData`](/slides/python-net/zh-hant/aspose.slides/iparagraphformateffectivedata) 不同，此類別的所有屬性皆可寫入。

繼承:[`ParagraphFormat`](/slides/python-net/zh-hant/aspose.slides/paragraphformat) → [`PVIObject`](/slides/python-net/zh-hant/aspose.slides/pviobject)

ParagraphFormat 類型公開以下成員：

## 建構函式

| 建構函式 | 說明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides/paragraphformat/__init__/#) | 初始化 [`ParagraphFormat`](/slides/python-net/zh-hant/aspose.slides/paragraphformat) 類別的新執行個體。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`alignment`](/slides/python-net/zh-hant/aspose.slides/paragraphformat/alignment/) | 傳回或設定段落中文本對齊方式（不套用繼承）。<br/>            可讀寫 [`TextAlignment`](/slides/python-net/zh-hant/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/zh-hant/aspose.slides/paragraphformat/space_within/) | 傳回或設定段落中基線之間的間距。正值表示百分比，負值表示點數大小。不套用繼承。<br/>            可讀寫 **float**. |
| [`space_before`](/slides/python-net/zh-hant/aspose.slides/paragraphformat/space_before/) | 傳回或設定段落中第一行之前的間距（不套用繼承）。<br/>            正值指定白色空間應為字型大小的百分比。<br/>            負值指定白色空間的點數大小。<br/>            可讀寫 **float**. |
| [`space_after`](/slides/python-net/zh-hant/aspose.slides/paragraphformat/space_after/) | 傳回或設定段落中最後一行之後的間距（不套用繼承）。<br/>            正值指定白色空間應為字型大小的百分比。<br/>            負值指定白色空間的點數大小。<br/>            可讀寫 **float**. |
| [`east_asian_line_break`](/slides/python-net/zh-hant/aspose.slides/paragraphformat/east_asian_line_break/) | 判斷段落是否使用東亞換行規則。不套用繼承。<br/>            可讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/zh-hant/aspose.slides/paragraphformat/right_to_left/) | 判斷段落是否使用右至左書寫。不套用繼承。<br/>            可讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/zh-hant/aspose.slides/paragraphformat/latin_line_break/) | 判斷段落是否使用拉丁換行規則。不套用繼承。<br/>            可讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/zh-hant/aspose.slides/paragraphformat/hanging_punctuation/) | 判斷段落是否使用懸掛標點。不套用繼承。<br/>            可讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/zh-hant/aspose.slides/paragraphformat/margin_left/) | 傳回或設定段落的左側邊距（不套用繼承）。<br/>            可讀寫 **float**. |
| [`margin_right`](/slides/python-net/zh-hant/aspose.slides/paragraphformat/margin_right/) | 傳回或設定段落的右側邊距（不套用繼承）。<br/>            可讀寫 **float**. |
| [`indent`](/slides/python-net/zh-hant/aspose.slides/paragraphformat/indent/) | 傳回或設定段落的首行縮排/懸掛縮排（不套用繼承）。懸掛縮排可使用負值定義。<br/>            可讀寫 **float**. |
| [`default_tab_size`](/slides/python-net/zh-hant/aspose.slides/paragraphformat/default_tab_size/) | 傳回或設定預設製表位大小（不套用繼承）。<br/>            可讀寫 **float**. |
| [`tabs`](/slides/python-net/zh-hant/aspose.slides/paragraphformat/tabs/) | 傳回段落的製表位。未套用繼承。<br/>            唯讀 [`ITabCollection`](/slides/python-net/zh-hant/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/zh-hant/aspose.slides/paragraphformat/font_alignment/) | 傳回或設定段落中的字型對齊方式（不套用繼承）。<br/>            可讀寫 [`FontAlignment`](/slides/python-net/zh-hant/aspose.slides/fontalignment). |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/paragraphformat/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/paragraphformat/presentation/) |  |
| [`bullet`](/slides/python-net/zh-hant/aspose.slides/paragraphformat/bullet/) |  |
| [`depth`](/slides/python-net/zh-hant/aspose.slides/paragraphformat/depth/) |  |
| [`default_portion_format`](/slides/python-net/zh-hant/aspose.slides/paragraphformat/default_portion_format/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/zh-hant/aspose.slides/paragraphformat/get_effective/#) | 取得套用繼承後的有效段落格式資料。 |

### 備註

此類別用於傳回與操作特定段落所定義的段落格式屬性。這表示在取得值時不套用繼承，因此在大多數情況下，您會得到「未定義」的值。

若要取得包括繼承在內的有效格式參數值，必須使用 [`ParagraphFormat.get_effective`](/slides/python-net/zh-hant/aspose.slides/paragraphformat/get_effective) 方法，它會傳回一個 [`IParagraphFormatEffectiveData`](/slides/python-net/zh-hant/aspose.slides/iparagraphformateffectivedata) 執行個體。

### 另請參閱
* 類別 [`IParagraphFormatEffectiveData`](/slides/python-net/zh-hant/aspose.slides/iparagraphformateffectivedata)
* 類別 [`ParagraphFormat`](/slides/python-net/zh-hant/aspose.slides/paragraphformat)
* 類別 [`PVIObject`](/slides/python-net/zh-hant/aspose.slides/pviobject)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)