---
title: Add
second_title: Referencia de API de Aspose.Slides para .NET
description: Agregar nueva celda a la colección.
type: docs
weight: 30
url: /es/aspose.slides.charts/chartcellcollection/add/
---

## Add(IChartDataCell) {#add}

Agregar nueva celda a la colección.

```csharp
public void Add(IChartDataCell cell)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cell | IChartDataCell | Nueva celda para agregar. |

### Ver También

* interface [IChartDataCell](../../ichartdatacell)
* class [ChartCellCollection](../../chartcellcollection)
* namespace [Aspose.Slides.Charts](../../chartcellcollection)
* assembly [Aspose.Slides](../../../)

---

## Add(object) {#add_1}

Crea [`ChartDataCell`](../../chartdatacell) a partir del valor especificado y lo agrega a la colección.

```csharp
public void Add(object value)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | Object | El valor. |

### Excepciones

| excepcion | condición |
| --- | --- |
| InvalidOperationException | si se excede el límite |

### Observaciones

Este método agrega una hoja de cálculo con el nombre AUTO_DATA y agrega todos los valores allí. Si utiliza [`ChartDataWorkbook`](../../chartdataworkbook) para agregar o editar valores de celda, asegúrese de que no está utilizando esta hoja de cálculo. El número máximo de valores agregados mediante este método no debe exceder 16711680.

### Ver También

* class [ChartCellCollection](../../chartcellcollection)
* namespace [Aspose.Slides.Charts](../../chartcellcollection)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->