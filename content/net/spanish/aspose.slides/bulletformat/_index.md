---
title: BulletFormat
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa las propiedades de formato de viñetas en un párrafo.
type: docs
weight: 990
url: /es/aspose.slides/bulletformat/
---

## Clase BulletFormat

Representa las propiedades de formato de viñetas en un párrafo.

```csharp
public sealed class BulletFormat : PVIObject, IBulletFormat
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obtener la interfaz base IPresentationComponent. Solo lectura [`IPresentationComponent`](../ipresentationcomponent). |
| [Char](../../aspose.slides/bulletformat/char) { get; set; } | Devuelve o establece el carácter de viñeta de un párrafo sin herencia. Lectura/escritura Char. |
| [Color](../../aspose.slides/bulletformat/color) { get; } | Devuelve el formato de color de una viñeta de un párrafo sin herencia. Solo lectura [`IColorFormat`](../icolorformat). |
| [Font](../../aspose.slides/bulletformat/font) { get; set; } | Devuelve o establece la fuente de viñeta de un párrafo sin herencia. Lectura/escritura [`IFontData`](../ifontdata). |
| [Height](../../aspose.slides/bulletformat/height) { get; set; } | Devuelve o establece la altura de la viñeta de un párrafo sin herencia. El valor float.NaN determina que la viñeta hereda la altura de la primera porción en el párrafo. Lectura/escritura Single. |
| [IsBulletHardColor](../../aspose.slides/bulletformat/isbullethardcolor) { get; set; } | Determina si la viñeta tiene su propio color o lo hereda de la primera porción en el párrafo. **NullableBool.True** si la viñeta tiene su propio color y **NullableBool.False** si la viñeta hereda el color de la primera porción en el párrafo. Lectura/escritura [`NullableBool`](../nullablebool). |
| [IsBulletHardFont](../../aspose.slides/bulletformat/isbullethardfont) { get; set; } | Determina si la viñeta tiene su propia fuente o la hereda de la primera porción en el párrafo. **NullableBool.True** si la viñeta tiene su propia fuente y **NullableBool.False** si la viñeta hereda la fuente de la primera porción en el párrafo. Lectura/escritura [`NullableBool`](../nullablebool). |
| [NumberedBulletStartWith](../../aspose.slides/bulletformat/numberedbulletstartwith) { get; set; } | Devuelve o establece el primer número que se utiliza para el grupo de viñetas numeradas sin herencia. Lectura/escritura Int16. |
| [NumberedBulletStyle](../../aspose.slides/bulletformat/numberedbulletstyle) { get; set; } | Devuelve o establece el estilo de una viñeta numerada sin herencia. Lectura/escritura [`NumberedBulletStyle`](../numberedbulletstyle). |
| [Picture](../../aspose.slides/bulletformat/picture) { get; } | Devuelve la imagen utilizada como viñeta en un párrafo sin herencia. Solo lectura [`ISlidesPicture`](../islidespicture). |
| [Type](../../aspose.slides/bulletformat/type) { get; set; } | Devuelve o establece el tipo de viñeta de un párrafo sin herencia. Lectura/escritura [`BulletType`](../bullettype). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ApplyDefaultParagraphIndentsShifts](../../aspose.slides/bulletformat/applydefaultparagraphindentsshifts)() | Establece desplazamientos predeterminados no cero para el sangrado efectivo del párrafo y MarginLeft cuando las viñetas están habilitadas (como lo hace PowerPoint si habilita las viñetas/numeración en el párrafo). Si las viñetas están deshabilitadas, entonces simplemente restablece el sangrado del párrafo y MarginLeft (como lo hace PowerPoint si desactiva las viñetas/numeración en el párrafo). Los desplazamientos de sangrado se aplican con respecto al contexto actual de la viñeta - IBulletFormat.Type, .NumberedBulletStyle y FontHeight de la primera porción. Los desplazamientos de sangrado no cero se aplican al sangrado efectivo y MarginLeft del párrafo actual (hacen que los valores resultantes sean valores locales). |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compara con el objeto especificado. |
| [GetEffective](../../aspose.slides/bulletformat/geteffective)() | Obtiene los datos de formato de viñeta efectivos con la herencia aplicada. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Devuelve el código hash. |

### También Visto

* clase [PVIObject](../pviobject)
* interfaz [IBulletFormat](../ibulletformat)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblaje [Aspose.Slides](../../)