---
title: IChartCategoryCollection
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa la colección deIChartCategory./ichartcategory
type: docs
weight: 1620
url: /es/aspose.slides.charts/ichartcategorycollection/
---
## IChartCategoryCollection interface

Representa la colección de[`IChartCategory`](../ichartcategory)

```csharp
public interface IChartCategoryCollection : IGenericCollection<IChartCategory>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [GroupingLevelCount](../../aspose.slides.charts/ichartcategorycollection/groupinglevelcount) { get; } | Devuelve el recuento de niveles de agrupación de categorías utilizados. Es más de uno para categorías multinivel. Solo lecturaInt32 . |
| [Item](../../aspose.slides.charts/ichartcategorycollection/item) { get; } | Obtiene el elemento en el índice especificado. |
| [UseCells](../../aspose.slides.charts/ichartcategorycollection/usecells) { get; set; } | Si es verdadero, la hoja de trabajo se usa para almacenar categorías (este caso admite categorías de niveles múltiples). Si es falso, la hoja de trabajo NO se usa para almacenar valores (y este caso no admite categorías de niveles múltiples ). Leer /escribeBoolean . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../aspose.slides.charts/ichartcategorycollection/add#add)(IChartDataCell) | Si la categoría existe en la colección, devuélvela. De lo contrario, crea una nueva categoría de gráfico a partir de [`IChartDataCell`](../ichartdatacell) y lo agrega a la colección. |
| [Add](../../aspose.slides.charts/ichartcategorycollection/add#add_1)(object) | Crea nuevo[`IChartCategory`](../ichartcategory) from value y lo agrega a la colección. |
| [Clear](../../aspose.slides.charts/ichartcategorycollection/clear)() | Elimina todos los elementos de la colección. |
| [IndexOf](../../aspose.slides.charts/ichartcategorycollection/indexof)(IChartCategory) | Busca el especificado[`IChartCategory`](../ichartcategory) y devuelve el índice de base cero de la primera aparición dentro de la colección completa |
| [Remove](../../aspose.slides.charts/ichartcategorycollection/remove)(IChartCategory) | Elimina el valor especificado. |
| [RemoveAt](../../aspose.slides.charts/ichartcategorycollection/removeat)(int) | Elimina el elemento en el índice dado. |

### Ver también

* interface [IGenericCollection&lt;T&gt;](../../aspose.slides/igenericcollection-1)
* interface [IChartCategory](../ichartcategory)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
