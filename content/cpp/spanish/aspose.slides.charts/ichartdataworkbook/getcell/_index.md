---
title: GetCell()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene la celda que se puede usar para series o categorías de gráficos
type: docs
weight: 40
url: /es/aspose.slides.charts/ichartdataworkbook/getcell/
---
## IChartDataWorkbook::GetCell(System::String, int32_t, int32_t) method


Obtiene la celda que se puede usar para series o categorías de gráficos

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Nombre de la hoja de cálculo. |
| row | **int32_t** | La fila. |
| column | **int32_t** | La columna. |

### Valor de retorno

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) method


Obtiene la celda que se puede usar para series o categorías de gráficos

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Índice de la hoja de cálculo. |
| row | **int32_t** | La fila. |
| column | **int32_t** | La columna. |

### Valor de retorno

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, System::String) method


Obtiene la celda que se puede usar para series o categorías de gráficos

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Índice de la hoja de cálculo. |
| cellName | [System::String](../../../system/string/) | Nombre de la celda. |

### Valor de retorno

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) method


Obtiene la celda que se puede usar para series o categorías de gráficos

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Índice de la hoja de cálculo. |
| cellName | [System::String](../../../system/string/) | Nombre de la celda. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | El valor. |

### Valor de retorno

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) method


Obtiene la celda que se puede usar para series o categorías de gráficos

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Índice de la hoja de cálculo. |
| row | **int32_t** | La fila. |
| column | **int32_t** | La columna. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | El valor. |

### Valor de retorno

[Cell](../../../aspose.slides/cell/) object

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [String](../../../system/string/)
* Class [IChartDataWorkbook](../)
* Class [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)