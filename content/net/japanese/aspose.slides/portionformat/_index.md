---
title: PortionFormat
second_title: Aspose.Sildes for .NET API リファレンス
description: このクラスはテキスト部分の書式設定プロパティを含みます。IPortionFormatEffectiveData./iportionformateffectivedata とは異なり、このクラスのすべてのプロパティは書き込み可能です。
type: docs
weight: 9490
url: /ja/aspose.slides/portionformat/
---
## PortionFormat クラス

このクラスはテキスト部分の書式設定プロパティを含みます。[`IPortionFormatEffectiveData`](../iportionformateffectivedata) とは異なり、このクラスのすべてのプロパティは書き込み可能です。

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PortionFormat](portionformat)() | 新しい [`PortionFormat`](../portionformat) クラスのインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | 代替言語の Id を取得または設定します。読み取り/書き込み可能な String。 |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | 基本的な IPresentationComponent インターフェイスを取得できます。読み取り専用 [`IPresentationComponent`](../ipresentationcomponent)。 |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | ブックマーク識別子を取得または設定します。読み取り/書き込み可能な String。 |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | 複合スクリプト フォント情報を取得または設定します。null はフォントが未定義であり、Master から継承されるべきことを意味します。読み取り/書き込み可能な [`IFontData`](../ifontdata)。 |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | 東アジアフォント情報を取得または設定します。null はフォントが未定義であり、Master から継承されるべきことを意味します。読み取り/書き込み可能な [`IFontData`](../ifontdata)。 |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | テキストの EffectFormat プロパティを取得します。継承は適用されません。読み取り専用 [`IEffectFormat`](../ieffectformat)。 |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | 上付きまたは下付きテキストを取得または設定します。値は -100%（下付き）から 100%（上付き）です。**float.NaN** は値が未定義であり、Master から継承されるべきことを意味します。読み取り/書き込み可能な Single。 |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | テキストの FillFormat プロパティを取得します。継承は適用されません。読み取り専用 [`IFillFormat`](../ifillformat)。 |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | フォントが太字かどうかを決定します。継承は適用されません。読み取り/書き込み可能な [`NullableBool`](../nullablebool)。 |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | 部分のフォント高さを取得または設定します。**float.NaN** は高さが未定義であり、Master から継承されるべきことを意味します。読み取り/書き込み可能な Single。 |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | フォントがイタリックかどうかを決定します。継承は適用されません。読み取り/書き込み可能な [`NullableBool`](../nullablebool)。 |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | テキストの下線タイプを取得または設定します。継承は適用されません。読み取り/書き込み可能な [`TextUnderlineType`](../textunderlinetype)。 |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | テキストのハイライトに使用される色を取得します。継承は適用されません。読み取り専用 [`IColorFormat`](../icolorformat)。 |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | マウスクリック用に定義されたハイパーリンクを取得または設定します。読み取り/書き込み可能な [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | ハイパーリンクマネージャー。読み取り専用 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | マウスオーバー用に定義されたハイパーリンクを取得または設定します。読み取り/書き込み可能な [`IHyperlink`](../ihyperlink)。 |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | 下線スタイルが独自の FillFormat プロパティを持つか、テキストの FillFormat プロパティから継承するかを決定します。読み取り/書き込み可能な [`NullableBool`](../nullablebool)。 |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | 下線スタイルが独自の LineFormat プロパティを持つか、テキストの LineFormat プロパティから継承するかを決定します。読み取り/書き込み可能な [`NullableBool`](../nullablebool)。 |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | カーニングを有効にすべき最小フォントサイズを取得または設定します。**float.NaN** は値が未定義であり、Master から継承されるべきことを意味します。読み取り/書き込み可能な Single。 |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | 数字がテキストの東アジア言語固有の縦書きレイアウトを無視すべきかどうかを決定します。継承は適用されません。読み取り/書き込み可能な [`NullableBool`](../nullablebool)。 |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | 校正言語の Id を取得または設定します。スペルチェックと文法チェックに使用されます。読み取り/書き込み可能な String。 |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | ラテンフォント情報を取得または設定します。null はフォントが未定義であり、Master から継承されるべきことを意味します。読み取り/書き込み可能な [`IFontData`](../ifontdata)。 |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | テキストアウトライン用の LineFormat プロパティを取得します。継承は適用されません。読み取り専用 [`ILineFormat`](../ilineformat)。 |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | テキストの高さを正規化すべきかどうかを決定します。継承は適用されません。読み取り/書き込み可能な [`NullableBool`](../nullablebool)。 |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | テキストが校正されないようにすべきかどうかを決定します。継承は適用されません。読み取り/書き込み可能な [`NullableBool`](../nullablebool)。 |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | スマートタグをクリーンアップすべきかどうかを決定します。継承は適用されません。読み取り/書き込み可能な Boolean。 |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | 文字間スペースの増分を取得または設定します。**float.NaN** は値が未定義であり、Master から継承されるべきことを意味します。読み取り/書き込み可能な Single。 |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | テキスト部分に対してスペルチェックが有効かどうかを示す値を取得または設定します。このプロパティが false に設定されている場合、テキスト要素のスペルチェックは抑制されます。true に設定すると、スペルチェックが許可されます。デフォルト値は `false` です。 |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | テキストの取り消し線タイプを取得または設定します。継承は適用されません。読み取り/書き込み可能な [`TextStrikethroughType`](../textstrikethroughtype)。 |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | シンボリックフォント情報を取得または設定します。null はフォントが未定義であり、Master から継承されるべきことを意味します。読み取り/書き込み可能な [`IFontData`](../ifontdata)。 |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | テキストの大文字化タイプを取得または設定します。継承は適用されません。読み取り/書き込み可能な [`TextCapType`](../textcaptype)。 |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | 下線線の FillFormat プロパティを取得します。継承は適用されません。読み取り専用 [`IFillFormat`](../ifillformat)。 |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | 下線線のアウトラインに使用される LineFormat プロパティを取得します。継承は適用されません。読み取り専用 [`ILineFormat`](../ilineformat)。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | 指定されたオブジェクトと比較します。 |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | 継承が適用された有効な部分書式設定データを取得します。 |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | ハッシュコードを返します。 |

### 備考

このクラスは、特定の部分に対して定義されたテキスト部分の書式設定プロパティを取得および操作するために使用されます。これは、値を取得する際に継承が適用されないことを意味し、ほとんどの場合「未定義」の値が得られます。

継承を含む有効な書式設定パラメータ値を取得するには、[`GetEffective`](./geteffective) メソッドを使用する必要があります。このメソッドは [`IPortionFormatEffectiveData`](../iportionformateffectivedata) インスタンスを返します。

### 例

以下の例は、PowerPoint プレゼンテーションの Paragraph の部分にラテンフォントを割り当てる方法を示します。

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
// Aspose.Slides はこれらの特殊識別子を使用します（PowerPoint で使用されるものと類似）:
// +mn-lt - 本文フォント ラテン文字（マイナーフォント ラテン文字）
// +mj-lt - 見出しフォント ラテン文字（メジャーフォント ラテン文字）
// +mn-ea - 本文フォント 東アジア文字（マイナーフォント 東アジア文字）
// +mj-ea - 本文フォント 東アジア文字（マイナーフォント 東アジア文字）
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### 関連項目

* クラス [BasePortionFormat](../baseportionformat)
* インターフェイス [IPortionFormat](../iportionformat)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->