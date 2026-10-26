---
title: GetCell()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de cel op die kan worden gebruikt voor grafiekseries of categorieën
type: docs
weight: 40
url: /nl/aspose.slides.charts/ichartdataworkbook/getcell/
---
## IChartDataWorkbook::GetCell(System::String, int32_t, int32_t) method

Haalt de cel op die kan worden gebruikt voor grafiekseries of categorieën

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Naam van het werkblad. |
| row | **int32_t** | De rij. |
| column | **int32_t** | De kolom. |

### Retourwaarde

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) method

Haalt de cel op die kan worden gebruikt voor grafiekseries of categorieën

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index van het werkblad. |
| row | **int32_t** | De rij. |
| column | **int32_t** | De kolom. |

### Retourwaarde

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, System::String) method

Haalt de cel op die kan worden gebruikt voor grafiekseries of categorieën

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index van het werkblad. |
| cellName | [System::String](../../../system/string/) | Naam van de cel. |

### Retourwaarde

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) method

Haalt de cel op die kan worden gebruikt voor grafiekseries of categorieën

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index van het werkblad. |
| cellName | [System::String](../../../system/string/) | Naam van de cel. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | De waarde. |

### Retourwaarde

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) method

Haalt de cel op die kan worden gebruikt voor grafiekseries of categorieën

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index van het werkblad. |
| row | **int32_t** | De rij. |
| column | **int32_t** | De kolom. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | De waarde. |

### Retourwaarde

[Cell](../../../aspose.slides/cell/) object

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [String](../../../system/string/)
* Class [IChartDataWorkbook](../)
* Class [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)