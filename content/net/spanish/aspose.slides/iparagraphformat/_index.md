---
title: IParagraphFormat
second_title: Referencia de API de Aspose.Sildes para .NET
description: Esta clase contiene las propiedades de formato de párrafo. A diferencia de IParagraphFormatEffectiveData./iparagraphformateffectivedata, todas las propiedades de esta clase son escribibles.
type: docs
weight: 6590
url: /es/aspose.slides/iparagraphformat/
---
## IParagraphFormat interfaz

Esta clase contiene las propiedades de formato de párrafo. A diferencia de [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), todas las propiedades de esta clase son escribibles.

```csharp
public interface IParagraphFormat
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Devuelve o establece la alineación del texto en un párrafo sin herencia. Lectura/escritura [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Devuelve el formato de viñeta del párrafo. Solo lectura [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Devuelve el formato de porción predeterminado de un párrafo. No se aplica herencia. Solo lectura [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Devuelve o establece el tamaño de tabulación predeterminado sin herencia. Lectura/escritura Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Devuelve o establece la profundidad del párrafo. El valor 0 significa valor indefinido. Lectura/escritura Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Determina si se usa el salto de línea de Asia Oriental en un párrafo. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Devuelve o establece la alineación de fuente en un párrafo sin herencia. Lectura/escritura [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Determina si se usa la puntuación colgante en un párrafo. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Devuelve o establece la sangría de primera línea/sangría colgante del párrafo sin herencia. La sangría colgante puede definirse con valores negativos. Lectura/escritura Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Determina si se usa el salto de línea latino en un párrafo. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Devuelve o establece el margen izquierdo en un párrafo sin herencia. Lectura/escritura Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Devuelve o establece el margen derecho en un párrafo sin herencia. Lectura/escritura Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Determina si se usa la escritura de derecha a izquierda en un párrafo. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Devuelve o establece la cantidad de espacio después de la última línea en un párrafo sin herencia. Un valor positivo especifica el porcentaje del tamaño de fuente que debe tener el espacio en blanco. Un valor negativo especifica el tamaño del espacio en blanco en puntos. Lectura/escritura Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Devuelve o establece la cantidad de espacio antes de la primera línea en un párrafo sin herencia. Un valor positivo especifica el porcentaje del tamaño de fuente que debe tener el espacio en blanco. Un valor negativo especifica el tamaño del espacio en blanco en puntos. Lectura/escritura Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Devuelve o establece la cantidad de espacio entre líneas base en un párrafo. Un valor positivo significa porcentaje, negativo - tamaño en puntos. No se aplica herencia. Lectura/escritura Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Devuelve las tabulaciones de un párrafo. No se aplica herencia. Solo lectura [`ITabCollection`](../itabcollection). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Obtiene los datos de formato de párrafo efectivos con la herencia aplicada. |

### Observaciones

Esta clase se usa para devolver y manipular las propiedades de formato de párrafo definidas para el párrafo concreto. Esto significa que no se aplica herencia al obtener valores, por lo que en la mayoría de los casos se obtendrán valores que significan "indefinido".

Para obtener los valores efectivos de los parámetros de formato, incluyendo los heredados, debe usar el método [`GetEffective`](./geteffective) que devuelve una instancia de [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Ver también

* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->