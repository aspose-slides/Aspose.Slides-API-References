---
title: Add()
second_title: Referencia de API de Aspose.Slides para C++
description: Agregar una nueva celda a la colección.
type: docs
weight: 53
url: /es/aspose.slides.charts/ichartcellcollection/add/
---
## IChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) método


Agregar una nueva celda a la colección.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Nueva celda a agregar. |

## IChartCellCollection::Add(System::SharedPtr\<System::Object\>) método


Crea [IChartDataCell](../../ichartdatacell/) a partir del valor especificado y lo agrega a la colección.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<System::Object> value)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | El valor. |
## Remarks



Este método agrega una hoja de cálculo con el nombre AUTO_DATA y agrega todos los valores allí. Si usa [IChartDataWorkbook](../../ichartdataworkbook/) para agregar o editar valores [Cell](../../../aspose.slides/cell/), asegúrese de no usar esta hoja de cálculo. El número máximo de valores agregados mediante este método no debe exceder 16711680



## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IChartDataCell](../../ichartdatacell/)
* Clase [IChartCellCollection](../)
* Clase [Object](../../../system/object/)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)