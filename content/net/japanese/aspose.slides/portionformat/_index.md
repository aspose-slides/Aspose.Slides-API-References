---
title: PortionFormat
second_title: Aspose.Sildes の .NET API リファレンス
description: このクラスはテキスト部分の書式設定プロパティを含みます。IPortionFormatEffectiveData./iportionformateffectivedata とは異なり、このクラスのすべてのプロパティは書き込み可能です。
type: docs
weight: 9510
url: /ja/aspose.slides/portionformat/
---
## PortionFormat クラス

このクラスはテキスト部分の書式設定プロパティを含みます。[`IPortionFormatEffectiveData`](../iportionformateffectivedata) とは異なり、このクラスのすべてのプロパティは書き込み可能です。

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## コンストラクタ

| Name | Description |
| --- | --- |
| [PortionFormat](portionformat)() | [`PortionFormat`](../portionformat) クラスの新しいインスタンスを初期化します。 |

## プロパティ

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | 代替言語の Id を取得または設定します。読み書き可能 String。 |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | 基底 IPresentationComponent インターフェイスを取得できます。読み取り専用 [`IPresentationComponent`](../ipresentationcomponent)。 |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | ブックマーク識別子を取得または設定します。読み書き可能 String。 |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | 複合スクリプトフォント情報を取得または設定します。null の場合はフォントが未定義であり、マスターから継承されます。読み書き可能 [`IFontData`](../ifontdata)。 |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | 東アジアフォント情報を取得または設定します。null の場合はフォントが未定義であり、マスターから継承されます。読み書き可能 [`IFontData`](../ifontdata)。 |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | テキストの EffectFormat プロパティを取得します。継承は適用されません。読み取り専用 [`IEffectFormat`](../ieffectformat)。 |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | 上付きまたは下付きテキストを取得または設定します。-100%（下付き）から 100%（上付き）の範囲の値です。**float.NaN** は値が未定義であり、マスターから継承されることを意味します。読み書き可能 Single。 |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | テキストの FillFormat プロパティを取得します。継承は適用されません。読み取り専用 [`IFillFormat`](../ifillformat)。 |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | フォントが太字かどうかを決定します。継承は適用されません。読み書き可能 [`NullableBool`](../nullablebool)。 |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | 部分のフォント高さを取得または設定します。**float.NaN** は高さが未定義であり、マスターから継承されることを意味します。読み書き可能 Single。 |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | フォントが斜体かどうかを決定します。継承は適用されません。読み書き可能 [`NullableBool`](../nullablebool)。 |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | テキストの下線タイプを取得または設定します。継承は適用されません。読み書き可能 [`TextUnderlineType`](../textunderlinetype)。 |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | テキストのハイライトに使用される色を取得します。継承は適用されません。読み取り専用 [`IColorFormat`](../icolorformat)。 |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | マウスクリック用に定義されたハイパーリンクを取得または設定します。読み書き可能 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | ハイパーリンクマネージャーです。読み取り専用 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | マウスオーバー用に定義されたハイパーリンクを取得または設定します。読み書き可能 [`IHyperlink`](../ihyperlink)。 |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | 下線スタイルが独自の FillFormat プロパティを持つか、テキストの FillFormat プロパティから継承するかを決定します。読み書き可能 [`NullableBool`](../nullablebool)。 |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | 下線スタイルが独自の LineFormat プロパティを持つか、テキストの LineFormat プロパティから継承するかを決定します。読み書き可能 [`NullableBool`](../nullablebool)。 |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | カーニングを有効にすべき最小フォントサイズを取得または設定します。**float.NaN** は値が未定義であり、マスターから継承されることを意味します。読み書き可能 Single。 |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | 数字がテキストの東アジア言語固有の縦書きレイアウトを無視すべきかどうかを決定します。継承は適用されません。読み書き可能 [`NullableBool`](../nullablebool)。 |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | 校正言語の Id を取得または設定します。スペルチェックと文法チェックに使用されます。読み書き可能 String。 |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | ラテンフォント情報を取得または設定します。null の場合はフォントが未定義であり、マスターから継承されます。読み書き可能 [`IFontData`](../ifontdata)。 |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | テキストのアウトライン用 LineFormat プロパティを取得します。継承は適用されません。読み取り専用 [`ILineFormat`](../ilineformat)。 |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | テキストの高さを正規化すべきかどうかを決定します。継承は適用されません。読み書き可能 [`NullableBool`](../nullablebool)。 |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | テキストが校正されないようにすべきかどうかを決定します。継承は適用されません。読み書き可能 [`NullableBool`](../nullablebool)。 |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | スマートタグをクリアすべきかどうかを決定します。継承は適用されません。読み書き可能 Boolean。 |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | 文字間隔の増分を取得または設定します。**float.NaN** は値が未定義であり、マスターから継承されることを意味します。読み書き可能 Single。 |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | テキスト部分のスペルチェックが有効かどうかを示す値を取得または設定します。このプロパティが false に設定されている場合、テキスト要素のスペルチェックは抑制されます。true に設定するとスペルチェックが許可されます。デフォルト値は `false` です。 |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | テキストの取り消し線タイプを取得または設定します。継承は適用されません。読み書き可能 [`TextStrikethroughType`](../textstrikethroughtype)。 |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | 記号フォント情報を取得または設定します。null の場合はフォントが未定義であり、マスターから継承されます。読み書き可能 [`IFontData`](../ifontdata)。 |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | テキストの大文字小文字変換タイプを取得または設定します。継承は適用されません。読み書き可能 [`TextCapType`](../textcaptype)。 |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | 下線線の FillFormat プロパティを取得します。継承は適用されません。読み取り専用 [`IFillFormat`](../ifillformat)。 |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | 下線線をアウトラインするために使用される LineFormat プロパティを取得します。継承は適用されません。読み取り専用 [`ILineFormat`](../ilineformat)。 |

## メソッド

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | 指定されたオブジェクトと比較します。 |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | 継承が適用された有効な部分書式データを取得します。 |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | ハッシュコードを返します。 |

### 備考

このクラスは、特定の部分に対して定義されたテキスト部分書式プロパティを取得および操作するために使用されます。取得時に継承が適用されないため、ほとんどの場合は「未定義」を意味する値が返されます。

継承を含む有効な書式パラメータ値を取得するには、[`GetEffective`](./geteffective) メソッドを使用してください。このメソッドは [`IPortionFormatEffectiveData`](../iportionformateffectivedata) インスタンスを返します。

### 例

以下の例は、PowerPoint プレゼンテーションの Paragraph の部分にラテンフォントを割り当てる方法を示しています。

```csharp
[C#]
//プレゼンテーションファイルを表すプレゼンテーションオブジェクトをインスタンス化します
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides はこれらの特別な識別子を使用します（PowerPoint で使用されるものと類似）:
// +mn-lt - 本文フォント Latin (マイナー Latin フォント)
// +mj-lt -見出しフォント Latin (メジャー Latin フォント)
// +mn-ea - 本文フォント East Asian (マイナー East Asian フォント)
// +mj-ea - 本文フォント East Asian (マイナー East Asian フォント)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### 関連項目

* クラス [BasePortionFormat](../baseportionformat)
* インターフェイス [IPortionFormat](../iportionformat)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->