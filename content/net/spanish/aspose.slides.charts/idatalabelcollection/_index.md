---
title: IDataLabelCollection
second_title: Referencia de API de Aspose.Sildes para .NET
description: Representa etiquetas de una serie.
type: docs
weight: 1950
url: /es/aspose.slides.charts/idatalabelcollection/
---

## Interfaz IDataLabelCollection

Representa etiquetas de una serie.

```csharp
public interface IDataLabelCollection : IChartComponent, IEnumerable<IDataLabel>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/idatalabelcollection/asichartcomponent) { get; } | Permite obtener la interfaz base IChartComponent. Solo lectura [`IChartComponent`](../ichartcomponent). |
| [AsIEnumerable](../../aspose.slides.charts/idatalabelcollection/asienumerable) { get; } | Permite obtener la interfaz base IEnumerable. Solo lectura IEnumerable. |
| [Count](../../aspose.slides.charts/idatalabelcollection/count) { get; } | Obtiene el número de todas las etiquetas de datos en la colección. Solo lectura Int32. |
| [CountOfVisibleDataLabels](../../aspose.slides.charts/idatalabelcollection/countofvisibledatalabels) { get; } | Obtiene el número de etiquetas de datos visibles en la colección. Solo lectura Int32. |
| [DefaultDataLabelFormat](../../aspose.slides.charts/idatalabelcollection/defaultdatalabelformat) { get; } | Devuelve el formato predeterminado de todas las etiquetas de datos en la colección. Solo lectura [`IDataLabelFormat`](../idatalabelformat). |
| [IsVisible](../../aspose.slides.charts/idatalabelcollection/isvisible) { get; } | Falso significa que la etiqueta de datos no es visible por defecto (y por lo tanto todas las banderas Show*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat son falsas). Solo lectura Boolean. |
| [Item](../../aspose.slides.charts/idatalabelcollection/item) { get; } | Obtiene la etiqueta de datos para el punto de datos con el índice especificado. |
| [LeaderLinesFormat](../../aspose.slides.charts/idatalabelcollection/leaderlinesformat) { get; } | Representa el formato de las líneas líderes de etiquetas de datos. Solo lectura [`IChartLinesFormat`](../ichartlinesformat). |
| [ParentSeries](../../aspose.slides.charts/idatalabelcollection/parentseries) { get; } | Devuelve la serie de gráficos padre. Solo lectura [`IChartSeries`](../ichartseries). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Hide](../../aspose.slides.charts/idatalabelcollection/hide)() | Hace que la etiqueta de datos esté oculta por defecto configurando todas las banderas Show*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat en estado falso. IsVisible será falso después de esto. |
| [IndexOf](../../aspose.slides.charts/idatalabelcollection/indexof)(IDataLabel) | Devuelve un índice de la DataLabel especificada en la colección. |

### Ver También

* interfaz [IChartComponent](../ichartcomponent)
* interfaz [IDataLabel](../idatalabel)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->