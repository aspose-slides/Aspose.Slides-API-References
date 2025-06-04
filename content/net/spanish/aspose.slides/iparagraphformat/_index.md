---
title: IParagraphFormat
second_title: Referencia de API de Aspose.Slides para .NET
description: Esta clase contiene las propiedades de formato de párrafo. A diferencia de IParagraphFormatEffectiveData./iparagraphformateffectivedata, todas las propiedades de esta clase son editables.
type: docs
weight: 6390
url: /es/aspose.slides/iparagraphformat/
---

## Interfaz IParagraphFormat

Esta clase contiene las propiedades de formato de párrafo. A diferencia de [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), todas las propiedades de esta clase son editables.

```csharp
public interface IParagraphFormat
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Devuelve o establece la alineación del texto en un párrafo sin herencia. Lectura/escritura [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Devuelve el formato de viñeta del párrafo. Solo lectura [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Devuelve el formato de porción predeterminado de un párrafo. No se aplica herencia. Solo lectura [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Devuelve o establece el tamaño de tabulación predeterminado sin herencia. Lectura/escritura Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Devuelve o establece la profundidad del párrafo. Un valor de 0 significa valor indefinido. Lectura/escritura Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Determina si se utiliza el salto de línea oriental en un párrafo. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Devuelve o establece una alineación de fuente en un párrafo sin herencia. Lectura/escritura [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Determina si se utiliza la puntuación colgante en un párrafo. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Devuelve o establece la Sangría de la Primera Línea/Sangría Colgante del párrafo sin herencia. La Sangría Colgante se puede definir con valores negativos. Lectura/escritura Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Determina si se utiliza el salto de línea latino en un párrafo. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Devuelve o establece el margen izquierdo en un párrafo sin herencia. Lectura/escritura Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Devuelve o establece el margen derecho en un párrafo sin herencia. Lectura/escritura Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Determina si se utiliza la escritura de derecha a izquierda en un párrafo. No se aplica herencia. Lectura/escritura [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Devuelve o establece la cantidad de espacio después de la última línea en un párrafo sin herencia. Un valor positivo especifica el porcentaje del tamaño de fuente que debería tener el espacio en blanco. Un valor negativo especifica el tamaño del espacio en blanco en puntos. Lectura/escritura Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Devuelve o establece la cantidad de espacio antes de la primera línea en un párrafo sin herencia. Un valor positivo especifica el porcentaje del tamaño de fuente que debería tener el espacio en blanco. Un valor negativo especifica el tamaño del espacio en blanco en puntos. Lectura/escritura Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Devuelve o establece la cantidad de espacio entre las líneas base en un párrafo. Un valor positivo significa porcentaje, negativo - tamaño en puntos. No se aplica herencia. Lectura/escritura Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Devuelve las tabulaciones de un párrafo. No se aplica herencia. Solo lectura [`ITabCollection`](../itabcollection). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Obtiene los datos de formato de párrafo efectivos con la herencia aplicada. |

### Observaciones

Esta clase se utiliza para devolver y manipular las propiedades de formato de párrafo definidas para el párrafo particular. Esto significa que no se aplica herencia al obtener valores, por lo que en la mayoría de los casos obtendrás valores que significan "indefinido".

Para obtener los valores de los parámetros de formato efectivos, incluidos los heredados, debes utilizar el método [`GetEffective`](./geteffective) que devuelve una instancia de [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Consulta También

* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->