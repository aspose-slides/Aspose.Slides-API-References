---
title: PortionFormat
second_title: Referência da API Aspose.Sildes para .NET
description: Esta classe contém as propriedades de formatação de trechos de texto. Ao contrário de IPortionFormatEffectiveData./iportionformateffectivedata, todas as propriedades desta classe são graváveis.
type: docs
weight: 9510
url: /pt/aspose.slides/portionformat/
---
## PortionFormat classe

Esta classe contém as propriedades de formatação de trechos de texto. Ao contrário de [`IPortionFormatEffectiveData`](../iportionformateffectivedata), todas as propriedades desta classe são graváveis.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PortionFormat](portionformat)() | Inicializa uma nova instância da classe [`PortionFormat`](../portionformat). |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Retorna ou define o Id de um idioma alternativo. Leitura/gravação String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obter a interface base IPresentationComponent. Somente leitura [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Retorna ou define o identificador de marcador. Leitura/gravação String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Retorna ou define as informações de fonte de script complexo. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leitura/gravação [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Retorna ou define as informações de fonte Leste Asiático. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leitura/gravação [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Retorna as propriedades de EffectFormat do texto. Nenhuma herança aplicada. Somente leitura [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Retorna ou define o texto sobrescrito ou subscrito. Valor de -100% (subscrito) a 100% (sobrescrito). **float.NaN** significa que o valor está indefinido e deve ser herdado do Mestre. Leitura/gravação Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Retorna as propriedades de FillFormat do texto. Nenhuma herança aplicada. Somente leitura [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Determina se a fonte está em negrito. Nenhuma herança aplicada. Leitura/gravação [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Retorna ou define a altura da fonte de um trecho. **float.NaN** significa que a altura está indefinida e deve ser herdada do Mestre. Leitura/gravação Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Determina se a fonte está em itálico. Nenhuma herança aplicada. Leitura/gravação [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Retorna ou define o tipo de sublinhado do texto. Nenhuma herança aplicada. Leitura/gravação [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Retorna a cor usada para realçar um texto. Nenhuma herança aplicada. Somente leitura [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Retorna ou define o hiperlink definido para clique do mouse. Leitura/gravação [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Gerenciador de hiperlinks. Somente leitura [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Retorna ou define o hiperlink definido para passagem do mouse. Leitura/gravação [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Determina se o estilo de sublinhado tem propriedades próprias de FillFormat ou as herda das propriedades de FillFormat do texto. Leitura/gravação [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Determina se o estilo de sublinhado tem propriedades próprias de LineFormat ou as herda das propriedades de LineFormat do texto. Leitura/gravação [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Retorna ou define o tamanho mínimo da fonte, para o qual o kerning deve ser ativado. **float.NaN** significa que o valor está indefinido e deve ser herdado do Mestre. Leitura/gravação Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Determina se os números devem ignorar o layout vertical de texto específico de idioma oriental. Nenhuma herança aplicada. Leitura/gravação [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Retorna ou define o Id de um idioma de revisão. Usado para verificação ortográfica e gramatical. Leitura/gravação String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Retorna ou define as informações de fonte Latina. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leitura/gravação [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Retorna as propriedades de LineFormat para contorno de texto. Nenhuma herança aplicada. Somente leitura [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Determina se a altura de um texto deve ser normalizada. Nenhuma herança aplicada. Leitura/gravação [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Determina se o texto não deve ser revisado. Nenhuma herança aplicada. Leitura/gravação [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Determina se a smart tag deve ser limpa. Nenhuma herança aplicada. Leitura/gravação Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Retorna ou define o incremento de espaçamento entre caracteres. **float.NaN** significa que o valor está indefinido e deve ser herdado do Mestre. Leitura/gravação Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Obtém ou define um valor que indica se a verificação ortográfica está ativada para o trecho de texto. Quando essa propriedade é definida como false, as verificações ortográficas para elementos de texto são suprimidas. Quando definida como true, a verificação ortográfica é permitida. O valor padrão é `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Retorna ou define o tipo de tachado de um texto. Nenhuma herança aplicada. Leitura/gravação [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Retorna ou define as informações de fonte simbólica. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leitura/gravação [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Retorna ou define o tipo de capitalização do texto. Nenhuma herança aplicada. Leitura/gravação [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Retorna as propriedades de FillFormat da linha de sublinhado. Nenhuma herança aplicada. Somente leitura [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Retorna as propriedades de LineFormat usadas para contornar a linha de sublinhado. Nenhuma herança aplicada. Somente leitura [`ILineFormat`](../ilineformat). |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compara com o objeto especificado. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Obtém os dados de formatação efetiva do trecho com a herança aplicada. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Retorna o código hash. |

### Observações

Esta classe é usada para retornar e manipular as propriedades de formatação de trechos de texto definidas para o trecho específico. Isso significa que nenhuma herança é aplicada ao obter valores, portanto na maioria dos casos você receberá valores que significam "indefinido".

Para obter os valores efetivos dos parâmetros de formatação, incluindo os herdados, você precisa usar o método [`GetEffective`](./geteffective) que retorna uma instância [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Exemplos

O exemplo a seguir mostra como atribuir a fonte Latina a um trecho de um Paragraph em uma apresentação PowerPoint.

```csharp
[C#]
//Instanciar um objeto de apresentação que representa um arquivo de apresentação
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides usa esses identificadores especiais (semelhantes aos usados no PowerPoint):
// +mn-lt - Fonte do Corpo Latin (Fonte Latin Menor)
// +mj-lt - Fonte do Cabeçalho Latin (Fonte Latin Maior)
// +mn-ea - Fonte do Corpo Leste Asiático (Fonte Leste Asiático Menor)
// +mj-ea - Fonte do Corpo Leste Asiático (Fonte Leste Asiático Menor)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Ver Também

* classe [BasePortionFormat](../baseportionformat)
* interface [IPortionFormat](../iportionformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->