---
title: GetCell()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene la celda que se puede usar para series o categorías del gráfico
type: docs
weight: 27
url: /es/aspose.slides.charts/chartdataworkbook/getcell/
---
## ChartDataWorkbook::GetCell(System::String, int32_t, int32_t) método


Obtiene la celda que se puede usar para series o categorías del gráfico

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Nombre de la hoja de cálculo. |
| row | **int32_t** | La fila. |
| column | **int32_t** | La columna. |

### Valor devuelto

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) método


Obtiene la celda que se puede usar para series o categorías del gráfico

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Índice de la hoja de cálculo. |
| row | **int32_t** | La fila. |
| column | **int32_t** | La columna. |

### Valor devuelto

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, System::String) método


Obtiene la celda que se puede usar para series o categorías del gráfico

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Índice de la hoja de cálculo. |
| cellName | [System::String](../../../system/string/) | Nombre de la celda. |

### Valor devuelto

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) método


Obtiene la celda que se puede usar para series o categorías del gráfico

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value) override
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Índice de la hoja de cálculo. |
| cellName | [System::String](../../../system/string/) | Nombre de la celda. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | El valor. |

### Valor devuelto

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) método


Obtiene la celda que se puede usar para series o categorías del gráfico

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value) override
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Índice de la hoja de cálculo. |
| row | **int32_t** | La fila. |
| column | **int32_t** | La columna. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | El valor. |

### Valor devuelto

[Cell](../../../aspose.slides/cell/) object

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IChartDataCell](../../ichartdatacell/)
* Clase [String](../../../system/string/)
* Clase [ChartDataWorkbook](../)
* Clase [Object](../../../system/object/)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)