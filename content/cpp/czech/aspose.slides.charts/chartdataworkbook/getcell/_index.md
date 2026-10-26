---
title: GetCell()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vrací buňku, která může být použita pro řady grafu nebo kategorie
type: docs
weight: 27
url: /cs/aspose.slides.charts/chartdataworkbook/getcell/
---
## ChartDataWorkbook::GetCell(System::String, int32_t, int32_t) metoda

Vrací buňku, která může být použita pro řady grafu nebo kategorie

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Název listu. |
| row | **int32_t** | Řádek. |
| column | **int32_t** | Sloupec. |

### Návratová hodnota

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) metoda

Vrací buňku, která může být použita pro řady grafu nebo kategorie

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index listu. |
| row | **int32_t** | Řádek. |
| column | **int32_t** | Sloupec. |

### Návratová hodnota

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, System::String) metoda

Vrací buňku, která může být použita pro řady grafu nebo kategorie

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index listu. |
| cellName | [System::String](../../../system/string/) | Název buňky. |

### Návratová hodnota

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) metoda

Vrací buňku, která může být použita pro řady grafu nebo kategorie

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index listu. |
| cellName | [System::String](../../../system/string/) | Název buňky. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Hodnota. |

### Návratová hodnota

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) metoda

Vrací buňku, která může být použita pro řady grafu nebo kategorie

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index listu. |
| row | **int32_t** | Řádek. |
| column | **int32_t** | Sloupec. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Hodnota. |

### Návratová hodnota

[Cell](../../../aspose.slides/cell/) object

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IChartDataCell](../../ichartdatacell/)
* Třída [String](../../../system/string/)
* Třída [ChartDataWorkbook](../)
* Třída [Object](../../../system/object/)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)