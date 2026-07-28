---
title: GetCell()
second_title: Aspose.Slides C++ API Referencia
description: Visszaadja azt a cellát, amely a diagram sorozatokhoz vagy kategóriákhoz használható
type: docs
weight: 40
url: /hu/aspose.slides.charts/ichartdataworkbook/getcell/
---
## IChartDataWorkbook::GetCell(System::String, int32_t, int32_t) metódus

Megkapja a cellát, amely a diagram sorozatokhoz vagy kategóriákhoz használható

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | A munkalap neve. |
| row | **int32_t** | A sor. |
| column | **int32_t** | Az oszlop. |

### Visszatérési érték

[Cell](../../../aspose.slides/cell/) objektum

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) metódus


Megkapja a cellát, amely a diagram sorozatokhoz vagy kategóriákhoz használható

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| worksheetIndex | **int32_t** | A munkalap indexe. |
| row | **int32_t** | A sor. |
| column | **int32_t** | Az oszlop. |

### Visszatérési érték

[Cell](../../../aspose.slides/cell/) objektum

## IChartDataWorkbook::GetCell(int32_t, System::String) metódus


Megkapja a cellát, amely a diagram sorozatokhoz vagy kategóriákhoz használható

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| worksheetIndex | **int32_t** | A munkalap indexe. |
| cellName | [System::String](../../../system/string/) | A cella neve. |

### Visszatérési érték

[Cell](../../../aspose.slides/cell/) objektum

## IChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) metódus


Megkapja a cellát, amely a diagram sorozatokhoz vagy kategóriákhoz használható

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| worksheetIndex | **int32_t** | A munkalap indexe. |
| cellName | [System::String](../../../system/string/) | A cella neve. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Az érték. |

### Visszatérési érték

[Cell](../../../aspose.slides/cell/) objektum

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) metódus


Megkapja a cellát, amely a diagram sorozatokhoz vagy kategóriákhoz használható

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| worksheetIndex | **int32_t** | A munkalap indexe. |
| row | **int32_t** | A sor. |
| column | **int32_t** | Az oszlop. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Az érték. |

### Visszatérési érték

[Cell](../../../aspose.slides/cell/) objektum

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IChartDataCell](../../ichartdatacell/)
* Osztály [String](../../../system/string/)
* Osztály [IChartDataWorkbook](../)
* Osztály [Object](../../../system/object/)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)