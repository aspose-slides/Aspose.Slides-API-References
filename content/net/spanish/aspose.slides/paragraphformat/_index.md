---
title: ParagraphFormat
second_title: Referencia de API de Aspose.Sildes para .NET
description: Esta clase contiene las propiedades de formato de párrafo. A diferencia de IParagraphFormatEffectiveData./iparagraphformateffectivedata, todas las propiedades de esta clase son escribibles.
type: docs
weight: 9310
url: /es/aspose.slides/paragraphformat/
---
## Clase ParagraphFormat

Esta clase contiene las propiedades de formato de párrafo. A diferencia de [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), todas las propiedades de esta clase son escribibles.

```csharp
public sealed class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Inicializa una nueva instancia de la clase [`ParagraphFormat`](../paragraphformat). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Devuelve o establece la alineación del texto en un párrafo sin herencia. Lectura/escritura [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obtener la interfaz base IPresentationComponent. Solo lectura [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Devuelve o establece el tamaño de tabulación predeterminado sin herencia. Lectura/escritura Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Determina si se utiliza el salto de línea de Asia Oriental en un párrafo. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Devuelve o establece una alineación de fuente en un párrafo sin herencia. Lectura/escritura [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Determina si se utiliza la puntuación colgante en un párrafo. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Devuelve o establece la sangría de primera línea/sangría colgante del párrafo sin herencia. La sangría colgante puede definirse con valores negativos. Lectura/escritura Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Determina si se utiliza el salto de línea latino en un párrafo. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Devuelve o establece el margen izquierdo en un párrafo sin herencia. Lectura/escritura Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Devuelve o establece el margen derecho en un párrafo sin herencia. Lectura/escritura Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Determina si se utiliza la escritura de derecha a izquierda en un párrafo. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Devuelve o establece la cantidad de espacio después de la última línea en un párrafo sin herencia. Un valor positivo especifica el porcentaje del tamaño de fuente que debe tener el espacio en blanco. Un valor negativo especifica el tamaño del espacio en blanco en puntos. Lectura/escritura Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Devuelve o establece la cantidad de espacio antes de la primera línea en un párrafo sin herencia. Un valor positivo especifica el porcentaje del tamaño de fuente que debe tener el espacio en blanco. Un valor negativo especifica el tamaño del espacio en blanco en puntos. Lectura/escritura Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Devuelve o establece la cantidad de espacio entre líneas base en un párrafo. Un valor positivo significa porcentaje, negativo – tamaño en puntos. No se aplica herencia. Lectura/escritura Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Devuelve las tabulaciones de un párrafo. No se aplica herencia. Solo lectura [`ITabCollection`](../itabcollection). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compara con el objeto especificado. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Obtiene los datos de formato de párrafo efectivos con la herencia aplicada. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Devuelve el código hash. |

### Comentarios

Esta clase se usa para devolver y manipular las propiedades de formato de párrafo definidas para el párrafo concreto. Esto significa que no se aplica herencia al obtener los valores, por lo que en la mayoría de los casos obtendrá valores que significan “indefinido”.

Para obtener los valores efectivos de los parámetros de formato, incluidos los heredados, necesita usar el método [`GetEffective`](./geteffective) que devuelve una instancia de [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Ver también

* clase [PVIObject](../pviobject)
* interfaz [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* interfaz [IParagraphFormat](../iparagraphformat)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->