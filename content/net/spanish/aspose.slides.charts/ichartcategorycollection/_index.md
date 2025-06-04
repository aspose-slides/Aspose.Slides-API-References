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
| [GroupingLevelCount](../../aspose.slides.charts/ichartcategorycollection/groupinglevelcount) { get; } | Devuelve la cantidad de niveles de agrupación de categorías utilizados. Es más de uno para categorías de varios niveles. Solo lectura Int32. |
| [Item](../../aspose.slides.charts/ichartcategorycollection/item) { get; } | Obtiene el elemento en el índice especificado. |
| [UseCells](../../aspose.slides.charts/ichartcategorycollection/usecells) { get; set; } | Si es verdadero, entonces se utiliza la hoja de trabajo para almacenar categorías (en este caso admite categorías de varios niveles). Si es falso, entonces la hoja de trabajo NO se utiliza para almacenar valores (y este caso no admite categorías de varios niveles). Lectura/escritura Boolean. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../aspose.slides.charts/ichartcategorycollection/add#add)(IChartDataCell) | Si la categoría existe en la colección, la devuelve. De lo contrario, crea una nueva categoría de gráfico a partir de [`IChartDataCell`](../ichartdatacell) y la añade a la colección. |
| [Add](../../aspose.slides.charts/ichartcategorycollection/add#add_1)(object) | Crea una nueva [`IChartCategory`](../ichartcategory) a partir del valor y la añade a la colección. |
| [Clear](../../aspose.slides.charts/ichartcategorycollection/clear)() | Elimina todos los elementos de la colección. |
| [IndexOf](../../aspose.slides.charts/ichartcategorycollection/indexof)(IChartCategory) | Busca la [`IChartCategory`](../ichartcategory) especificada y devuelve el índice basado en cero de la primera ocurrencia dentro de toda la colección. |
| [Remove](../../aspose.slides.charts/ichartcategorycollection/remove)(IChartCategory) | Elimina el valor especificado. |
| [RemoveAt](../../aspose.slides.charts/ichartcategorycollection/removeat)(int) | Elimina el elemento en el índice dado. |

### Véase también

* interfaz [IGenericCollection&lt;T&gt;](../../aspose.slides/igenericcollection-1)
* interfaz [IChartCategory](../ichartcategory)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->