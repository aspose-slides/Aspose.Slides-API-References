---
title: IChartCategoryCollection
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa la colección de IChartCategory./ichartcategory
type: docs
weight: 1680
url: /es/aspose.slides.charts/ichartcategorycollection/
---

## Interfaz IChartCategoryCollection

Representa la colección de [`IChartCategory`](../ichartcategory)

```csharp
public interface IChartCategoryCollection : IGenericCollection<IChartCategory>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [GroupingLevelCount](../../aspose.slides.charts/ichartcategorycollection/groupinglevelcount) { get; } | Devuelve la cantidad de niveles de agrupación de categorías utilizados. Es más de uno para categorías multilevel. Solo lectura Int32. |
| [Item](../../aspose.slides.charts/ichartcategorycollection/item) { get; } | Obtiene el elemento en el índice especificado. |
| [UseCells](../../aspose.slides.charts/ichartcategorycollection/usecells) { get; set; } | Si es verdadero, entonces la hoja de cálculo se utiliza para almacenar categorías (este caso admite categorías multilevel). Si es falso, entonces la hoja de cálculo NO se utiliza para almacenar valores (y este caso no admite categorías multilevel). Lectura/escritura Boolean. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../aspose.slides.charts/ichartcategorycollection/add#add)(IChartDataCell) | Si la categoría existe en la colección, devuélvela. De lo contrario, crea una nueva categoría de gráfico a partir de [`IChartDataCell`](../ichartdatacell) y la agrega a la colección. |
| [Add](../../aspose.slides.charts/ichartcategorycollection/add#add_1)(object) | Crea una nueva [`IChartCategory`](../ichartcategory) a partir del valor y la agrega a la colección. |
| [Clear](../../aspose.slides.charts/ichartcategorycollection/clear)() | Elimina todos los elementos de la colección. |
| [IndexOf](../../aspose.slides.charts/ichartcategorycollection/indexof)(IChartCategory) | Busca el [`IChartCategory`](../ichartcategory) especificado y devuelve el índice basado en cero de la primera ocurrencia dentro de toda la colección. |
| [Remove](../../aspose.slides.charts/ichartcategorycollection/remove)(IChartCategory) | Elimina el valor especificado. |
| [RemoveAt](../../aspose.slides.charts/ichartcategorycollection/removeat)(int) | Elimina el elemento en el índice dado. |

### También vea

* interfaz [IGenericCollection&lt;T&gt;](../../aspose.slides/igenericcollection-1)
* interfaz [IChartCategory](../ichartcategory)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->