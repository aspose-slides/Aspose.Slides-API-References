---
title: PortionFormat
second_title: Referência da API Aspose.Sildes para .NET
description: Esta classe contém as propriedades de formatação de parte de texto. Ao contrário de IPortionFormatEffectiveData./iportionformateffectivedata, todas as propriedades desta classe são graváveis.
type: docs
weight: 9470
url: /pt/aspose.slides/portionformat/
---
## PortionFormat classe

Esta classe contém as propriedades de formatação de parte de texto. Ao contrário de [`IPortionFormatEffectiveData`](../iportionformateffectivedata), todas as propriedades desta classe são graváveis.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## Construtores

| Name | Description |
| --- | --- |
| [PortionFormat](portionformat)() | Inicializa uma nova instância da classe [`PortionFormat`](../portionformat). |

## Propriedades

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Retorna ou define o Id de um idioma alternativo. Leitura/Gravação String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obter a interface base IPresentationComponent. Somente leitura [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Retorna ou define o identificador do marcador. Leitura/Gravação String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Retorna ou define as informações de fonte de script complexo. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leitura/Gravação [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Retorna ou define as informações de fonte da Ásia Oriental. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leitura/Gravação [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Retorna as propriedades de EffectFormat do texto. Nenhuma herança aplicada. Somente leitura [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Retorna ou define o texto sobrescrito ou subscrito. Valor de -100% (subscrito) a 100% (sobrescrito). **float.NaN** significa que o valor está indefinido e deve ser herdado do Mestre. Leitura/Gravação Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Retorna as propriedades de FillFormat do texto. Nenhuma herança aplicada. Somente leitura [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Determina se a fonte está em negrito. Nenhuma herança aplicada. Leitura/Gravação [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Retorna ou define a altura da fonte de uma parte. **float.NaN** significa que a altura está indefinida e deve ser herdada do Mestre. Leitura/Gravação Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Determina se a fonte está itálica. Nenhuma herança aplicada. Leitura/Gravação [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Retorna ou define o tipo de sublinhado do texto. Nenhuma herança aplicada. Leitura/Gravação [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Retorna a cor usada para realçar um texto. Nenhuma herança aplicada. Somente leitura [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Retorna ou define o hyperlink definido para clique do mouse. Leitura/Gravação [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Gerenciador de hyperlinks. Somente leitura [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Retorna ou define o hyperlink definido para passagem do mouse. Leitura/Gravação [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Determina se o estilo de sublinhado tem propriedades próprias de FillFormat ou as herda das propriedades de FillFormat do texto. Leitura/Gravação [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Determina se o estilo de sublinhado tem propriedades próprias de LineFormat ou as herda das propriedades de LineFormat do texto. Leitura/Gravação [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Retorna ou define o tamanho mínimo da fonte, para o qual o kerning deve ser ativado. **float.NaN** significa que o valor está indefinido e deve ser herdado do Mestre. Leitura/Gravação Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Determina se os números devem ignorar o layout vertical de texto específico de idioma oriental. Nenhuma herança aplicada. Leitura/Gravação [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Retorna ou define o Id de um idioma de revisão. Usado para verificação ortográfica e gramatical. Leitura/Gravação String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Retorna ou define as informações de fonte Latina. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leitura/Gravação [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Retorna as propriedades de LineFormat para contorno de texto. Nenhuma herança aplicada. Somente leitura [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Determina se a altura do texto deve ser normalizada. Nenhuma herança aplicada. Leitura/Gravação [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Determina se o texto não deve ser revisado. Nenhuma herança aplicada. Leitura/Gravação [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Determina se a smart tag deve ser limpa. Nenhuma herança aplicada. Leitura/Gravação Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Retorna ou define o incremento de espaçamento intercaracteres. **float.NaN** significa que o valor está indefinido e deve ser herdado do Mestre. Leitura/Gravação Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Obtém ou define um valor que indica se a verificação ortográfica está habilitada para a parte de texto. Quando esta propriedade é definida como false, as verificações ortográficas para elementos de texto são suprimidas. Quando definida como true, a verificação ortográfica é permitida. O valor padrão é `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Retorna ou define o tipo de tachado de um texto. Nenhuma herança aplicada. Leitura/Gravação [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Retorna ou define as informações de fonte simbólica. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leitura/Gravação [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Retorna ou define o tipo de capitalização do texto. Nenhuma herança aplicada. Leitura/Gravação [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Retorna as propriedades de FillFormat da linha de sublinhado. Nenhuma herança aplicada. Somente leitura [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Retorna as propriedades de LineFormat usadas para contornar a linha de sublinhado. Nenhuma herança aplicada. Somente leitura [`ILineFormat`](../ilineformat). |

## Métodos

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compara com o objeto especificado. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Obtém os dados de formatação efetiva da parte com a herança aplicada. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Retorna o código hash. |

### Observações

Esta classe é usada para retornar e manipular as propriedades de formatação de parte de texto definidas para a parte específica. Isso significa que nenhuma herança é aplicada ao obter valores, portanto, na maioria dos casos você receberá valores que significam "indefinido". Para obter os valores efetivos dos parâmetros de formatação, incluindo os herdados, você precisa usar o método [`GetEffective`](./geteffective) que retorna uma instância [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Exemplos

Os exemplos a seguir mostram como atribuir a fonte Latina a uma parte de Parágrafo de uma Apresentação PowerPoint.

```csharp
[C#]
//Instancia um objeto de apresentação que representa um arquivo de apresentação
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides usa esses identificadores especiais (semelhantes aos usados no PowerPoint):
// +mn-lt - Fonte do Corpo Latin (Fonte Latin Menor)
// +mj-lt - Fonte de Cabeçalho Latin (Fonte Latin Maior)
// +mn-ea - Fonte do Corpo Oriental (Fonte Oriental Menor)
// +mj-ea - Fonte do Corpo Oriental (Fonte Oriental Menor)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Veja Também

* classe [BasePortionFormat](../baseportionformat)
* interface [IPortionFormat](../iportionformat)
* espaço de nomes [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->