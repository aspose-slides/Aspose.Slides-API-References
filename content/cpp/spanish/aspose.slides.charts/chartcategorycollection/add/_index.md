---
title: Add()
second_title: Referencia de la API de Aspose.Slides para C++
description: Si la categoría existe en la colección, la devuelve. De lo contrario, crea una nueva categoría de gráfico a partir de IChartDataCell y la añade a la colección.
type: docs
weight: 92
url: /es/aspose.slides.charts/chartcategorycollection/add/
---
## ChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) método

Si la categoría existe en la colección, la devuelve. De lo contrario crea una nueva categoría de gráfico a partir de [IChartDataCell](../../ichartdatacell/) y la añade a la colección.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) utilizado para crear la categoría del gráfico. |

### Valor devuelto

Categoría añadida o existente.

## ChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) método

Crea un nuevo [ChartCategory](../../chartcategory/) a partir del valor y lo añade a la colección.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<System::Object> value) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | El valor. |

### Valor devuelto

Añadido [IChartCategory](../../ichartcategory/).

## Observaciones

Este método añade una hoja de cálculo con el nombre AUTO_DATA y agrega todos los valores allí. Si utiliza [ChartDataWorkbook](../../chartdataworkbook/) para añadir o editar valores de celdas, asegúrese de no usar esta hoja de cálculo. El número máximo de valores añadidos mediante este método no debe superar 16711680

## Ver también

* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [IChartCategory](../../ichartcategory/)
* Clase [IChartDataCell](../../ichartdatacell/)
* Clase [ChartCategoryCollection](../)
* Clase [Object](../../../system/object/)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)