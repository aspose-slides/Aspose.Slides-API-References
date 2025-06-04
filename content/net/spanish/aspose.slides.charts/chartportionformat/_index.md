---
title: ChartPortionFormat
second_title: Aspose.Sildes for .NET API Reference
description: Esta clase contiene las propiedades de formato de porciones de gráficos utilizadas en gráficos. A diferencia de IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata, todas las propiedades de esta clase son escribibles.
type: docs
weight: 1350
url: /es/aspose.slides.charts/chartportionformat/
---

## ChartPortionFormat class

Esta clase contiene las propiedades de formato de porciones de gráficos utilizadas en gráficos. A diferencia de [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata), todas las propiedades de esta clase son escribibles.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Properties

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Devuelve o establece el Id de un idioma alternativo. Lectura/escritura String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obtener la interfaz base IPresentationComponent. Solo lectura [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Devuelve o establece la información de la fuente de script complejo. Null significa que la fuente está indefinida y debe heredarse del Master. Lectura/escritura [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Devuelve o establece la información de la fuente del Este Asiático. Null significa que la fuente está indefinida y debe heredarse del Master. Lectura/escritura [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Devuelve las propiedades de formato de efecto del texto. No se aplica herencia. Solo lectura [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Devuelve o establece el texto en superíndice o subíndice. Valor de -100 % (subíndice) a 100 % (superíndice). **float.NaN** significa que el valor está indefinido y debe heredarse del Master. Lectura/escritura Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Devuelve las propiedades de formato de relleno del texto. No se aplica herencia. Solo lectura [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Determina si la fuente es negrita. No se aplica herencia. Lectura/escritura [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Devuelve o establece la altura de la fuente de una porción. **float.NaN** significa que la altura está indefinida y debe heredarse del Master. Lectura/escritura Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Determina si la fuente es cursiva. No se aplica herencia. Lectura/escritura [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Devuelve o establece el tipo de subrayado del texto. No se aplica herencia. Lectura/escritura [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Devuelve el color utilizado para resaltar un texto. No se aplica herencia. Solo lectura [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Determina si el estilo de subrayado tiene sus propias propiedades de FillFormat o las hereda de las propiedades de FillFormat del texto. Lectura/escritura [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Determina si el estilo de subrayado tiene sus propias propiedades de LineFormat o las hereda de las propiedades de LineFormat del texto. Lectura/escritura [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Devuelve o establece el tamaño mínimo de fuente, para el cual debe activarse el kerning. **float.NaN** significa que el valor está indefinido y debe heredarse del Master. Lectura/escritura Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Determina si los números deben ignorar el diseño de texto vertical específico del idioma del Este. No se aplica herencia. Lectura/escritura [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Devuelve o establece el Id de un idioma de revisión. Se usa para verificar la ortografía y la gramática. Lectura/escritura String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Devuelve o establece la información de la fuente latina. Null significa que la fuente está indefinida y debe heredarse del Master. Lectura/escritura [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Devuelve las propiedades de LineFormat para el contorno del texto. No se aplica herencia. Solo lectura [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Determina si la altura de un texto debe normalizarse. No se aplica herencia. Lectura/escritura [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Determina si el texto no debe ser revisado. No se aplica herencia. Lectura/escritura [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Devuelve o establece el incremento de espaciado entre caracteres. **float.NaN** significa que el valor está indefinido y debe heredarse del Master. Lectura/escritura Single. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Devuelve o establece el tipo de tachado de un texto. No se aplica herencia. Lectura/escritura [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Devuelve o establece la información de la fuente simbólica. Null significa que la fuente está indefinida y debe heredarse del Master. Lectura/escritura [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Devuelve o establece el tipo de capitalización de texto. No se aplica herencia. Lectura/escritura [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Devuelve las propiedades de FillFormat de la línea de subrayado. No se aplica herencia. Solo lectura [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Devuelve las propiedades de LineFormat utilizadas para contornear la línea de subrayado. No se aplica herencia. Solo lectura [`ILineFormat`](../../aspose.slides/ilineformat). |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compara con el objeto especificado. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Devuelve el código hash. |

### Remarks

Esta clase se utiliza para devolver y manipular las propiedades de formato de porciones de texto definidas para la porción particular. Esto significa que no se aplica herencia al obtener valores, por lo que en la mayoría de los casos obtendrás valores que significan "indefinido".

Para obtener los valores de los parámetros de formato efectivos, incluidos los heredados, debes usar el método [`GetEffective`](../../aspose.slides/portionformat/geteffective), que devuelve una instancia de [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata).

### See Also

* class [BasePortionFormat](../../aspose.slides/baseportionformat)
* interface [IChartPortionFormat](../ichartportionformat)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->