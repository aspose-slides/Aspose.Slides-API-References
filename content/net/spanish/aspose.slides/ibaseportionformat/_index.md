---
title: IBasePortionFormat
second_title: Referencia de la API de Aspose.Slides para .NET
description: Esta clase contiene las propiedades de formato de la porción de texto. A diferencia de IPortionFormatEffectiveData, todas las propiedades de esta clase son escribibles.
type: docs
weight: 5110
url: /es/aspose.slides/ibaseportionformat/
---

## Interfaz IBasePortionFormat

Esta clase contiene las propiedades de formato de la porción de texto. A diferencia de [`IPortionFormatEffectiveData`](../iportionformateffectivedata), todas las propiedades de esta clase son escribibles.

```csharp
public interface IBasePortionFormat
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Devuelve o establece el Id de un idioma alternativo. Lectura/escritura String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Devuelve o establece la información de la fuente de script complejo. Null significa que la fuente no está definida y debería heredarse del Master. Lectura/escritura [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Devuelve o establece la información de la fuente Este Asiático. Null significa que la fuente no está definida y debería heredarse del Master. Lectura/escritura [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Devuelve las propiedades de formato de efecto de texto. No se aplica herencia. Solo lectura [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Devuelve o establece el texto en superíndice o subíndice. Valor de -100% (subíndice) a 100% (superíndice). **float.NaN** significa que el valor no está definido y debería heredarse del Master. Lectura/escritura Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Devuelve las propiedades de formato de relleno de texto. No se aplica herencia. Solo lectura [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Determina si la fuente es en negrita. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Devuelve o establece la altura de la fuente de una porción. **float.NaN** significa que la altura no está definida y debería heredarse del Master. Lectura/escritura Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Determina si la fuente es en cursiva. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Devuelve o establece el tipo de subrayado de texto. No se aplica herencia. Lectura/escritura [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Devuelve el color utilizado para resaltar un texto. No se aplica herencia. Solo lectura [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Determina si el estilo de subrayado tiene sus propias propiedades de FillFormat o las hereda de las propiedades de FillFormat del texto. Lectura/escritura [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Determina si el estilo de subrayado tiene sus propias propiedades de LineFormat o las hereda de las propiedades de LineFormat del texto. Lectura/escritura [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Devuelve o establece el tamaño mínimo de fuente, para el cual el espaciado de caracteres debería estar activado. **float.NaN** significa que el valor no está definido y debería heredarse del Master. Lectura/escritura Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Determina si los números deberían ignorar el diseño de texto vertical específico del idioma oriental. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Devuelve o establece el Id de un idioma de prueba. Utilizado para la verificación de ortografía y gramática. Lectura/escritura String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Devuelve o establece la información de la fuente latina. Null significa que la fuente no está definida y debería heredarse del Master. Lectura/escritura [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Devuelve las propiedades de LineFormat para el contorno del texto. No se aplica herencia. Solo lectura [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Determina si la altura de un texto debería ser normalizada. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Determina si el texto no debería ser probado. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Devuelve o establece el incremento de espaciado entre caracteres. **float.NaN** significa que el valor no está definido y debería heredarse del Master. Lectura/escritura Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Devuelve o establece el tipo de tachado de un texto. No se aplica herencia. Lectura/escritura [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Devuelve o establece la información de la fuente simbólica. Null significa que la fuente no está definida y debería heredarse del Master. Lectura/escritura [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Devuelve o establece el tipo de capitalización de texto. No se aplica herencia. Lectura/escritura [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Devuelve las propiedades de FillFormat de la línea de subrayado. No se aplica herencia. Solo lectura [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Devuelve las propiedades de LineFormat utilizadas para delinear la línea de subrayado. No se aplica herencia. Solo lectura [`ILineFormat`](../ilineformat). |

### Observaciones

Esta clase se utiliza para devolver y manipular las propiedades de formato de porción de texto definidas para la porción particular. Esto significa que no se aplica herencia al obtener valores, por lo que en la mayoría de los casos obtendrá valores que significan "no definido".

Para obtener los valores de parámetros de formato efectivos, incluyendo los heredados, debe utilizar el método [`GetEffective`](../iportionformat/geteffective) que devuelve una instancia de [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Véase también

* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->