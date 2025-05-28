---
title: Agregar
second_title: Referencia de API de Aspose.Slides para .NET
description: Si la categoría existe en la colección, devuélvela. De lo contrario, crea una nueva categoría de gráfico a partir de IChartDataCellaspose.slides.charts/ichartdatacell y la añade a la colección.
type: docs
weight: 40
url: /es/aspose.slides.charts/ichartcategorycollection/add/
---

## Add(IChartDataCell) {#add}

Si la categoría existe en la colección, devuélvela. De lo contrario, crea una nueva categoría de gráfico a partir de [`IChartDataCell`](../../ichartdatacell) y la añade a la colección.

```csharp
public IChartCategory Add(IChartDataCell chartDataCell)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chartDataCell | IChartDataCell | Celda utilizada para crear la categoría de gráfico. |

### Valor de Retorno

Categoría añadida o existente.

### Ver También

* interface [IChartCategory](../../ichartcategory)
* interface [IChartDataCell](../../ichartdatacell)
* interface [IChartCategoryCollection](../../ichartcategorycollection)
* namespace [Aspose.Slides.Charts](../../ichartcategorycollection)
* assembly [Aspose.Slides](../../../)

---

## Add(object) {#add_1}

Crea un nuevo [`IChartCategory`](../../ichartcategory) a partir del valor y lo añade a la colección.

```csharp
public IChartCategory Add(object value)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | Object | El valor. |

### Valor de Retorno

[`IChartCategory`](../../ichartcategory) añadida.

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException | si se excede el límite |

### Notas

Este método añade una hoja de cálculo con el nombre AUTO_DATA y añade todos los valores allí. Si utilizas [`IChartDataWorkbook`](../../ichartdataworkbook) para añadir o editar valores de celdas, asegúrate de no utilizar esta hoja de cálculo. El número máximo de valores añadidos usando este método no debe exceder 16711680.

### Ver También

* interface [IChartCategory](../../ichartcategory)
* interface [IChartCategoryCollection](../../ichartcategorycollection)
* namespace [Aspose.Slides.Charts](../../ichartcategorycollection)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->