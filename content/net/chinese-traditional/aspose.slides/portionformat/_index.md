---
title: PortionFormat
second_title: Aspose.Sildes for .NET API 參考
description: 此類別包含文字片段格式設定屬性。與 IPortionFormatEffectiveData./iportionformateffectivedata 不同，此類別的所有屬性皆可寫入。
type: docs
weight: 9510
url: /zh-hant/aspose.slides/portionformat/
---
## PortionFormat 類別

此類別包含文字區段的格式設定屬性。與 [`IPortionFormatEffectiveData`](../iportionformateffectivedata) 不同，此類別的所有屬性皆可寫入。

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## 建構函式

| 名稱 | 說明 |
| --- | --- |
| [PortionFormat](portionformat)() | 初始化 [`PortionFormat`](../portionformat) 類別的新執行個體。 |

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | 返回或設定替代語言的 Id。可讀寫 String。 |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | 允許取得基礎 IPresentationComponent 介面。唯讀 [`IPresentationComponent`](../ipresentationcomponent)。 |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | 返回或設定書籤識別碼。可讀寫 String。 |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | 返回或設定複雜腳本字型資訊。Null 表示字型未定義，應從母片繼承。可讀寫 [`IFontData`](../ifontdata)。 |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | 返回或設定東亞字型資訊。Null 表示字型未定義，應從母片繼承。可讀寫 [`IFontData`](../ifontdata)。 |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | 返回文字 EffectFormat 屬性。未套用繼承。唯讀 [`IEffectFormat`](../ieffectformat)。 |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | 返回或設定上標或下標文字。值介於 -100%（下標）至 100%（上標）。**float.NaN** 表示值未定義，應從母片繼承。可讀寫 Single。 |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | 返回文字 FillFormat 屬性。未套用繼承。唯讀 [`IFillFormat`](../ifillformat)。 |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | 決定字型是否為粗體。未套用繼承。可讀寫 [`NullableBool`](../nullablebool)。 |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | 返回或設定區段的字型高度。**float.NaN** 表示高度未定義，應從母片繼承。可讀寫 Single。 |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | 決定字型是否為斜體。未套用繼承。可讀寫 [`NullableBool`](../nullablebool)。 |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | 返回或設定文字底線類型。未套用繼承。可讀寫 [`TextUnderlineType`](../textunderlinetype)。 |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | 返回用於突顯文字的顏色。未套用繼承。唯讀 [`IColorFormat`](../icolorformat)。 |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | 返回或設定滑鼠點擊時的超連結。可讀寫 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | 超連結管理員。唯讀 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | 返回或設定滑鼠懸停時的超連結。可讀寫 [`IHyperlink`](../ihyperlink)。 |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | 決定底線樣式是否擁有自己的 FillFormat 屬性，或從文字的 FillFormat 屬性繼承。可讀寫 [`NullableBool`](../nullablebool)。 |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | 決定底線樣式是否擁有自己的 LineFormat 屬性，或從文字的 LineFormat 屬性繼承。可讀寫 [`NullableBool`](../nullablebool)。 |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | 返回或設定啟用字距調整的最小字型大小。**float.NaN** 表示值未定義，應從母片繼承。可讀寫 Single。 |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | 決定數字是否應忽略文字東方語言特定的垂直排版。未套用繼承。可讀寫 [`NullableBool`](../nullablebool)。 |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | 返回或設定校對語言的 Id。用於拼寫與文法檢查。可讀寫 String。 |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | 返回或設定拉丁字型資訊。Null 表示字型未定義，應從母片繼承。可讀寫 [`IFontData`](../ifontdata)。 |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | 返回文字描邊的 LineFormat 屬性。未套用繼承。唯讀 [`ILineFormat`](../ilineformat)。 |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | 決定文字高度是否應正規化。未套用繼承。可讀寫 [`NullableBool`](../nullablebool)。 |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | 決定文字是否不進行校對。未套用繼承。可讀寫 [`NullableBool`](../nullablebool)。 |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | 決定智慧標記是否應被清除。未套用繼承。可讀寫 Boolean。 |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | 返回或設定字元間距增量。**float.NaN** 表示值未定義，應從母片繼承。可讀寫 Single。 |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | 取得或設定指示是否為文字區段啟用拼寫檢查的值。當此屬性設為 false 時，會抑制文字元素的拼寫檢查。設為 true 時，允許拼寫檢查。預設值為 `false`。 |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | 返回或設定文字的刪除線類型。未套用繼承。可讀寫 [`TextStrikethroughType`](../textstrikethroughtype)。 |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | 返回或設定符號字型資訊。Null 表示字型未定義，應從母片繼承。可讀寫 [`IFontData`](../ifontdata)。 |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | 返回或設定文字大小寫類型。未套用繼承。可讀寫 [`TextCapType`](../textcaptype)。 |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | 返回底線線條的 FillFormat 屬性。未套用繼承。唯讀 [`IFillFormat`](../ifillformat)。 |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | 返回用於描繪底線線條的 LineFormat 屬性。未套用繼承。唯讀 [`ILineFormat`](../ilineformat)。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | 與指定物件比較。 |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | 取得套用繼承後的實際區段格式資料。 |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | 返回雜湊碼。 |

### 備註

此類別用於返回和操作針對特定區段定義的文字區段格式屬性。這表示在取得值時不會套用繼承，因而在大多數情況下會取得表示「未定義」的值。

若要取得包含繼承的實際格式參數值，必須使用 [`GetEffective`](./geteffective) 方法，該方法返回一個 [`IPortionFormatEffectiveData`](../iportionformateffectivedata) 實例。

### 範例

以下範例示範如何將拉丁字型指派給 PowerPoint 簡報中 Paragraph 的區段。

```csharp
[C#]
//實例化一個表示簡報檔案的簡報物件
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides 使用這些特殊識別碼（類似於 PowerPoint 中使用的）：
// +mn-lt - 正文字型 Latin（次要 Latin 字型）
// +mj-lt - 標題字型 Latin（主要 Latin 字型）
// +mn-ea - 正文字型 East Asian（次要 East Asian 字型）
// +mj-ea - 正文字型 East Asian（次要 East Asian 字型）
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### 另請參閱

* 類別 [BasePortionFormat](../baseportionformat)
* 介面 [IPortionFormat](../iportionformat)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->