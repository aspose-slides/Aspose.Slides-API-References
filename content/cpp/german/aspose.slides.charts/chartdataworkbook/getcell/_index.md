---
title: GetCell()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt die Zelle, die für Diagrammserien oder Kategorien verwendet werden kann
type: docs
weight: 27
url: /de/aspose.slides.charts/chartdataworkbook/getcell/
---
## ChartDataWorkbook::GetCell(System::String, int32_t, int32_t) Methode

Ermittelt die Zelle, die für Diagrammserien oder Kategorien verwendet werden kann.

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Name des Arbeitsblatts. |
| row | **int32_t** | Die Zeile. |
| column | **int32_t** | Die Spalte. |

### Rückgabewert

[Cell](../../../aspose.slides/cell/) Objekt

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) Methode


Ermittelt die Zelle, die für Diagrammserien oder Kategorien verwendet werden kann.

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index des Arbeitsblatts. |
| row | **int32_t** | Die Zeile. |
| column | **int32_t** | Die Spalte. |

### Rückgabewert

[Cell](../../../aspose.slides/cell/) Objekt

## ChartDataWorkbook::GetCell(int32_t, System::String) Methode


Ermittelt die Zelle, die für Diagrammserien oder Kategorien verwendet werden kann.

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index des Arbeitsblatts. |
| cellName | [System::String](../../../system/string/) | Name der Zelle. |

### Rückgabewert

[Cell](../../../aspose.slides/cell/) Objekt

## ChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) Methode


Ermittelt die Zelle, die für Diagrammserien oder Kategorien verwendet werden kann.

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index des Arbeitsblatts. |
| cellName | [System::String](../../../system/string/) | Name der Zelle. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Der Wert. |

### Rückgabewert

[Cell](../../../aspose.slides/cell/) Objekt

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) Methode


Ermittelt die Zelle, die für Diagrammserien oder Kategorien verwendet werden kann.

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index des Arbeitsblatts. |
| row | **int32_t** | Die Zeile. |
| column | **int32_t** | Die Spalte. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Der Wert. |

### Rückgabewert

[Cell](../../../aspose.slides/cell/) Objekt

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartDataCell](../../ichartdatacell/)
* Klasse [String](../../../system/string/)
* Klasse [ChartDataWorkbook](../)
* Klasse [Object](../../../system/object/)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)