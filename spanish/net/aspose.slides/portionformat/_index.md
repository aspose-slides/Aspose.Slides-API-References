---
title: PortionFormat
second_title: Referencia de la API de Aspose.Slides para .NET
description: Esta clase contiene las propiedades de formato de la parte de texto. A diferencia deIPortionFormatEffectiveData./iportionformateffectivedata  todas las propiedades de esta clase se pueden escribir.
type: docs
weight: 8760
url: /es/net/aspose.slides/portionformat/
---
## PortionFormat class

Esta clase contiene las propiedades de formato de la parte de texto. A diferencia de[`IPortionFormatEffectiveData`](../iportionformateffectivedata) , todas las propiedades de esta clase se pueden escribir.

```csharp
public class PortionFormat : BasePortionFormat, IPortionFormat
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PortionFormat](portionformat)() | Inicializa una nueva instancia de[`PortionFormat`](../portionformat) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Devuelve o establece el Id de un idioma alternativo. Lectura/escrituraString . |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obtener la interfaz base IPPresentationComponent. Solo lectura[`IPresentationComponent`](../ipresentationcomponent) . |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Devuelve o establece el identificador de marcador. Lectura/escrituraString . |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Devuelve o establece la información de la fuente de secuencia de comandos compleja. Nulo significa que la fuente no está definida y debe heredarse del Maestro. Lectura/escritura[`IFontData`](../ifontdata) . |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Devuelve o establece la información de la fuente de Asia oriental. Nulo significa que la fuente no está definida y debe heredarse del Maestro. Lectura/escritura[`IFontData`](../ifontdata) . |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Devuelve las propiedades de EffectFormat del texto. Sin herencia aplicada. Solo lectura[`IEffectFormat`](../ieffectformat) . |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Devuelve o establece el texto en superíndice o subíndice. Valor de -100% (subíndice) a 100% (superíndice).  **float.NaN** significa que el valor no está definido y debe heredarse del Maestro. Lectura/escrituraSingle . |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Devuelve las propiedades del formato de relleno del texto. Sin herencia aplicada. Solo lectura[`IFillFormat`](../ifillformat) . |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Determina si la fuente está en negrita. No se aplica herencia. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Devuelve o establece la altura de fuente de una porción.  **float.NaN** significa que la altura no está definida y debe heredarse del Maestro. Lectura/escrituraSingle . |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Determina si la fuente es cursiva. No se aplica herencia. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Devuelve o establece el tipo de subrayado del texto. No se aplica herencia. Lectura/escritura[`TextUnderlineType`](../textunderlinetype) . |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Devuelve el color utilizado para resaltar un texto. Sin herencia aplicada. Solo lectura[`IColorFormat`](../icolorformat) . |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Devuelve o establece el hipervínculo definido para el clic del mouse. Lectura/escritura[`IHyperlink`](../ihyperlink) . |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Administrador de hipervínculos. Solo lectura[`IHyperlinkManager`](../ihyperlinkmanager) . |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Devuelve o establece el hipervínculo definido para pasar el mouse. Lectura/escritura[`IHyperlink`](../ihyperlink) . |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Determina si el estilo de subrayado tiene propiedades propias de FillFormat o las hereda de las propiedades de FillFormat del texto. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Determina si el estilo de subrayado tiene propiedades LineFormat propias o las hereda de las propiedades LineFormat del texto. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Devuelve o establece el tamaño de fuente mínimo, para el cual se debe activar el interletraje.  **float.NaN** significa que el valor no está definido y debe heredarse del Maestro. Lectura/escrituraSingle . |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Determina si los números deben ignorar el diseño de texto vertical específico del idioma oriental. No se aplica herencia. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Devuelve o establece el Id de un idioma de revisión. Se utiliza para revisar la ortografía y la gramática. Lectura/escrituraString . |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Devuelve o establece la fuente latina info. Nulo significa que la fuente no está definida y debe heredarse del Maestro. Lectura/escritura[`IFontData`](../ifontdata) . |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Devuelve las propiedades de LineFormat para el esquema de texto. Sin herencia aplicada. Solo lectura[`ILineFormat`](../ilineformat) . |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Determina si se debe normalizar la altura de un texto. No se aplica herencia. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Determina si el texto no debe revisarse. No se aplica herencia. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Determina si se debe limpiar la etiqueta inteligente. No se aplica herencia. Lectura/escrituraBoolean . |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Devuelve o establece el incremento de espaciado entre caracteres.  **float.NaN** significa que el valor no está definido y debe heredarse del Maestro. Lectura/escrituraSingle . |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Devuelve o establece el tipo de tachado de un texto. No se aplica herencia. Lectura/escritura[`TextStrikethroughType`](../textstrikethroughtype) . |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Devuelve o establece la fuente simbólica info. Nulo significa que la fuente no está definida y debe heredarse del Maestro. Lectura/escritura[`IFontData`](../ifontdata) . |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Devuelve o establece el tipo de mayúsculas y minúsculas del texto. No se aplica herencia. Lectura/escritura[`TextCapType`](../textcaptype) . |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Devuelve las propiedades de FillFormat de la línea subrayada. Sin herencia aplicada. Solo lectura[`IFillFormat`](../ifillformat) . |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Devuelve las propiedades de LineFormat utilizadas para delinear la línea de subrayado. Sin herencia aplicada. Solo lectura[`ILineFormat`](../ilineformat) . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compara con el objeto especificado. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Obtiene datos de formato de porción efectivo con la herencia aplicada. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Devuelve el código hash. |

### Observaciones

Esta clase se usa para devolver y manipular las propiedades de formato de la porción de texto definidas para la porción en particular. Esto significa que no se aplica herencia al obtener valores, por lo que en la mayoría de los casos obtendrá valores que significan "indefinido".

Para obtener los valores de parámetros de formato efectivos, incluidos los heredados, debe usar[`GetEffective`](./geteffective) método que devuelve un[`IPortionFormatEffectiveData`](../iportionformateffectivedata) instancia.

### Ver también

* class [BasePortionFormat](../baseportionformat)
* interface [IPortionFormat](../iportionformat)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
