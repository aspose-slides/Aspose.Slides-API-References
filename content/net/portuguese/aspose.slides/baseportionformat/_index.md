---
title: BasePortionFormat
second_title: Referência da API Aspose.Sildes para .NET
description: Propriedades comuns de formatação de porções de texto.
type: docs
weight: 970
url: /pt/aspose.slides/baseportionformat/
---
## classe BasePortionFormat

Propriedades comuns de formatação de porções de texto.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## Propriedades

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Retorna ou define o Id de um idioma alternativo. Leitura/gravação String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obter a interface base IPresentationComponent. Somente leitura [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Retorna ou define as informações de fonte de script complexo. Null significa que a fonte está indefinida e deve ser herdada do Master. Leitura/gravação [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Retorna ou define as informações de fonte East Asian. Null significa que a fonte está indefinida e deve ser herdada do Master. Leitura/gravação [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Retorna as propriedades de EffectFormat do texto. Nenhuma herança aplicada. Somente leitura [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Retorna ou define o texto sobrescrito ou subscrito. Valor de -100% (subscrito) a 100% (sobrescrito). **float.NaN** significa que o valor está indefinido e deve ser herdado do Master. Leitura/gravação Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Retorna as propriedades de FillFormat do texto. Nenhuma herança aplicada. Somente leitura [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Determina se a fonte está em negrito. Nenhuma herança aplicada. Leitura/gravação [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Retorna ou define a altura da fonte de uma porção. **float.NaN** significa que a altura está indefinida e deve ser herdada do Master. Leitura/gravação Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Determina se a fonte está em itálico. Nenhuma herança aplicada. Leitura/gravação [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Retorna ou define o tipo de sublinhado do texto. Nenhuma herança aplicada. Leitura/gravação [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Retorna a cor usada para destacar um texto. Nenhuma herança aplicada. Somente leitura [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Determina se o estilo de sublinhado tem suas próprias propriedades FillFormat ou as herda das propriedades FillFormat do texto. Leitura/gravação [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Determina se o estilo de sublinhado tem suas próprias propriedades LineFormat ou as herda das propriedades LineFormat do texto. Leitura/gravação [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Retorna ou define o tamanho mínimo da fonte, para o qual o kerning deve ser ativado. **float.NaN** significa que o valor está indefinido e deve ser herdado do Master. Leitura/gravação Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Determina se os números devem ignorar o layout vertical específico de idioma oriental do texto. Nenhuma herança aplicada. Leitura/gravação [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Retorna ou define o Id de um idioma de correção. Usado para verificação ortográfica e gramatical. Leitura/gravação String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Retorna ou define as informações de fonte Latin. Null significa que a fonte está indefinida e deve ser herdada do Master. Leitura/gravação [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Retorna as propriedades de LineFormat para contorno de texto. Nenhuma herança aplicada. Somente leitura [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Determina se a altura de um texto deve ser normalizada. Nenhuma herança aplicada. Leitura/gravação [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Determina se o texto não deve ser corrigido. Nenhuma herança aplicada. Leitura/gravação [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Retorna ou define o incremento de espaçamento entre caracteres. **float.NaN** significa que o valor está indefinido e deve ser herdado do Master. Leitura/gravação Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Obtém ou define um valor que indica se a verificação ortográfica está habilitada para a porção de texto. Quando essa propriedade está definida como false, as verificações ortográficas para elementos de texto são suprimidas. Quando definida como true, a verificação ortográfica é permitida. O valor padrão é `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Retorna ou define o tipo de tachado de um texto. Nenhuma herança aplicada. Leitura/gravação [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Retorna ou define as informações de fonte simbólica. Null significa que a fonte está indefinida e deve ser herdada do Master. Leitura/gravação [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Retorna ou define o tipo de capitalização do texto. Nenhuma herança aplicada. Leitura/gravação [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Retorna as propriedades FillFormat da linha de sublinhado. Nenhuma herança aplicada. Somente leitura [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Retorna as propriedades LineFormat usadas para contornar a linha de sublinhado. Nenhuma herança aplicada. Somente leitura [`ILineFormat`](../ilineformat). |

## Métodos

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compara com o objeto especificado. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Retorna o código hash. |

### Veja Também

* classe [PVIObject](../pviobject)
* interface [IBasePortionFormat](../ibaseportionformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->