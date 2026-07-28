---
title: GetCell()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Pobiera komórkę, którą można wykorzystać dla serii wykresu lub kategorii
type: docs
weight: 40
url: /pl/aspose.slides.charts/ichartdataworkbook/getcell/
---
## IChartDataWorkbook::GetCell(System::String, int32_t, int32_t) metoda


Pobiera komórkę, którą można wykorzystać dla serii wykresu lub kategorii

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Nazwa arkusza. |
| row | **int32_t** | Wiersz. |
| column | **int32_t** | Kolumna. |

### Wartość zwracana

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) metoda


Pobiera komórkę, którą można wykorzystać dla serii wykresu lub kategorii

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Indeks arkusza. |
| row | **int32_t** | Wiersz. |
| column | **int32_t** | Kolumna. |

### Wartość zwracana

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, System::String) metoda


Pobiera komórkę, którą można wykorzystać dla serii wykresu lub kategorii

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Indeks arkusza. |
| cellName | [System::String](../../../system/string/) | Nazwa komórki. |

### Wartość zwracana

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) metoda


Pobiera komórkę, którą można wykorzystać dla serii wykresu lub kategorii

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Indeks arkusza. |
| cellName | [System::String](../../../system/string/) | Nazwa komórki. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Wartość. |

### Wartość zwracana

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) metoda


Pobiera komórkę, którą można wykorzystać dla serii wykresu lub kategorii

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Indeks arkusza. |
| row | **int32_t** | Wiersz. |
| column | **int32_t** | Kolumna. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Wartość. |

### Wartość zwracana

[Cell](../../../aspose.slides/cell/) object

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IChartDataCell](../../ichartdatacell/)
* Klasa [String](../../../system/string/)
* Klasa [IChartDataWorkbook](../)
* Klasa [Object](../../../system/object/)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)