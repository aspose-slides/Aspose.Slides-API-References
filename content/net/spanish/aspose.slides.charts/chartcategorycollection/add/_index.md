---
title: Add
second_title: Referencia de la API de Aspose.Slides para .NET
description: Si la categoría existe en la colección, devuélvela. De lo contrario, crea una nueva categoría de gráfico a partir de IChartDataCellaspose.slides.charts/ichartdatacell y la agrega a la colección.
type: docs
weight: 70
url: /es/aspose.slides.charts/chartcategorycollection/add/
---

## Add(IChartDataCell) {#add}

Si la categoría existe en la colección, devuélvela. De lo contrario, crea una nueva categoría de gráfico a partir de [`IChartDataCell`](../../ichartdatacell) y la agrega a la colección.

```csharp
public IChartCategory Add(IChartDataCell chartDataCell)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chartDataCell | IChartDataCell | Celda utilizada para crear la categoría del gráfico. |

### Valor de Retorno

Categoría agregada o existente.

### Véase También

* interfaz [IChartCategory](../../ichartcategory)
* interfaz [IChartDataCell](../../ichartdatacell)
* clase [ChartCategoryCollection](../../chartcategorycollection)
* espacio de nombres [Aspose.Slides.Charts](../../chartcategorycollection)
* ensamblado [Aspose.Slides](../../../)

---

## Add(object) {#add_1}

Crea una nueva [`ChartCategory`](../../chartcategory) a partir de un valor y la agrega a la colección.

```csharp
public IChartCategory Add(object value)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | Object | El valor. |

### Valor de Retorno

[`IChartCategory`](../../ichartcategory) agregada.

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException | si se excede el límite |

### Comentarios

Este método agrega una hoja de cálculo con el nombre AUTO_DATA y agrega todos los valores allí. Si utilizas [`ChartDataWorkbook`](../../chartdataworkbook) para agregar o editar valores de celda, asegúrate de que no uses esta hoja de cálculo. El número máximo de valores que se pueden agregar usando este método no debe exceder 16711680.

### Véase También

* interfaz [IChartCategory](../../ichartcategory)
* clase [ChartCategoryCollection](../../chartcategorycollection)
* espacio de nombres [Aspose.Slides.Charts](../../chartcategorycollection)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->