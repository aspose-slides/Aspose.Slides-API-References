---
title: ChartPortionFormat
second_title: Aspose.Sildes for .NET API 參考文件
description: 此類別包含圖表中使用的圖表區段格式屬性。與 IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata 不同，該類別的所有屬性皆可寫入。
type: docs
weight: 1430
url: /zh-hant/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat 類別

此類別包含圖表中使用的圖表區段格式屬性。與 [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) 不同，該類別的所有屬性皆可寫入。

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | 取得或設定替代語言的 Id。可讀寫 String。 |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | 允許取得基礎 IPresentationComponent 介面。唯讀 [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent)。 |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | 取得或設定複合文字腳本字型資訊。Null 代表字型未定義，應從母片繼承。可讀寫 [`IFontData`](../../aspose.slides/ifontdata)。 |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | 取得或設定東亞字型資訊。Null 代表字型未定義，應從母片繼承。可讀寫 [`IFontData`](../../aspose.slides/ifontdata)。 |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | 取得文字 EffectFormat 屬性。未套用繼承。唯讀 [`IEffectFormat`](../../aspose.slides/ieffectformat)。 |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | 取得或設定上標或下標文字。值範圍為 -100%（下標）至 100%（上標）。**float.NaN** 代表值未定義，應從母片繼承。可讀寫 Single。 |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | 取得文字 FillFormat 屬性。未套用繼承。唯讀 [`IFillFormat`](../../aspose.slides/ifillformat)。 |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | 決定字型是否為粗體。未套用繼承。可讀寫 [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | 取得或設定區段的字型高度。**float.NaN** 代表高度未定義，應從母片繼承。可讀寫 Single。 |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | 決定字型是否為斜體。未套用繼承。可讀寫 [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | 取得或設定文字底線類型。未套用繼承。可讀寫 [`TextUnderlineType`](../../aspose.slides/textunderlinetype)。 |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | 取得用於突顯文字的顏色。未套用繼承。唯讀 [`IColorFormat`](../../aspose.slides/icolorformat)。 |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | 決定底線樣式是否具有自訂的 FillFormat 屬性，或是繼承自文字的 FillFormat 屬性。可讀寫 [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | 決定底線樣式是否具有自訂的 LineFormat 屬性，或是繼承自文字的 LineFormat 屬性。可讀寫 [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | 取得或設定字型的最小尺寸，當字距微調應啟用時。**float.NaN** 代表值未定義，應從母片繼承。可讀寫 Single。 |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | 決定數字是否應忽略文字東方語言特定的垂直文字版面配置。未套用繼承。可讀寫 [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | 取得或設定校對語言的 Id。用於拼寫與文法檢查。可讀寫 String。 |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | 取得或設定拉丁字型資訊。Null 代表字型未定義，應從母片繼承。可讀寫 [`IFontData`](../../aspose.slides/ifontdata)。 |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | 取得文字描邊的 LineFormat 屬性。未套用繼承。唯讀 [`ILineFormat`](../../aspose.slides/ilineformat)。 |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | 決定文字的高度是否應正規化。未套用繼承。可讀寫 [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | 決定文字是否不進行校對。未套用繼承。可讀寫 [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | 取得或設定字元間距的增量。**float.NaN** 代表值未定義，應從母片繼承。可讀寫 Single。 |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | 取得或設定指示是否為文字區段啟用拼寫檢查的值。當此屬性設為 false 時，文字元素的拼寫檢查會被抑制。設為 true 時，允許拼寫檢查。預設值為 `false`。 |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | 取得或設定文字的刪除線類型。未套用繼承。可讀寫 [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype)。 |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | 取得或設定符號字型資訊。Null 代表字型未定義，應從母片繼承。可讀寫 [`IFontData`](../../aspose.slides/ifontdata)。 |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | 取得或設定文字大寫類型。未套用繼承。可讀寫 [`TextCapType`](../../aspose.slides/textcaptype)。 |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | 取得底線線條的 FillFormat 屬性。未套用繼承。唯讀 [`IFillFormat`](../../aspose.slides/ifillformat)。 |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | 取得用於描繪底線線條的 LineFormat 屬性。未套用繼承。唯讀 [`ILineFormat`](../../aspose.slides/ilineformat)。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | 與指定的物件比較。 |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | 取得雜湊碼。 |

### 備註

此類別用於回傳與操作針對特定區段所定義的文字區段格式屬性。這表示在取得值時不會套用繼承，因此在大多數情況下會取得表示「未定義」的值。

若要取得包括繼承在內的有效格式參數值，必須使用 [`GetEffective`](../../aspose.slides/portionformat/geteffective) 方法，該方法會回傳一個 [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) 實例。

### 另請參閱

* 類別 [BasePortionFormat](../../aspose.slides/baseportionformat)
* 介面 [IChartPortionFormat](../ichartportionformat)
* 命名空間 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->