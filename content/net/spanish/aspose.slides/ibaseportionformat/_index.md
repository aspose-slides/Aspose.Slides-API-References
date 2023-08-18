---
title: IBasePortionFormat
second_title: Referencia de la API de Aspose.Slides para .NET
description: Esta clase contiene las propiedades de formato de la parte de texto. A diferencia deIPortionFormatEffectiveData./iportionformateffectivedata  todas las propiedades de esta clase se pueden escribir.
type: docs
weight: 4830
url: /es/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat interface

Esta clase contiene las propiedades de formato de la parte de texto. A diferencia de[`IPortionFormatEffectiveData`](../iportionformateffectivedata) , todas las propiedades de esta clase se pueden escribir.

```csharp
public interface IBasePortionFormat
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Devuelve o establece el Id de un idioma alternativo. Lectura/escrituraString . |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Devuelve o establece la información de la fuente de secuencia de comandos compleja. Nulo significa que la fuente no está definida y debe heredarse del Maestro. Lectura/escritura[`IFontData`](../ifontdata) . |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Devuelve o establece la información de la fuente de Asia oriental. Nulo significa que la fuente no está definida y debe heredarse del Maestro. Lectura/escritura[`IFontData`](../ifontdata) . |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Devuelve las propiedades de EffectFormat del texto. Sin herencia aplicada. Solo lectura[`IEffectFormat`](../ieffectformat) . |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Devuelve o establece el texto en superíndice o subíndice. Valor de -100% (subíndice) a 100% (superíndice).  **float.NaN** significa que el valor no está definido y debe heredarse del Maestro. Lectura/escrituraSingle . |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Devuelve las propiedades del formato de relleno del texto. Sin herencia aplicada. Solo lectura[`IFillFormat`](../ifillformat) . |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Determina si la fuente está en negrita. No se aplica herencia. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Devuelve o establece la altura de fuente de una porción.  **float.NaN** significa que la altura no está definida y debe heredarse del Maestro. Lectura/escrituraSingle . |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Determina si la fuente es cursiva. No se aplica herencia. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Devuelve o establece el tipo de subrayado del texto. No se aplica herencia. Lectura/escritura[`TextUnderlineType`](../textunderlinetype) . |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Devuelve el color utilizado para resaltar un texto. Sin herencia aplicada. Solo lectura[`IColorFormat`](../icolorformat) . |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Determina si el estilo de subrayado tiene propiedades propias de FillFormat o las hereda de las propiedades de FillFormat del texto. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Determina si el estilo de subrayado tiene propiedades LineFormat propias o las hereda de las propiedades LineFormat del texto. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Devuelve o establece el tamaño de fuente mínimo, para el cual se debe activar el interletraje.  **float.NaN** significa que el valor no está definido y debe heredarse del Maestro. Lectura/escrituraSingle . |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Determina si los números deben ignorar el diseño de texto vertical específico del idioma oriental. No se aplica herencia. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Devuelve o establece el Id de un idioma de revisión. Se utiliza para revisar la ortografía y la gramática. Lectura/escrituraString . |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Devuelve o establece la fuente latina info. Nulo significa que la fuente no está definida y debe heredarse del Maestro. Lectura/escritura[`IFontData`](../ifontdata) . |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Devuelve las propiedades de LineFormat para el esquema de texto. Sin herencia aplicada. Solo lectura[`ILineFormat`](../ilineformat) . |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Determina si se debe normalizar la altura de un texto. No se aplica herencia. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Determina si el texto no debe revisarse. No se aplica herencia. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Devuelve o establece el incremento de espaciado entre caracteres.  **float.NaN** significa que el valor no está definido y debe heredarse del Maestro. Lectura/escrituraSingle . |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Devuelve o establece el tipo de tachado de un texto. No se aplica herencia. Lectura/escritura[`TextStrikethroughType`](../textstrikethroughtype) . |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Devuelve o establece la fuente simbólica info. Nulo significa que la fuente no está definida y debe heredarse del Maestro. Lectura/escritura[`IFontData`](../ifontdata) . |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Devuelve o establece el tipo de mayúsculas y minúsculas del texto. No se aplica herencia. Lectura/escritura[`TextCapType`](../textcaptype) . |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Devuelve las propiedades de FillFormat de la línea subrayada. Sin herencia aplicada. Solo lectura[`IFillFormat`](../ifillformat) . |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Devuelve las propiedades de LineFormat utilizadas para delinear la línea de subrayado. Sin herencia aplicada. Solo lectura[`ILineFormat`](../ilineformat) . |

### Observaciones

Esta clase se usa para devolver y manipular las propiedades de formato de la porción de texto definidas para la porción en particular. Esto significa que no se aplica herencia al obtener valores, por lo que en la mayoría de los casos obtendrá valores que significan "indefinido".

Para obtener los valores de parámetros de formato efectivos, incluidos los heredados, debe usar[`GetEffective`](../iportionformat/geteffective) método que devuelve un[`IPortionFormatEffectiveData`](../iportionformateffectivedata) instancia.

### Ver también

* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
