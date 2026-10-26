---
title: BasePortionFormat
second_title: Aspose.Sildes for .NET API リファレンス
description: テキスト部分の共通書式設定プロパティ。
type: docs
weight: 970
url: /ja/aspose.slides/baseportionformat/
---
## BasePortionFormat クラス

テキスト部分の共通書式設定プロパティ。

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | 代替言語の Id を取得または設定します。読み書き可能な String。 |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | ベースの IPresentationComponent インターフェイスを取得できます。読み取り専用 [`IPresentationComponent`](../ipresentationcomponent)。 |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | 複雑なスクリプトのフォント情報を取得または設定します。Null はフォントが未定義であり、マスターから継承されることを意味します。読み書き可能な [`IFontData`](../ifontdata)。 |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | 東アジアのフォント情報を取得または設定します。Null はフォントが未定義であり、マスターから継承されることを意味します。読み書き可能な [`IFontData`](../ifontdata)。 |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | テキストの EffectFormat プロパティを取得します。継承は適用されません。読み取り専用 [`IEffectFormat`](../ieffectformat)。 |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | 上付きまたは下付きテキストを取得または設定します。値は -100%（下付き）から 100%（上付き）です。**float.NaN** は値が未定義であり、マスターから継承されることを意味します。読み書き可能な Single。 |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | テキストの FillFormat プロパティを取得します。継承は適用されません。読み取り専用 [`IFillFormat`](../ifillformat)。 |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | フォントが太字かどうかを決定します。継承は適用されません。読み書き可能な [`NullableBool`](../nullablebool)。 |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | 部分のフォント高さを取得または設定します。**float.NaN** は高さが未定義であり、マスターから継承されることを意味します。読み書き可能な Single。 |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | フォントが斜体かどうかを決定します。継承は適用されません。読み書き可能な [`NullableBool`](../nullablebool)。 |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | テキストの下線タイプを取得または設定します。継承は適用されません。読み書き可能な [`TextUnderlineType`](../textunderlinetype)。 |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | テキストのハイライトに使用される色を取得します。継承は適用されません。読み取り専用 [`IColorFormat`](../icolorformat)。 |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | 下線スタイルが独自の FillFormat プロパティを持つか、テキストの FillFormat プロパティから継承するかを決定します。読み書き可能な [`NullableBool`](../nullablebool)。 |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | 下線スタイルが独自の LineFormat プロパティを持つか、テキストの LineFormat プロパティから継承するかを決定します。読み書き可能な [`NullableBool`](../nullablebool)。 |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | カーニングを有効にすべき最小フォントサイズを取得または設定します。**float.NaN** は値が未定義であり、マスターから継承されることを意味します。読み書き可能な Single。 |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | 数字がテキストの東アジア言語固有の縦書きレイアウトを無視すべきかどうかを決定します。継承は適用されません。読み書き可能な [`NullableBool`](../nullablebool)。 |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | 校正言語の Id を取得または設定します。スペルチェックおよび文法チェックに使用されます。読み書き可能な String。 |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | ラテン文字のフォント情報を取得または設定します。Null はフォントが未定義であり、マスターから継承されることを意味します。読み書き可能な [`IFontData`](../ifontdata)。 |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | テキスト輪郭の LineFormat プロパティを取得します。継承は適用されません。読み取り専用 [`ILineFormat`](../ilineformat)。 |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | テキストの高さを正規化すべきかどうかを決定します。継承は適用されません。読み書き可能な [`NullableBool`](../nullablebool)。 |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | テキストが校正されないようにすべきかどうかを決定します。継承は適用されません。読み書き可能な [`NullableBool`](../nullablebool)。 |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | 文字間の間隔増分を取得または設定します。**float.NaN** は値が未定義であり、マスターから継承されることを意味します。読み書き可能な Single。 |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | テキスト部分に対してスペルチェックが有効かどうかを示す値を取得または設定します。このプロパティが `false` に設定されている場合、テキスト要素のスペルチェックは抑制されます。`true` に設定すると、スペルチェックが許可されます。デフォルト値は `false` です。 |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | テキストの取り消し線タイプを取得または設定します。継承は適用されません。読み書き可能な [`TextStrikethroughType`](../textstrikethroughtype)。 |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | シンボリックフォント情報を取得または設定します。Null はフォントが未定義であり、マスターから継承されることを意味します。読み書き可能な [`IFontData`](../ifontdata)。 |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | テキストの大文字化タイプを取得または設定します。継承は適用されません。読み書き可能な [`TextCapType`](../textcaptype)。 |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | 下線ラインの FillFormat プロパティを取得します。継承は適用されません。読み取り専用 [`IFillFormat`](../ifillformat)。 |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | 下線ラインの輪郭に使用される LineFormat プロパティを取得します。継承は適用されません。読み取り専用 [`ILineFormat`](../ilineformat)。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | 指定されたオブジェクトと比較します。 |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | ハッシュコードを返します。 |

### 関連項目

* クラス [PVIObject](../pviobject)
* インターフェイス [IBasePortionFormat](../ibaseportionformat)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->