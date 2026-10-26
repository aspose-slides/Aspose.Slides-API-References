---
title: Add()
second_title: Referencia de API de Aspose.Slides para C++
description: Si la categoría existe en la colección, la devuelve. De lo contrario, crea una nueva categoría de gráfico a partir de IChartDataCell y la agrega a la colección.
type: docs
weight: 53
url: /es/aspose.slides.charts/ichartcategorycollection/add/
---
## IChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) método


Si la categoría existe en la colección, la devuelve. De lo contrario crea una nueva categoría del gráfico a partir de [IChartDataCell](../../ichartdatacell/) y la agrega a la colección.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) usado para crear la categoría del gráfico. |

### Valor devuelto

Categoría añadida o existente.



## IChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) método


Crea un nuevo [IChartCategory](../../ichartcategory/) a partir del valor y lo agrega a la colección.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<System::Object> value)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | El valor. |

### Valor devuelto

Añadido [IChartCategory](../../ichartcategory/).
## Observaciones



Este método agrega una hoja de cálculo con el nombre AUTO_DATA y agrega allí todos los valores. Si usted usa [IChartDataWorkbook](../../ichartdataworkbook/) para agregar o editar valores de celdas, asegúrese de no usar esta hoja de cálculo. El número máximo de valores agregados mediante este método no debe superar 16711680



## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IChartCategory](../../ichartcategory/)
* Clase [IChartDataCell](../../ichartdatacell/)
* Clase [IChartCategoryCollection](../)
* Clase [Object](../../../system/object/)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)