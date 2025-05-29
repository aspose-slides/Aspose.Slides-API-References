---
title: ChartPortionFormat
second_title: Referencia de API de Aspose.Slides para .NET
description: Esta clase contiene las propiedades de formato de porciones de gráfico utilizadas en gráficos. A diferencia de IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata, todas las propiedades de esta clase son escribibles.
type: docs
weight: 1350
url: /es/aspose.slides.charts/chartportionformat/
---

## Clase ChartPortionFormat

Esta clase contiene las propiedades de formato de porciones de gráfico utilizadas en gráficos. A diferencia de [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata), todas las propiedades de esta clase son escribibles.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Devuelve o establece el Id de un idioma alternativo. Cadena de lectura/escritura. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obtener la interfaz base IPresentationComponent. Solo lectura [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Devuelve o establece la información de la fuente de script complejo. Nulo significa que la fuente no está definida y debe heredarse del maestro. Lectura/escritura [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Devuelve o establece la información de la fuente de Asia Oriental. Nulo significa que la fuente no está definida y debe heredarse del maestro. Lectura/escritura [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Devuelve las propiedades de EffectFormat del texto. No se aplica la herencia. Solo lectura [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Devuelve o establece el texto superíndice o subíndice. Valor de -100% (subíndice) a 100% (superíndice). **float.NaN** significa que el valor no está definido y debe heredarse del maestro. Lectura/escritura Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Devuelve las propiedades de FillFormat del texto. No se aplica la herencia. Solo lectura [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Determina si la fuente es negrita. No se aplica la herencia. Lectura/escritura [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Devuelve o establece la altura de la fuente de una porción. **float.NaN** significa que la altura no está definida y debe heredarse del maestro. Lectura/escritura Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Determina si la fuente está en cursiva. No se aplica la herencia. Lectura/escritura [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Devuelve o establece el tipo de subrayado del texto. No se aplica la herencia. Lectura/escritura [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Devuelve el color utilizado para resaltar un texto. No se aplica la herencia. Solo lectura [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Determina si el estilo de subrayado tiene sus propias propiedades de FillFormat o las hereda de las propiedades de FillFormat del texto. Lectura/escritura [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Determina si el estilo de subrayado tiene sus propias propiedades de LineFormat o las hereda de las propiedades de LineFormat del texto. Lectura/escritura [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Devuelve o establece el tamaño mínimo de la fuente, para el cual se debe activar el kerning. **float.NaN** significa que el valor no está definido y debe heredarse del maestro. Lectura/escritura Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Determina si los números deben ignorar la disposición de texto vertical específica del idioma oriental. No se aplica la herencia. Lectura/escritura [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Devuelve o establece el Id de un idioma de prueba. Utilizado para verificar la ortografía y la gramática. Lectura/escritura Cadena. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Devuelve o establece la información de la fuente latina. Nulo significa que la fuente no está definida y debe heredarse del maestro. Lectura/escritura [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Devuelve las propiedades de LineFormat para el contorno del texto. No se aplica la herencia. Solo lectura [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Determina si la altura de un texto debe ser normalizada. No se aplica la herencia. Lectura/escritura [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Determina si el texto no debe ser probado. No se aplica la herencia. Lectura/escritura [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Devuelve o establece el incremento del espaciado entre caracteres. **float.NaN** significa que el valor no está definido y debe heredarse del maestro. Lectura/escritura Single. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Devuelve o establece el tipo de tachado de un texto. No se aplica la herencia. Lectura/escritura [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Devuelve o establece la información de la fuente simbólica. Nulo significa que la fuente no está definida y debe heredarse del maestro. Lectura/escritura [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Devuelve o establece el tipo de capitalización del texto. No se aplica la herencia. Lectura/escritura [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Devuelve las propiedades de FillFormat de la línea de subrayado. No se aplica la herencia. Solo lectura [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Devuelve las propiedades de LineFormat utilizadas para contornear la línea de subrayado. No se aplica la herencia. Solo lectura [`ILineFormat`](../../aspose.slides/ilineformat). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compara con el objeto especificado. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Devuelve el código hash. |

### Comentarios

Esta clase se utiliza para devolver y manipular las propiedades de formato de porciones de texto definidas para una porción particular. Esto significa que no se aplica la herencia al obtener valores, así que para la mayoría de los casos obtendrá valores que significan "no definido".

Para obtener los valores de parámetros de formato efectivo, incluidos los heredados, necesita utilizar el método [`GetEffective`](../../aspose.slides/portionformat/geteffective), que devuelve una instancia de [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata).

### Véase También

* clase [BasePortionFormat](../../aspose.slides/baseportionformat)
* interfaz [IChartPortionFormat](../ichartportionformat)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)