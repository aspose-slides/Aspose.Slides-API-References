---
title: IDataLabelCollection
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa una serie de etiquetas.
type: docs
weight: 1890
url: /es/net/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection interface

Representa una serie de etiquetas.

```csharp
public interface IDataLabelCollection : IChartComponent, IEnumerable<IDataLabel>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/idatalabelcollection/asichartcomponent) { get; } | Permite obtener la interfaz base de IChartComponent. Solo lectura[`IChartComponent`](../ichartcomponent) . |
| [AsIEnumerable](../../aspose.slides.charts/idatalabelcollection/asienumerable) { get; } | Permite obtener la interfaz base IEnumerable. Solo lecturaIEnumerable . |
| [Count](../../aspose.slides.charts/idatalabelcollection/count) { get; } | Obtiene el número de todas las etiquetas de datos de la colección. Solo lecturaInt32 . |
| [CountOfVisibleDataLabels](../../aspose.slides.charts/idatalabelcollection/countofvisibledatalabels) { get; } | Obtiene el número de etiquetas de datos visibles en la colección. Solo lecturaInt32 . |
| [DefaultDataLabelFormat](../../aspose.slides.charts/idatalabelcollection/defaultdatalabelformat) { get; } | Devuelve el formato predeterminado de todas las etiquetas de datos de la colección. Solo lectura[`IDataLabelFormat`](../idatalabelformat) . |
| [IsVisible](../../aspose.slides.charts/idatalabelcollection/isvisible) { get; } | Falso significa que la etiqueta de datos no está visible de forma predeterminada (por lo que todos los indicadores Show* (ShowValue, ...) de la propiedad DefaultDataLabelFormat son falsos). Solo lecturaBoolean . |
| [Item](../../aspose.slides.charts/idatalabelcollection/item) { get; } | Obtiene la etiqueta de datos para el punto de datos con el índice especificado. |
| [ParentSeries](../../aspose.slides.charts/idatalabelcollection/parentseries) { get; } | Devuelve la serie del gráfico principal. Solo lectura[`IChartSeries`](../ichartseries) . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Hide](../../aspose.slides.charts/idatalabelcollection/hide)() | Oculte la etiqueta de datos de forma predeterminada configurando todos los indicadores Mostrar* (ShowValue, ...) de la propiedad DefaultDataLabelFormat en estado falso. IsVisible será falso después de esto. |
| [IndexOf](../../aspose.slides.charts/idatalabelcollection/indexof)(IDataLabel) | Devuelve un índice del DataLabel especificado en la colección. |

### Ver también

* interface [IChartComponent](../ichartcomponent)
* interface [IDataLabel](../idatalabel)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->