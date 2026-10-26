---
title: GetCell()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Získá buňku, která může být použita pro řady nebo kategorie grafu
type: docs
weight: 40
url: /cs/aspose.slides.charts/ichartdataworkbook/getcell/
---
## IChartDataWorkbook::GetCell(System::String, int32_t, int32_t) metoda


Získá buňku, kterou lze použít pro řady nebo kategorie grafu

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Název listu. |
| row | **int32_t** | Řádek. |
| column | **int32_t** | Sloupec. |

### Návratová hodnota

[Cell](../../../aspose.slides/cell/) objekt

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) metoda


Získá buňku, kterou lze použít pro řady nebo kategorie grafu

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index listu. |
| row | **int32_t** | Řádek. |
| column | **int32_t** | Sloupec. |

### Návratová hodnota

[Cell](../../../aspose.slides/cell/) objekt

## IChartDataWorkbook::GetCell(int32_t, System::String) metoda


Získá buňku, kterou lze použít pro řady nebo kategorie grafu

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index listu. |
| cellName | [System::String](../../../system/string/) | Název buňky. |

### Návratová hodnota

[Cell](../../../aspose.slides/cell/) objekt

## IChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) metoda


Získá buňku, kterou lze použít pro řady nebo kategorie grafu

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index listu. |
| cellName | [System::String](../../../system/string/) | Název buňky. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Hodnota. |

### Návratová hodnota

[Cell](../../../aspose.slides/cell/) objekt

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) metoda


Získá buňku, kterou lze použít pro řady nebo kategorie grafu

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index listu. |
| row | **int32_t** | Řádek. |
| column | **int32_t** | Sloupec. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Hodnota. |

### Návratová hodnota

[Cell](../../../aspose.slides/cell/) objekt

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IChartDataCell](../../ichartdatacell/)
* Třída [String](../../../system/string/)
* Třída [IChartDataWorkbook](../)
* Třída [Object](../../../system/object/)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)