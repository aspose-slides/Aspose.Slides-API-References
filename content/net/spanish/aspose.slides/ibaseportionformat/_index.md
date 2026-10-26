---
title: IBasePortionFormat
second_title: Referencia de API de Aspose.Sildes para .NET
description: Esta clase contiene las propiedades de formato de porción de texto. A diferencia de IPortionFormatEffectiveData./iportionformateffectivedata, todas las propiedades de esta clase son editables.
type: docs
weight: 5310
url: /es/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat interfaz

Esta clase contiene las propiedades de formato de porción de texto. A diferencia de [`IPortionFormatEffectiveData`](../iportionformateffectivedata), todas las propiedades de esta clase son editables.

```csharp
public interface IBasePortionFormat
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Devuelve o establece el Id de un idioma alternativo. Lectura/escritura String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Devuelve o establece la información de fuente para scripts complejos. Null significa que la fuente no está definida y debe heredarse del Maestro. Lectura/escritura [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Devuelve o establece la información de fuente para idiomas este-asiáticos. Null significa que la fuente no está definida y debe heredarse del Maestro. Lectura/escritura [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Devuelve las propiedades EffectFormat del texto. No se aplica herencia. Solo lectura [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Devuelve o establece el texto en super-índice o sub-índice. Valor entre -100 % (sub-índice) y 100 % (super-índice). **float.NaN** indica que el valor no está definido y debe heredarse del Maestro. Lectura/escritura Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Devuelve las propiedades FillFormat del texto. No se aplica herencia. Solo lectura [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Determina si la fuente es negrita. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Devuelve o establece la altura de la fuente de una porción. **float.NaN** indica que la altura no está definida y debe heredarse del Maestro. Lectura/escritura Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Determina si la fuente es cursiva. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Devuelve o establece el tipo de subrayado del texto. No se aplica herencia. Lectura/escritura [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Devuelve el color usado para resaltar texto. No se aplica herencia. Solo lectura [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Determina si el estilo de subrayado tiene sus propias propiedades FillFormat o las hereda de las propiedades FillFormat del texto. Lectura/escritura [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Determina si el estilo de subrayado tiene sus propias propiedades LineFormat o las hereda de las propiedades LineFormat del texto. Lectura/escritura [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Devuelve o establece el tamaño mínimo de fuente para el que se debe activar el kerning. **float.NaN** indica que el valor no está definido y debe heredarse del Maestro. Lectura/escritura Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Determina si los números deben ignorar la disposición vertical del texto específica de idiomas orientales. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Devuelve o establece el Id de un idioma de corrección. Se usa para comprobar ortografía y gramática. Lectura/escritura String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Devuelve o establece la información de fuente latina. Null significa que la fuente no está definida y debe heredarse del Maestro. Lectura/escritura [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Devuelve las propiedades LineFormat para el contorno del texto. No se aplica herencia. Solo lectura [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Determina si la altura del texto debe normalizarse. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Determina si el texto no debe revisarse. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Devuelve o establece el incremento de espaciado intercaracteres. **float.NaN** indica que el valor no está definido y debe heredarse del Maestro. Lectura/escritura Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | Obtiene o establece un valor que indica si la corrección ortográfica está habilitada para la porción de texto. Cuando esta propiedad se establece en false, se suprimen las comprobaciones ortográficas para los elementos de texto. Cuando se establece en true, se permite la corrección ortográfica. El valor predeterminado es `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Devuelve o establece el tipo de tachado del texto. No se aplica herencia. Lectura/escritura [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Devuelve o establece la información de fuente simbólica. Null significa que la fuente no está definida y debe heredarse del Maestro. Lectura/escritura [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Devuelve o establece el tipo de capitalización del texto. No se aplica herencia. Lectura/escritura [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Devuelve las propiedades FillFormat de la línea subrayada. No se aplica herencia. Solo lectura [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Devuelve las propiedades LineFormat usadas para delinear la línea subrayada. No se aplica herencia. Solo lectura [`ILineFormat`](../ilineformat). |

### Comentarios

Esta clase se utiliza para devolver y manipular las propiedades de formato de porción de texto definidas para la porción concreta. Esto significa que no se aplica herencia al obtener valores, por lo que en la mayoría de los casos obtendrá valores que significan “indefinido”.

Para obtener los valores efectivos de los parámetros de formato, incluidos los heredados, debe usar el método [`GetEffective`](../iportionformat/geteffective) que devuelve una instancia [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Ver también

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->