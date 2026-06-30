---
title: IBasePortionFormat
second_title: Aspose.Sildes para .NET Referência da API
description: Esta classe contém as propriedades de formatação de porções de texto. Ao contrário de IPortionFormatEffectiveData./iportionformateffectivedata, todas as propriedades desta classe são graváveis.
type: docs
weight: 5290
url: /pt/aspose.slides/ibaseportionformat/
---
## Interface IBasePortionFormat

Esta classe contém as propriedades de formatação de porções de texto. Ao contrário de [`IPortionFormatEffectiveData`](../iportionformateffectivedata), todas as propriedades desta classe são graváveis.

```csharp
public interface IBasePortionFormat
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Retorna ou define o Id de um idioma alternativo. Leitura/Gravação String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Retorna ou define as informações da fonte de script complexo. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leitura/Gravação [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Retorna ou define as informações da fonte leste-asiática. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leitura/Gravação [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Retorna as propriedades EffectFormat do texto. Nenhuma herança aplicada. Somente leitura [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Retorna ou define o texto sobrescrito ou subscrito. Valor de -100% (subscrito) a 100% (sobrescrito). **float.NaN** significa que o valor está indefinido e deve ser herdado do Mestre. Leitura/Gravação Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Retorna as propriedades FillFormat do texto. Nenhuma herança aplicada. Somente leitura [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Determina se a fonte está em negrito. Nenhuma herança aplicada. Leitura/Gravação [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Retorna ou define a altura da fonte de uma porção. **float.NaN** significa que a altura está indefinida e deve ser herdada do Mestre. Leitura/Gravação Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Determina se a fonte está em itálico. Nenhuma herança aplicada. Leitura/Gravação [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Retorna ou define o tipo de sublinhado do texto. Nenhuma herança aplicada. Leitura/Gravação [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Retorna a cor usada para realçar um texto. Nenhuma herança aplicada. Somente leitura [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Determina se o estilo de sublinhado tem propriedades FillFormat próprias ou as herda das propriedades FillFormat do texto. Leitura/Gravação [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Determina se o estilo de sublinhado tem propriedades LineFormat próprias ou as herda das propriedades LineFormat do texto. Leitura/Gravação [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Retorna ou define o tamanho mínimo da fonte, para o qual o kerning deve ser ativado. **float.NaN** significa que o valor está indefinido e deve ser herdado do Mestre. Leitura/Gravação Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Determina se os números devem ignorar o layout vertical específico de idioma oriental do texto. Nenhuma herança aplicada. Leitura/Gravação [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Retorna ou define o Id de um idioma de revisão. Usado para verificação ortográfica e gramatical. Leitura/Gravação String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Retorna ou define as informações da fonte latina. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leitura/Gravação [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Retorna as propriedades LineFormat para contorno de texto. Nenhuma herança aplicada. Somente leitura [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Determina se a altura do texto deve ser normalizada. Nenhuma herança aplicada. Leitura/Gravação [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Determina se o texto não deve ser revisado. Nenhuma herança aplicada. Leitura/Gravação [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Retorna ou define o incremento do espaçamento entre caracteres. **float.NaN** significa que o valor está indefinido e deve ser herdado do Mestre. Leitura/Gravação Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | Obtém ou define um valor que indica se a verificação ortográfica está habilitada para a porção de texto. Quando esta propriedade é definida como false, as verificações ortográficas para elementos de texto são suprimidas. Quando definida como true, a verificação ortográfica é permitida. O valor padrão é `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Retorna ou define o tipo de tachado do texto. Nenhuma herança aplicada. Leitura/Gravação [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Retorna ou define as informações da fonte simbólica. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leitura/Gravação [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Retorna ou define o tipo de capitalização do texto. Nenhuma herança aplicada. Leitura/Gravação [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Retorna as propriedades FillFormat da linha de sublinhado. Nenhuma herança aplicada. Somente leitura [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Retorna as propriedades LineFormat usadas para contornar a linha de sublinhado. Nenhuma herança aplicada. Somente leitura [`ILineFormat`](../ilineformat). |

### Observações

Esta classe é usada para obter e manipular as propriedades de formatação de porções de texto definidas para a porção específica. Isso significa que nenhuma herança é aplicada ao obter valores, portanto, na maioria dos casos você receberá valores que significam "indefinido".

Para obter os valores efetivos dos parâmetros de formatação, incluindo os herdados, você precisa usar o método [`GetEffective`](../iportionformat/geteffective) que retorna uma instância [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Veja Também

* espaço de nomes [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->