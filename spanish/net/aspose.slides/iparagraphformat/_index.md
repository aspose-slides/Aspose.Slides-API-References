---
title: IParagraphFormat
second_title: Referencia de la API de Aspose.Slides para .NET
description: Esta clase contiene las propiedades de formato de párrafo. A diferencia deIParagraphFormatEffectiveData./iparagraphformateffectivedata  todas las propiedades de esta clase se pueden escribir.
type: docs
weight: 6030
url: /es/net/aspose.slides/iparagraphformat/
---
## IParagraphFormat interface

Esta clase contiene las propiedades de formato de párrafo. A diferencia de[`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) , todas las propiedades de esta clase se pueden escribir.

```csharp
public interface IParagraphFormat
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Devuelve o establece la alineación del texto en un párrafo sin herencia. Lectura/escritura[`TextAlignment`](../textalignment) . |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Devuelve el formato de viñeta del párrafo. Solo lectura[`IBulletFormat`](../ibulletformat) . |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Devuelve el formato de parte predeterminado de un párrafo. Sin herencia aplicada. Solo lectura[`IPortionFormat`](../iportionformat) . |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Devuelve o establece el tamaño de tabulación predeterminado sin herencia. Lectura/escrituraSingle . |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Devuelve o establece la profundidad del párrafo. Valor 0 significa valor indefinido. Lectura/escrituraInt16 . |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Determina si se utiliza el salto de línea de Asia oriental en un párrafo. No se aplica herencia. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Devuelve o establece una alineación de fuente en un párrafo sin herencia. Lectura/escritura[`FontAlignment`](../fontalignment) . |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Determina si se utiliza la puntuación colgante en un párrafo. No se aplica herencia. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Devuelve o establece la sangría de primera línea o la sangría francesa del párrafo sin herencia. La sangría francesa se puede definir con valores negativos. Lectura/escrituraSingle . |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Determina si se utiliza el salto de línea latino en un párrafo. No se aplica herencia. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Devuelve o establece el margen izquierdo en un párrafo sin herencia. Lectura/escrituraSingle . |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Devuelve o establece el margen derecho en un párrafo sin herencia. Lectura/escrituraSingle . |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Determina si se utiliza la escritura de derecha a izquierda en un párrafo. No se aplica herencia. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Devuelve o establece la cantidad de espacio después de la última línea de un párrafo sin herencia. Un valor positivo especifica el porcentaje del tamaño de fuente que debe tener el espacio en blanco. Un valor negativo especifica el tamaño del espacio en blanco en el punto tamaño. Lectura/escrituraSingle . |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Devuelve o establece la cantidad de espacio antes de la primera línea de un párrafo sin herencia. Un valor positivo especifica el porcentaje del tamaño de fuente que debe tener el espacio en blanco. Un valor negativo especifica el tamaño del espacio en blanco en el punto tamaño. Lectura/escrituraSingle . |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Devuelve o establece la cantidad de espacio entre líneas base en un párrafo. Valor positivo significa porcentaje, negativo - tamaño en puntos. No se aplica herencia. Lectura/escrituraSingle . |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Devuelve las tabulaciones de un párrafo. Sin herencia aplicada. Solo lectura[`ITabCollection`](../itabcollection) . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Obtiene datos de formato de párrafo efectivo con la herencia aplicada. |

### Observaciones

Esta clase se utiliza para devolver y manipular las propiedades de formato de párrafo definidas para el párrafo en particular. Esto significa que no se aplica herencia al obtener valores, por lo que en la mayoría de los casos obtendrá valores que significan "indefinido".

Para obtener los valores de parámetros de formato efectivos, incluidos los heredados, debe usar[`GetEffective`](./geteffective) método que devuelve un[`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) instancia.

### Ver también

* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
