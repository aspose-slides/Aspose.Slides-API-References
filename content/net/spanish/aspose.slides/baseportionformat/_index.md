---
title: BasePortionFormat
second_title: Referencia de la API de Aspose.Slides para .NET
description: Propiedades comunes de formato de parte de texto.
type: docs
weight: 870
url: /es/aspose.slides/baseportionformat/
---
## BasePortionFormat class

Propiedades comunes de formato de parte de texto.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Devuelve o establece el Id de un idioma alternativo. Lectura/escrituraString . |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obtener la interfaz base IPPresentationComponent. Solo lectura[`IPresentationComponent`](../ipresentationcomponent) . |
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
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Determina si el estilo de subrayado tiene propiedades propias de FillFormat o las hereda de las propiedades de FillFormat del texto. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Determina si el estilo de subrayado tiene propiedades LineFormat propias o las hereda de las propiedades LineFormat del texto. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Devuelve o establece el tamaño de fuente mínimo, para el cual se debe activar el interletraje.  **float.NaN** significa que el valor no está definido y debe heredarse del Maestro. Lectura/escrituraSingle . |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Determina si los números deben ignorar el diseño de texto vertical específico del idioma oriental. No se aplica herencia. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Devuelve o establece el Id de un idioma de revisión. Se utiliza para revisar la ortografía y la gramática. Lectura/escrituraString . |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Devuelve o establece la fuente latina info. Nulo significa que la fuente no está definida y debe heredarse del Maestro. Lectura/escritura[`IFontData`](../ifontdata) . |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Devuelve las propiedades de LineFormat para el esquema de texto. Sin herencia aplicada. Solo lectura[`ILineFormat`](../ilineformat) . |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Determina si se debe normalizar la altura de un texto. No se aplica herencia. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Determina si el texto no debe revisarse. No se aplica herencia. Lectura/escritura[`NullableBool`](../nullablebool) . |
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
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Devuelve el código hash. |

### Ver también

* class [PVIObject](../pviobject)
* interface [IBasePortionFormat](../ibaseportionformat)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
