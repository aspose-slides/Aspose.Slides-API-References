---
title: PortionFormat
second_title: Referencia de API Aspose.Sildes para .NET
description: Esta clase contiene las propiedades de formato de la porción de texto. A diferencia de IPortionFormatEffectiveData./iportionformateffectivedata, todas las propiedades de esta clase son editables.
type: docs
weight: 9510
url: /es/aspose.slides/portionformat/
---
## PortionFormat clase

Esta clase contiene las propiedades de formato de la porción de texto. A diferencia de [`IPortionFormatEffectiveData`](../iportionformateffectivedata), todas las propiedades de esta clase son editables.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## Constructores

| Name | Description |
| --- | --- |
| [PortionFormat](portionformat)() | Inicializa una nueva instancia de la clase [`PortionFormat`](../portionformat). |

## Propiedades

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Devuelve o establece el Id de un idioma alternativo. Lectura/Escritura String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obtener la interfaz base IPresentationComponent. Solo lectura [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Devuelve o establece el identificador del marcador. Lectura/Escritura String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Devuelve o establece la información de la fuente de script complejo. Null significa que la fuente no está definida y debe heredarse del Master. Lectura/Escritura [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Devuelve o establece la información de la fuente de Asia Oriental. Null significa que la fuente no está definida y debe heredarse del Master. Lectura/Escritura [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Devuelve las propiedades de texto EffectFormat. No se aplica herencia. Solo lectura [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Devuelve o establece el texto de superíndice o subíndice. Valor de -100% (subíndice) a 100% (superíndice). **float.NaN** significa que el valor no está definido y debe heredarse del Master. Lectura/Escritura Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Devuelve las propiedades de texto FillFormat. No se aplica herencia. Solo lectura [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Determina si la fuente está en negrita. No se aplica herencia. Lectura/Escritura [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Devuelve o establece la altura de fuente de una porción. **float.NaN** significa que la altura no está definida y debe heredarse del Master. Lectura/Escritura Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Determina si la fuente está en cursiva. No se aplica herencia. Lectura/Escritura [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Devuelve o establece el tipo de subrayado del texto. No se aplica herencia. Lectura/Escritura [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Devuelve el color usado para resaltar un texto. No se aplica herencia. Solo lectura [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Devuelve o establece el hipervínculo definido para clic del ratón. Lectura/Escritura [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Administrador de hipervínculos. Solo lectura [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Devuelve o establece el hipervínculo definido para pasar el ratón por encima. Lectura/Escritura [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Determina si el estilo de subrayado tiene sus propias propiedades FillFormat o las hereda de las propiedades FillFormat del texto. Lectura/Escritura [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Determina si el estilo de subrayado tiene sus propias propiedades LineFormat o las hereda de las propiedades LineFormat del texto. Lectura/Escritura [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Devuelve o establece el tamaño de fuente mínimo, para el cual debe activarse el kerning. **float.NaN** significa que el valor no está definido y debe heredarse del Master. Lectura/Escritura Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Determina si los números deben ignorar la disposición vertical del texto específica de idiomas orientales. No se aplica herencia. Lectura/Escritura [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Devuelve o establece el Id de un idioma de corrección. Se usa para comprobar la ortografía y la gramática. Lectura/Escritura String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Devuelve o establece la información de la fuente latina. Null significa que la fuente no está definida y debe heredarse del Master. Lectura/Escritura [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Devuelve las propiedades LineFormat para el contorno del texto. No se aplica herencia. Solo lectura [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Determina si la altura del texto debe normalizarse. No se aplica herencia. Lectura/Escritura [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Determina si el texto no debe ser corregido. No se aplica herencia. Lectura/Escritura [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Determina si la etiqueta inteligente debe limpiarse. No se aplica herencia. Lectura/Escritura Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Devuelve o establece el incremento de espaciado entre caracteres. **float.NaN** significa que el valor no está definido y debe heredarse del Master. Lectura/Escritura Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Obtiene o establece un valor que indica si la corrección ortográfica está habilitada para la porción de texto. Cuando esta propiedad se establece en false, se suprimen las verificaciones ortográficas para los elementos de texto. Cuando se establece en true, se permite la corrección ortográfica. El valor predeterminado es `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Devuelve o establece el tipo de tachado de un texto. No se aplica herencia. Lectura/Escritura [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Devuelve o establece la información de la fuente simbólica. Null significa que la fuente no está definida y debe heredarse del Master. Lectura/Escritura [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Devuelve o establece el tipo de capitalización del texto. No se aplica herencia. Lectura/Escritura [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Devuelve las propiedades FillFormat de la línea de subrayado. No se aplica herencia. Solo lectura [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Devuelve las propiedades LineFormat usadas para delinear la línea de subrayado. No se aplica herencia. Solo lectura [`ILineFormat`](../ilineformat). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compara con el objeto especificado. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Obtiene los datos de formato de porción efectivos con la herencia aplicada. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Devuelve el código hash. |

### Comentarios

Esta clase se usa para devolver y manipular las propiedades de formato de porción de texto definidas para la porción en particular. Esto significa que no se aplica herencia al obtener valores, por lo que en la mayoría de los casos obtendrá valores que significan "undefined".

Para obtener los valores de los parámetros de formato efectivos, incluidas las herencias, necesita usar el método [`GetEffective`](./geteffective) que devuelve una instancia de [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Ejemplos

El siguiente ejemplo muestra cómo asignar la fuente latina a la porción de un Paragraph de una presentación de PowerPoint.

```csharp
[C#]
//Instanciar un objeto Presentation que representa un archivo de presentación
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides usa estos identificadores especiales (similares a los usados en PowerPoint):
// +mn-lt - Fuente del cuerpo Latin (Fuente Latin menor)
// +mj-lt - Fuente del encabezado Latin (Fuente Latin mayor)
// +mn-ea - Fuente del cuerpo East Asian (Fuente East Asian menor)
// +mj-ea - Fuente del cuerpo East Asian (Fuente East Asian menor)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Véase también

* clase [BasePortionFormat](../baseportionformat)
* interfaz [IPortionFormat](../iportionformat)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->