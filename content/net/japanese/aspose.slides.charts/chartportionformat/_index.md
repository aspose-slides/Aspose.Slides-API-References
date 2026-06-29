---
title: ChartPortionFormat
second_title: Aspose.Sildes for .NET API リファレンス
description: このクラスは、チャートで使用されるチャート部分の書式設定プロパティを含みます。IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata と異なり、このクラスのすべてのプロパティは書き込み可能です。
type: docs
weight: 1410
url: /ja/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat クラス

このクラスは、チャートで使用されるチャート部分の書式設定プロパティを含みます。[`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata)とは異なり、このクラスのすべてのプロパティは書き込み可能です。

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | 代替言語の Id を取得または設定します。 読み書き可能な String。 |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | 基本 IPresentationComponent インターフェイスを取得できます。 読み取り専用 [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent)。 |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | 複雑スクリプト フォント情報を取得または設定します。 Null はフォントが未定義であり、マスターから継承されることを意味します。 読み書き可能な [`IFontData`](../../aspose.slides/ifontdata)。 |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | 東アジア フォント情報を取得または設定します。 Null はフォントが未定義であり、マスターから継承されることを意味します。 読み書き可能な [`IFontData`](../../aspose.slides/ifontdata)。 |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | テキストの EffectFormat プロパティを取得します。 継承は適用されません。 読み取り専用 [`IEffectFormat`](../../aspose.slides/ieffectformat)。 |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | 上付きまたは下付きテキストを取得または設定します。 値は -100%（下付き）から 100%（上付き）までです。 **float.NaN** は値が未定義であり、マスターから継承されることを意味します。 読み書き可能な Single。 |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | テキストの FillFormat プロパティを取得します。 継承は適用されません。 読み取り専用 [`IFillFormat`](../../aspose.slides/ifillformat)。 |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | フォントが太字かどうかを決定します。 継承は適用されません。 読み書き可能な [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | 部分のフォント高さを取得または設定します。 **float.NaN** は高さが未定義であり、マスターから継承されることを意味します。 読み書き可能な Single。 |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | フォントが斜体かどうかを決定します。 継承は適用されません。 読み書き可能な [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | テキストの下線タイプを取得または設定します。 継承は適用されません。 読み書き可能な [`TextUnderlineType`](../../aspose.slides/textunderlinetype)。 |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | テキストのハイライトに使用される色を取得します。 継承は適用されません。 読み取り専用 [`IColorFormat`](../../aspose.slides/icolorformat)。 |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | 下線スタイルが独自の FillFormat プロパティを持つか、テキストの FillFormat プロパティから継承するかを決定します。 読み書き可能な [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | 下線スタイルが独自の LineFormat プロパティを持つか、テキストの LineFormat プロパティから継承するかを決定します。 読み書き可能な [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | カーニングを有効にすべき最小フォントサイズを取得または設定します。 **float.NaN** は値が未定義であり、マスターから継承されることを意味します。 読み書き可能な Single。 |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | 数字がテキストの東アジア言語固有の縦書きレイアウトを無視すべきかどうかを決定します。 継承は適用されません。 読み書き可能な [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | 校正言語の Id を取得または設定します。 スペルチェックと文法チェックに使用されます。 読み書き可能な String。 |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | ラテン文字フォント情報を取得または設定します。 Null はフォントが未定義であり、マスターから継承されることを意味します。 読み書き可能な [`IFontData`](../../aspose.slides/ifontdata)。 |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | テキストの輪郭描画用 LineFormat プロパティを取得します。 継承は適用されません。 読み取り専用 [`ILineFormat`](../../aspose.slides/ilineformat)。 |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | テキストの高さを正規化すべきかどうかを決定します。 継承は適用されません。 読み書き可能な [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | テキストが校正されないようにすべきかどうかを決定します。 継承は適用されません。 読み書き可能な [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | 文字間スペースの増分を取得または設定します。 **float.NaN** は値が未定義であり、マスターから継承されることを意味します。 読み書き可能な Single。 |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | テキスト部分に対してスペルチェックが有効かどうかを示す値を取得または設定します。このプロパティが false に設定されている場合、テキスト要素のスペルチェックは抑制されます。true に設定するとスペルチェックが許可されます。デフォルト値は `false` です。 |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | テキストの取り消し線タイプを取得または設定します。 継承は適用されません。 読み書き可能な [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype)。 |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | 記号フォント情報を取得または設定します。 Null はフォントが未定義であり、マスターから継承されることを意味します。 読み書き可能な [`IFontData`](../../aspose.slides/ifontdata)。 |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | テキストの大文字化タイプを取得または設定します。 継承は適用されません。 読み書き可能な [`TextCapType`](../../aspose.slides/textcaptype)。 |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | 下線ラインの FillFormat プロパティを取得します。 継承は適用されません。 読み取り専用 [`IFillFormat`](../../aspose.slides/ifillformat)。 |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | 下線ラインを輪郭描画するために使用される LineFormat プロパティを取得します。 継承は適用されません。 読み取り専用 [`ILineFormat`](../../aspose.slides/ilineformat)。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | 指定されたオブジェクトと比較します。 |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | ハッシュコードを返します。 |

### 備考

このクラスは、特定の部分に定義されたテキスト部分の書式設定プロパティを取得および操作するために使用されます。これは、値を取得する際に継承が適用されないことを意味し、ほとんどの場合「未定義」の値が得られます。

継承されたものを含む実際の書式設定パラメータ値を取得するには、[`GetEffective`](../../aspose.slides/portionformat/geteffective)メソッドを使用し、[`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata)インスタンスを取得します。

### 関連項目

* クラス [BasePortionFormat](../../aspose.slides/baseportionformat)
* インターフェイス [IChartPortionFormat](../ichartportionformat)
* 名前空間 [Aspose.Slides.Charts](../../aspose.slides.charts)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->