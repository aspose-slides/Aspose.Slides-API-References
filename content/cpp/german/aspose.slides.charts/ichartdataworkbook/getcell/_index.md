---
title: GetCell()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft die Zelle ab, die für Diagrammserien oder -kategorien verwendet werden kann
type: docs
weight: 40
url: /de/aspose.slides.charts/ichartdataworkbook/getcell/
---
## IChartDataWorkbook::GetCell(System::String, int32_t, int32_t) Methode

Ruft die Zelle ab, die für Diagrammserien oder -kategorien verwendet werden kann

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Name des Arbeitsblatts. |
| row | **int32_t** | Die Zeile. |
| column | **int32_t** | Die Spalte. |

### Rückgabewert

[Cell](../../../aspose.slides/cell/) Objekt

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) Methode

Ruft die Zelle ab, die für Diagrammserien oder -kategorien verwendet werden kann

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index des Arbeitsblatts. |
| row | **int32_t** | Die Zeile. |
| column | **int32_t** | Die Spalte. |

### Rückgabewert

[Cell](../../../aspose.slides/cell/) Objekt

## IChartDataWorkbook::GetCell(int32_t, System::String) Methode

Ruft die Zelle ab, die für Diagrammserien oder -kategorien verwendet werden kann

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index des Arbeitsblatts. |
| cellName | [System::String](../../../system/string/) | Name der Zelle. |

### Rückgabewert

[Cell](../../../aspose.slides/cell/) Objekt

## IChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) Methode

Ruft die Zelle ab, die für Diagrammserien oder -kategorien verwendet werden kann

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index des Arbeitsblatts. |
| cellName | [System::String](../../../system/string/) | Name der Zelle. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Der Wert. |

### Rückgabewert

[Cell](../../../aspose.slides/cell/) Objekt

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) Methode

Ruft die Zelle ab, die für Diagrammserien oder -kategorien verwendet werden kann

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value)=0
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
* Klasse [IChartDataWorkbook](../)
* Klasse [Object](../../../system/object/)
* Namensraum [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)