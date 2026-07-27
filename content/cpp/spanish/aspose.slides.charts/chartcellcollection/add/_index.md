---
title: Add()
second_title: Referencia de API de Aspose.Slides para C++
description: Añade una nueva celda a la colección.
type: docs
weight: 53
url: /es/aspose.slides.charts/chartcellcollection/add/
---
## ChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) método

Añade una nueva celda a la colección.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<IChartDataCell> cell) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Nueva celda a añadir. |

## ChartCellCollection::Add(System::SharedPtr\<System::Object\>) método

Crea [ChartDataCell](../../chartdatacell/) a partir del valor especificado y lo añade a la colección.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<System::Object> value) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | El valor. |

## Observaciones

Este método agrega una hoja de cálculo con el nombre AUTO_DATA y añade allí todos los valores. Si utiliza [ChartDataWorkbook](../../chartdataworkbook/) para agregar o editar valores [Cell](../../../aspose.slides/cell/), asegúrese de no utilizar esta hoja de cálculo. El número máximo de valores añadidos mediante este método no debe superar 16711680

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IChartDataCell](../../ichartdatacell/)
* Clase [ChartCellCollection](../)
* Clase [Object](../../../system/object/)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)