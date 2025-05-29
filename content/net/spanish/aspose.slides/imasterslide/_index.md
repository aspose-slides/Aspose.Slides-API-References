---
title: IMasterSlide
second_title: Aspose.Sildes para .NET API Reference
description: Representa una diapositiva maestra en una presentación.
type: docs
weight: 6220
url: /es/aspose.slides/imasterslide/
---

## Interfaz IMasterSlide

Representa una diapositiva maestra en una presentación.

```csharp
public interface IMasterSlide : IBaseSlide, IMasterThemeable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIBaseSlide](../../aspose.slides/imasterslide/asibaseslide) { get; } | Permite obtener la interfaz base IBaseSlide. Solo lectura [`IBaseSlide`](../ibaseslide). |
| [AsIMasterThemeable](../../aspose.slides/imasterslide/asimasterthemeable) { get; } | Devuelve la interfaz IMasterThemeable. Solo lectura [`IMasterThemeable`](../../aspose.slides.theme/imasterthemeable). |
| [BodyStyle](../../aspose.slides/imasterslide/bodystyle) { get; } | Devuelve el estilo de un texto de cuerpo. Solo lectura [`ITextStyle`](../itextstyle). |
| [HasDependingSlides](../../aspose.slides/imasterslide/hasdependingslides) { get; } | Devuelve verdadero si existe al menos una diapositiva que depende de esta diapositiva maestra. Solo lectura Booleano. |
| [HeaderFooterManager](../../aspose.slides/imasterslide/headerfootermanager) { get; } | Devuelve el administrador de encabezados y pies de página de la diapositiva maestra. Solo lectura [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [LayoutSlides](../../aspose.slides/imasterslide/layoutslides) { get; } | Devuelve la colección de diapositivas de diseño secundarias para esta diapositiva maestra. Solo lectura [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| [OtherStyle](../../aspose.slides/imasterslide/otherstyle) { get; } | Devuelve el estilo de otro texto. Solo lectura [`ITextStyle`](../itextstyle). |
| [Preserve](../../aspose.slides/imasterslide/preserve) { get; set; } | Determina si la maestra correspondiente se elimina cuando se eliminan todas las diapositivas que siguen a esa maestra. Nota: Aspose.Slides nunca eliminará ninguna maestra no utilizada por sí misma, para eliminar realmente las maestras no utilizadas llame a [`RemoveUnused`](../imasterslidecollection/removeunused) Lectura/escritura Booleano. |
| [TitleStyle](../../aspose.slides/imasterslide/titlestyle) { get; } | Devuelve el estilo de un texto de título. Solo lectura [`ITextStyle`](../itextstyle). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/imasterslide/applyexternalthemetodependingslides)(string) | Crea una nueva diapositiva maestra basada en la actual, aplicando un tema externo a ella y aplica la diapositiva maestra creada a todas las diapositivas dependientes. |
| [GetDependingSlides](../../aspose.slides/imasterslide/getdependingslides)() | Devuelve un arreglo con todas las diapositivas que dependen de esta diapositiva maestra. |

### Ver También

* interfaz [IBaseSlide](../ibaseslide)
* interfaz [IMasterThemeable](../../aspose.slides.theme/imasterthemeable)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITE: generado por xmldocmd para Aspose.Slides.dll -->