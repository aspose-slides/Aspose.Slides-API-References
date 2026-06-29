---
title: IBasePortionFormat
second_title: Aspose.Sildes for .NET API リファレンス
description: このクラスはテキスト部分の書式設定プロパティを含みます。IPortionFormatEffectiveData./iportionformateffectivedataとは異なり、このクラスのすべてのプロパティは書き込み可能です。
type: docs
weight: 5290
url: /ja/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat インターフェイス

このクラスはテキスト部分の書式設定プロパティを含みます。[`IPortionFormatEffectiveData`](../iportionformateffectivedata)とは異なり、このクラスのすべてのプロパティは書き込み可能です。

```csharp
public interface IBasePortionFormat
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | 代替言語の Id を取得または設定します。Read/write String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | 複合文字スクリプトのフォント情報を取得または設定します。Null はフォントが未定義であり、マスターから継承されることを意味します。Read/write [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | 東アジアフォント情報を取得または設定します。Null はフォントが未定義であり、マスターから継承されることを意味します。Read/write [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | テキストの EffectFormat プロパティを取得します。継承は適用されません。Read-only [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | 上付きまたは下付きテキストを取得または設定します。値は -100%（下付き）から 100%（上付き）です。**float.NaN** は値が未定義であり、マスターから継承されることを意味します。Read/write Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | テキストの FillFormat プロパティを取得します。継承は適用されません。Read-only [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | フォントが太字かどうかを決定します。継承は適用されません。Read/write [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | 部分のフォント高さを取得または設定します。**float.NaN** は高さが未定義であり、マスターから継承されることを意味します。Read/write Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | フォントがイタリックかどうかを決定します。継承は適用されません。Read/write [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | テキストの下線タイプを取得または設定します。継承は適用されません。Read/write [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | テキストのハイライトに使用される色を取得します。継承は適用されません。Read-only [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | 下線スタイルが独自の FillFormat プロパティを持つか、テキストの FillFormat プロパティから継承するかを決定します。Read/write [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | 下線スタイルが独自の LineFormat プロパティを持つか、テキストの LineFormat プロパティから継承するかを決定します。Read/write [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | カーニングを有効にすべき最小フォントサイズを取得または設定します。**float.NaN** は値が未定義であり、マスターから継承されることを意味します。Read/write Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | 数字がテキストの東アジア言語固有の縦書きレイアウトを無視すべきかどうかを決定します。継承は適用されません。Read/write [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | 校正言語の Id を取得または設定します。スペルと文法のチェックに使用されます。Read/write String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | ラテンフォント情報を取得または設定します。Null はフォントが未定義であり、マスターから継承されることを意味します。Read/write [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | テキストのアウトライン用 LineFormat プロパティを取得します。継承は適用されません。Read-only [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | テキストの高さを正規化すべきかどうかを決定します。継承は適用されません。Read/write [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | テキストが校正されないようにすべきかどうかを決定します。継承は適用されません。Read/write [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | 文字間スペーシングの増分を取得または設定します。**float.NaN** は値が未定義であり、マスターから継承されることを意味します。Read/write Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | テキスト部分のスペルチェックが有効かどうかを示す値を取得または設定します。このプロパティが false に設定されている場合、テキスト要素のスペルチェックは抑制されます。true に設定すると、スペルチェックが許可されます。デフォルト値は `false` です。 |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | テキストの打ち消し線タイプを取得または設定します。継承は適用されません。Read/write [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | シンボリックフォント情報を取得または設定します。Null はフォントが未定義であり、マスターから継承されることを意味します。Read/write [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | テキストの大文字化タイプを取得または設定します。継承は適用されません。Read/write [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | 下線ラインの FillFormat プロパティを取得します。継承は適用されません。Read-only [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | 下線ラインのアウトラインに使用される LineFormat プロパティを取得します。継承は適用されません。Read-only [`ILineFormat`](../ilineformat). |

### 備考

このクラスは、特定の部分に定義されたテキスト部分の書式設定プロパティを取得および操作するために使用されます。これは、値を取得する際に継承が適用されないことを意味し、ほとんどの場合「未定義」の値が返されます。

継承を含む有効な書式設定パラメータ値を取得するには、[`GetEffective`](../iportionformat/geteffective) メソッドを使用する必要があります。このメソッドは [`IPortionFormatEffectiveData`](../iportionformateffectivedata) インスタンスを返します。

### 参照

* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->