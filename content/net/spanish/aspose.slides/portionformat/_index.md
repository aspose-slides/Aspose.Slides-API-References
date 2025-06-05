---
title: PortionFormat
second_title: Referencia de API de Aspose.Slides para .NET
description: Esta clase contiene las propiedades de formato de porciones de texto. A diferencia de IPortionFormatEffectiveData, todas las propiedades de esta clase son modificables.
type: docs
weight: 9220
url: /es/aspose.slides/portionformat/
---

## Clase PortionFormat

Esta clase contiene las propiedades de formato de porciones de texto. A diferencia de [`IPortionFormatEffectiveData`](../iportionformateffectivedata), todas las propiedades de esta clase son modificables.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PortionFormat](portionformat)() | Inicializa una nueva instancia de la clase [`PortionFormat`](../portionformat). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Devuelve o establece el Id de un idioma alternativo. Cadena de lectura/escritura. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obtener la interfaz base IPresentationComponent. Solo lectura [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Devuelve o establece el identificador del marcador. Cadena de lectura/escritura. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Devuelve o establece la información de la fuente de escritura compleja. Null significa que la fuente no está definida y debe heredarse del Maestro. Lectura/escritura [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Devuelve o establece la información de la fuente de Asia Oriental. Null significa que la fuente no está definida y debe heredarse del Maestro. Lectura/escritura [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Devuelve las propiedades de EffectFormat del texto. No se aplica la herencia. Solo lectura [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Devuelve o establece el texto en superíndice o subíndice. Valor de -100% (subíndice) a 100% (superíndice). **float.NaN** significa que el valor no está definido y debe heredarse del Maestro. Lectura/escritura Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Devuelve las propiedades de FillFormat del texto. No se aplica la herencia. Solo lectura [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Determina si la fuente es negrita. No se aplica la herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Devuelve o establece la altura de la fuente de una porción. **float.NaN** significa que la altura no está definida y debe heredarse del Maestro. Lectura/escritura Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Determina si la fuente es cursiva. No se aplica la herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Devuelve o establece el tipo de subrayado del texto. No se aplica la herencia. Lectura/escritura [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Devuelve el color utilizado para resaltar un texto. No se aplica la herencia. Solo lectura [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Devuelve o establece el hipervínculo definido para el clic del mouse. Lectura/escritura [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Gestor de hipervínculos. Solo lectura [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Devuelve o establece el hipervínculo definido para el puntero del mouse. Lectura/escritura [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Determina si el estilo de subrayado tiene sus propias propiedades de FillFormat o las hereda de las propiedades de FillFormat del texto. Lectura/escritura [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Determina si el estilo de subrayado tiene sus propias propiedades de LineFormat o las hereda de las propiedades de LineFormat del texto. Lectura/escritura [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Devuelve o establece el tamaño mínimo de la fuente, para el cual debe activarse el kerning. **float.NaN** significa que el valor no está definido y debe heredarse del Maestro. Lectura/escritura Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Determina si los números deben ignorar la disposición de texto vertical específica del idioma oriental. No se aplica la herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Devuelve o establece el Id de un idioma de revisión. Utilizado para verificar la ortografía y la gramática. Cadena de lectura/escritura. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Devuelve o establece la información de la fuente latina. Null significa que la fuente no está definida y debe heredarse del Maestro. Lectura/escritura [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Devuelve las propiedades de LineFormat para el contorno del texto. No se aplica la herencia. Solo lectura [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Determina si la altura de un texto debe normalizarse. No se aplica la herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Determina si el texto no debe ser revisado. No se aplica la herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Determina si la etiqueta inteligente debe ser limpiada. No se aplica la herencia. Lectura/escritura Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Devuelve o establece el incremento de espaciado entre caracteres. **float.NaN** significa que el valor no está definido y debe heredarse del Maestro. Lectura/escritura Single. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Devuelve o establece el tipo de tachado de un texto. No se aplica la herencia. Lectura/escritura [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Devuelve o establece la información de la fuente simbólica. Null significa que la fuente no está definida y debe heredarse del Maestro. Lectura/escritura [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Devuelve o establece el tipo de capitalización del texto. No se aplica la herencia. Lectura/escritura [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Devuelve las propiedades de FillFormat de la línea de subrayado. No se aplica la herencia. Solo lectura [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Devuelve las propiedades de LineFormat utilizadas para contornear la línea de subrayado. No se aplica la herencia. Solo lectura [`ILineFormat`](../ilineformat). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compara con el objeto especificado. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Obtiene los datos de formato de porción efectivos con la herencia aplicada. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Devuelve el código hash. |

### Observaciones

Esta clase se utiliza para devolver y manipular las propiedades de formato de porciones de texto definidas para una porción particular. Esto significa que no se aplica la herencia al obtener valores, por lo que en la mayoría de los casos obtendrá valores que significan "no definido".

Para obtener los valores de los parámetros de formato efectivos, incluidos los heredados, necesita usar el método [`GetEffective`](./geteffective) que devuelve una instancia de [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Ejemplos

Los siguientes ejemplos muestran cómo asignar la fuente latina a una porción de un párrafo de una presentación de PowerPoint.

```csharp
[C#]
//Instanciar un objeto de presentación que representa un archivo de presentación
using (Presentation pres = new Presentation("demo.pptx"))
{
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
    Paragraph paragraph = new Paragraph();
    Portion portion = new Portion("Formato de texto del tema");
    paragraph.Portions.Add(portion);
    shape.TextFrame.Paragraphs.Add(paragraph);
    // Aspose.Slides utiliza estos identificadores especiales (similares a los utilizados en PowerPoint):
    // +mn-lt - Fuente del cuerpo latina (Fuente menor latina)
    // +mj-lt - Fuente de encabezado latina (Fuente mayor latina)
    // +mn-ea - Fuente del cuerpo de Asia oriental (Fuente menor de Asia oriental)
    // +mj-ea - Fuente del cuerpo de Asia oriental (Fuente mayor de Asia oriental)
    portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Ver También

* clase [BasePortionFormat](../baseportionformat)
* interfaz [IPortionFormat](../iportionformat)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblaje [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->