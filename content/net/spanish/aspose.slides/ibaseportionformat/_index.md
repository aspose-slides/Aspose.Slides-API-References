---
title: IBasePortionFormat
second_title: Referencia de API de Aspose.Slides para .NET
description: Esta clase contiene las propiedades de formato de porciones de texto. A diferencia de IPortionFormatEffectiveData./iportionformateffectivedata, todas las propiedades de esta clase son editables.
type: docs
weight: 5110
url: /es/aspose.slides/ibaseportionformat/
---

## Interfaz IBasePortionFormat

Esta clase contiene las propiedades de formato de porciones de texto. A diferencia de [`IPortionFormatEffectiveData`](../iportionformateffectivedata), todas las propiedades de esta clase son editables.

```csharp
public interface IBasePortionFormat
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Devuelve o establece el Id de un idioma alternativo. Cadena de lectura/escritura. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Devuelve o establece la información de la fuente de escritura compleja. Null significa que la fuente no está definida y debe heredarse del Maestro. Lectura/escritura [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Devuelve o establece la información de la fuente de este asiático. Null significa que la fuente no está definida y debe heredarse del Maestro. Lectura/escritura [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Devuelve las propiedades de formato de efecto de texto. No se aplica herencia. Solo lectura [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Devuelve o establece el texto en superíndice o subíndice. Valor de -100% (subíndice) a 100% (superíndice). **float.NaN** significa que el valor no está definido y debe heredarse del Maestro. Lectura/escritura Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Devuelve las propiedades de formato de relleno de texto. No se aplica herencia. Solo lectura [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Determina si la fuente es negrita. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Devuelve o establece la altura de la fuente de una porción. **float.NaN** significa que la altura no está definida y debe heredarse del Maestro. Lectura/escritura Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Determina si la fuente es cursiva. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Devuelve o establece el tipo de subrayado del texto. No se aplica herencia. Lectura/escritura [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Devuelve el color utilizado para resaltar un texto. No se aplica herencia. Solo lectura [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Determina si el estilo de subrayado tiene sus propias propiedades de formato de relleno o las hereda de las propiedades de formato de relleno del texto. Lectura/escritura [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Determina si el estilo de subrayado tiene sus propias propiedades de formato de línea o las hereda de las propiedades de formato de línea del texto. Lectura/escritura [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Devuelve o establece el tamaño mínimo de fuente, para el cual se debe activar el ajuste de distancia. **float.NaN** significa que el valor no está definido y debe heredarse del Maestro. Lectura/escritura Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Determina si los números deben ignorar el diseño de texto vertical específico del idioma oriental. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Devuelve o establece el Id de un idioma de revisión. Usado para comprobar la ortografía y la gramática. Cadena de lectura/escritura. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Devuelve o establece la información de la fuente latina. Null significa que la fuente no está definida y debe heredarse del Maestro. Lectura/escritura [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Devuelve las propiedades de LineFormat para el contorno del texto. No se aplica herencia. Solo lectura [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Determina si la altura de un texto debe ser normalizada. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Determina si el texto no debe ser revisado. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Devuelve o establece el incremento del espaciado entre caracteres. **float.NaN** significa que el valor no está definido y debe heredarse del Maestro. Lectura/escritura Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Devuelve o establece el tipo de tachado de un texto. No se aplica herencia. Lectura/escritura [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Devuelve o establece la información de la fuente simbólica. Null significa que la fuente no está definida y debe heredarse del Maestro. Lectura/escritura [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Devuelve o establece el tipo de capitalización de texto. No se aplica herencia. Lectura/escritura [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Devuelve las propiedades de formato de relleno de la línea de subrayado. No se aplica herencia. Solo lectura [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Devuelve las propiedades de LineFormat utilizadas para contornear la línea de subrayado. No se aplica herencia. Solo lectura [`ILineFormat`](../ilineformat). |

### Observaciones

Esta clase se utiliza para devolver y manipular las propiedades de formato de porciones de texto definidas para la porción particular. Esto significa que no se aplica herencia al obtener valores, por lo que en la mayoría de los casos se obtendrán valores que significan "no definido".

Para obtener los valores de los parámetros de formato efectivos, incluidos los heredados, debe utilizar el método [`GetEffective`](../iportionformat/geteffective), que devuelve una instancia de [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Ver También

* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->