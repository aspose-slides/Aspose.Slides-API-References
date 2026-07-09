---
title: ChartPortionFormat
second_title: Referência da API Aspose.Sildes para .NET
description: Esta classe contém as propriedades de formatação da parte do gráfico usadas em gráficos. Ao contrário de IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata todas as propriedades desta classe são graváveis.
type: docs
weight: 1430
url: /pt/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat classe

Esta classe contém as propriedades de formatação da parte do gráfico usadas em gráficos. Ao contrário de [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata), todas as propriedades desta classe são graváveis.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Retorna ou define o Id de um idioma alternativo. Leitura/gravação String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obter a interface base IPresentationComponent. Somente leitura [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Retorna ou define as informações da fonte de script complexo. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leitura/gravação [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Retorna ou define as informações da fonte do Leste Asiático. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leitura/gravação [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Retorna as propriedades EffectFormat do texto. Nenhuma herança aplicada. Somente leitura [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Retorna ou define o texto sobrescrito ou subscrito. Valor de -100% (subscrito) a 100% (sobrescrito). **float.NaN** significa que o valor está indefinido e deve ser herdado do Mestre. Leitura/gravação Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Retorna as propriedades FillFormat do texto. Nenhuma herança aplicada. Somente leitura [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Determina se a fonte está em negrito. Nenhuma herança aplicada. Leitura/gravação [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Retorna ou define a altura da fonte de uma porção. **float.NaN** significa que a altura está indefinida e deve ser herdada do Mestre. Leitura/gravação Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Determina se a fonte está itálica. Nenhuma herança aplicada. Leitura/gravação [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Retorna ou define o tipo de sublinhado do texto. Nenhuma herança aplicada. Leitura/gravação [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Retorna a cor usada para destacar um texto. Nenhuma herança aplicada. Somente leitura [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Determina se o estilo de sublinhado tem propriedades FillFormat próprias ou as herda das propriedades FillFormat do texto. Leitura/gravação [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Determina se o estilo de sublinhado tem propriedades LineFormat próprias ou as herda das propriedades LineFormat do texto. Leitura/gravação [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Retorna ou define o tamanho mínimo da fonte, para o qual o kerning deve ser ativado. **float.NaN** significa que o valor está indefinido e deve ser herdado do Mestre. Leitura/gravação Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Determina se os números devem ignorar o layout vertical específico de idioma oriental do texto. Nenhuma herança aplicada. Leitura/gravação [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Retorna ou define o Id de um idioma de revisão. Usado para verificação ortográfica e gramatical. Leitura/gravação String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Retorna ou define as informações da fonte Latina. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leitura/gravação [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Retorna as propriedades LineFormat para contorno de texto. Nenhuma herança aplicada. Somente leitura [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Determina se a altura do texto deve ser normalizada. Nenhuma herança aplicada. Leitura/gravação [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Determina se o texto não deve ser revisado. Nenhuma herança aplicada. Leitura/gravação [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Retorna ou define o incremento de espaçamento entre caracteres. **float.NaN** significa que o valor está indefinido e deve ser herdado do Mestre. Leitura/gravação Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Determina se a verificação ortográfica está habilitada para a porção de texto. Quando esta propriedade é definida como false, as verificações ortográficas para elementos de texto são suprimidas. Quando definida como true, a verificação ortográfica é permitida. Valor padrão é `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Retorna ou define o tipo de tachado de um texto. Nenhuma herança aplicada. Leitura/gravação [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Retorna ou define as informações da fonte simbólica. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leitura/gravação [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Retorna ou define o tipo de capitalização do texto. Nenhuma herança aplicada. Leitura/gravação [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Retorna as propriedades FillFormat da linha de sublinhado. Nenhuma herança aplicada. Somente leitura [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Retorna as propriedades LineFormat usadas para contornar a linha de sublinhado. Nenhuma herança aplicada. Somente leitura [`ILineFormat`](../../aspose.slides/ilineformat). |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compara com o objeto especificado. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Retorna o código hash. |

### Observações

Esta classe é usada para retornar e manipular as propriedades de formatação da parte do texto definidas para a porção específica. Isso significa que nenhuma herança é aplicada ao obter valores, portanto, na maioria dos casos você obterá valores que significam "indefinido".

Para obter os valores efetivos dos parâmetros de formatação, incluindo os herdados, você precisa usar o método [`GetEffective`](../../aspose.slides/portionformat/geteffective) que retorna uma instância [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata).

### Veja Também

* classe [BasePortionFormat](../../aspose.slides/baseportionformat)
* interface [IChartPortionFormat](../ichartportionformat)
* espaço de nomes [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->