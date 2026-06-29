---
title: BasePortionFormat
second_title: Aspose.Sildes for .NET API リファレンス
description: 共通テキスト部分の書式設定プロパティ。
type: docs
weight: 950
url: /ja/aspose.slides/baseportionformat/
---
## BasePortionFormat クラス

共通テキスト部分の書式設定プロパティ。

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | 代替言語の Id を取得または設定します。 読み書き String。 |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | 基本 IPresentationComponent インターフェイスを取得できます。 読み取り専用 [`IPresentationComponent`](../ipresentationcomponent)。 |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | 複雑なスクリプトのフォント情報を取得または設定します。 Null はフォントが未定義であり、マスターから継承されることを意味します。 読み書き [`IFontData`](../ifontdata)。 |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | 東アジアフォント情報を取得または設定します。 Null はフォントが未定義であり、マスターから継承されることを意味します。 読み書き [`IFontData`](../ifontdata)。 |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | テキストの EffectFormat プロパティを取得します。 継承は適用されません。 読み取り専用 [`IEffectFormat`](../ieffectformat)。 |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | 上付きまたは下付きテキストを取得または設定します。 値は -100%（下付き）から 100%（上付き）です。 **float.NaN** は値が未定義であり、マスターから継承されることを意味します。 読み書き Single。 |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | テキストの FillFormat プロパティを取得します。 継承は適用されません。 読み取り専用 [`IFillFormat`](../ifillformat)。 |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | フォントが太字かどうかを決定します。 継承は適用されません。 読み書き [`NullableBool`](../nullablebool)。 |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | 部分のフォント高さを取得または設定します。 **float.NaN** は高さが未定義であり、マスターから継承されることを意味します。 読み書き Single。 |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | フォントが斜体かどうかを決定します。 継承は適用されません。 読み書き [`NullableBool`](../nullablebool)。 |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | テキストの下線タイプを取得または設定します。 継承は適用されません。 読み書き [`TextUnderlineType`](../textunderlinetype)。 |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | テキストのハイライトに使用される色を取得します。 継承は適用されません。 読み取り専用 [`IColorFormat`](../icolorformat)。 |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | 下線スタイルが独自の FillFormat プロパティを持つか、テキストの FillFormat プロパティから継承するかを決定します。 読み書き [`NullableBool`](../nullablebool)。 |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | 下線スタイルが独自の LineFormat プロパティを持つか、テキストの LineFormat プロパティから継承するかを決定します。 読み書き [`NullableBool`](../nullablebool)。 |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | カーニングが有効になる最小フォントサイズを取得または設定します。 **float.NaN** は値が未定義であり、マスターから継承されることを意味します。 読み書き Single。 |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | 数値がテキストの東アジア言語固有の縦書きレイアウトを無視すべきかどうかを決定します。 継承は適用されません。 読み書き [`NullableBool`](../nullablebool)。 |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | 校正言語の Id を取得または設定します。 スペルチェックと文法チェックに使用されます。 読み書き String。 |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | ラテンフォント情報を取得または設定します。 Null はフォントが未定義であり、マスターから継承されることを意味します。 読み書き [`IFontData`](../ifontdata)。 |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | テキストのアウトライン用 LineFormat プロパティを取得します。 継承は適用されません。 読み取り専用 [`ILineFormat`](../ilineformat)。 |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | テキストの高さを正規化すべきかどうかを決定します。 継承は適用されません。 読み書き [`NullableBool`](../nullablebool)。 |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | テキストを校正対象外にするかどうかを決定します。 継承は適用されません。 読み書き [`NullableBool`](../nullablebool)。 |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | 文字間隔増分を取得または設定します。 **float.NaN** は値が未定義であり、マスターから継承されることを意味します。 読み書き Single。 |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | テキスト部分のスペルチェックが有効かどうかを示す値を取得または設定します。このプロパティが false に設定されている場合、テキスト要素のスペルチェックは抑制されます。true に設定すると、スペルチェックが許可されます。既定値は `false` です。 |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | テキストの取り消し線タイプを取得または設定します。 継承は適用されません。 読み書き [`TextStrikethroughType`](../textstrikethroughtype)。 |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | シンボリックフォント情報を取得または設定します。 Null はフォントが未定義であり、マスターから継承されることを意味します。 読み書き [`IFontData`](../ifontdata)。 |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | テキストの大文字化タイプを取得または設定します。 継承は適用されません。 読み書き [`TextCapType`](../textcaptype)。 |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | 下線ラインの FillFormat プロパティを取得します。 継承は適用されません。 読み取り専用 [`IFillFormat`](../ifillformat)。 |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | 下線ラインのアウトラインに使用される LineFormat プロパティを取得します。 継承は適用されません。 読み取り専用 [`ILineFormat`](../ilineformat)。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | 指定されたオブジェクトと比較します。 |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | ハッシュコードを返します。 |

### 参照

* クラス [PVIObject](../pviobject)
* インターフェイス [IBasePortionFormat](../ibaseportionformat)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->