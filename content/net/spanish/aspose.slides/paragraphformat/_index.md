---
title: ParagraphFormat
second_title: Referencia de la API de Aspose.Slides para .NET
description: Esta clase contiene las propiedades de formato de párrafo. A diferencia deIParagraphFormatEffectiveData./iparagraphformateffectivedata  todas las propiedades de esta clase se pueden escribir.
type: docs
weight: 8580
url: /es/aspose.slides/paragraphformat/
---
## ParagraphFormat class

Esta clase contiene las propiedades de formato de párrafo. A diferencia de[`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) , todas las propiedades de esta clase se pueden escribir.

```csharp
public class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Inicializa una nueva instancia de[`ParagraphFormat`](../paragraphformat) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Devuelve o establece la alineación del texto en un párrafo sin herencia. Lectura/escritura[`TextAlignment`](../textalignment) . |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obtener la interfaz base IPPresentationComponent. Solo lectura[`IPresentationComponent`](../ipresentationcomponent) . |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Devuelve o establece el tamaño de tabulación predeterminado sin herencia. Lectura/escrituraSingle . |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Determina si se utiliza el salto de línea de Asia oriental en un párrafo. No se aplica herencia. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Devuelve o establece una alineación de fuente en un párrafo sin herencia. Lectura/escritura[`FontAlignment`](../fontalignment) . |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Determina si se utiliza la puntuación colgante en un párrafo. No se aplica herencia. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Devuelve o establece la sangría de primera línea o la sangría francesa del párrafo sin herencia. La sangría francesa se puede definir con valores negativos. Lectura/escrituraSingle . |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Determina si se utiliza el salto de línea latino en un párrafo. No se aplica herencia. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Devuelve o establece el margen izquierdo en un párrafo sin herencia. Lectura/escrituraSingle . |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Devuelve o establece el margen derecho en un párrafo sin herencia. Lectura/escrituraSingle . |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Determina si se utiliza la escritura de derecha a izquierda en un párrafo. No se aplica herencia. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Devuelve o establece la cantidad de espacio después de la última línea de un párrafo sin herencia. Un valor positivo especifica el porcentaje del tamaño de fuente que debe tener el espacio en blanco. Un valor negativo especifica el tamaño del espacio en blanco en el punto tamaño. Lectura/escrituraSingle . |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Devuelve o establece la cantidad de espacio antes de la primera línea de un párrafo sin herencia. Un valor positivo especifica el porcentaje del tamaño de fuente que debe tener el espacio en blanco. Un valor negativo especifica el tamaño del espacio en blanco en el punto tamaño. Lectura/escrituraSingle . |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Devuelve o establece la cantidad de espacio entre líneas base en un párrafo. Valor positivo significa porcentaje, negativo - tamaño en puntos. No se aplica herencia. Lectura/escrituraSingle . |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Devuelve las tabulaciones de un párrafo. Sin herencia aplicada. Solo lectura[`ITabCollection`](../itabcollection) . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compara con el objeto especificado. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Obtiene datos de formato de párrafo efectivo con la herencia aplicada. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Devuelve el código hash. |

### Observaciones

Esta clase se utiliza para devolver y manipular las propiedades de formato de párrafo definidas para el párrafo en particular. Esto significa que no se aplica herencia al obtener valores, por lo que en la mayoría de los casos obtendrá valores que significan "indefinido".

Para obtener los valores de parámetros de formato efectivos, incluidos los heredados, debe usar[`GetEffective`](./geteffective) método que devuelve un[`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) instancia.

### Ver también

* class [PVIObject](../pviobject)
* interface [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* interface [IParagraphFormat](../iparagraphformat)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
