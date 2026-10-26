---
title: GetCell()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar cellen som kan användas för diagramserier eller kategorier
type: docs
weight: 40
url: /sv/aspose.slides.charts/ichartdataworkbook/getcell/
---
## IChartDataWorkbook::GetCell(System::String, int32_t, int32_t) metod

Hämtar cellen som kan användas för diagramserier eller kategorier

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Namnet på arbetsbladet. |
| row | **int32_t** | Raden. |
| column | **int32_t** | Kolumnen. |

### Returvärde

[Cell](../../../aspose.slides/cell/) objekt

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) metod


Hämtar cellen som kan användas för diagramserier eller kategorier

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index för arbetsbladet. |
| row | **int32_t** | Raden. |
| column | **int32_t** | Kolumnen. |

### Returvärde

[Cell](../../../aspose.slides/cell/) objekt

## IChartDataWorkbook::GetCell(int32_t, System::String) metod


Hämtar cellen som kan användas för diagramserier eller kategorier

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index för arbetsbladet. |
| cellName | [System::String](../../../system/string/) | Namnet på cellen. |

### Returvärde

[Cell](../../../aspose.slides/cell/) objekt

## IChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) metod


Hämtar cellen som kan användas för diagramserier eller kategorier

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value)=0
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index för arbetsbladet. |
| cellName | [System::String](../../../system/string/) | Namnet på cellen. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Värdet. |

### Returvärde

[Cell](../../../aspose.slides/cell/) objekt

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) metod


Hämtar cellen som kan användas för diagramserier eller kategorier

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value)=0
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index för arbetsbladet. |
| row | **int32_t** | Raden. |
| column | **int32_t** | Kolumnen. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Värdet. |

### Returvärde

[Cell](../../../aspose.slides/cell/) objekt

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IChartDataCell](../../ichartdatacell/)
* Klass [String](../../../system/string/)
* Klass [IChartDataWorkbook](../)
* Klass [Object](../../../system/object/)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)