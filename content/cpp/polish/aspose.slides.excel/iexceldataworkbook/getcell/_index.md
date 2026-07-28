---
title: GetCell()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Pobiera komórkę z określonego arkusza kalkulacyjnego, używając jego indeksu i współrzędnych komórki.
type: docs
weight: 14
url: /pl/aspose.slides.excel/iexceldataworkbook/getcell/
---
## IExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) metoda


Pobiera komórkę z określonego arkusza kalkulacyjnego, używając jego indeksu i współrzędnych komórki.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Indeks arkusza zaczynający się od zera. |
| row | **int32_t** | Indeks wiersza komórki zaczynający się od zera. |
| column | **int32_t** | Indeks kolumny komórki zaczynający się od zera. |

### Wartość zwracana

Komórka znajdująca się w określonym miejscu.
## Uwagi



Przykład: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) metoda


Pobiera komórkę z określonego arkusza kalkulacyjnego, używając jego nazwy i współrzędnych komórki.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Nazwa arkusza kalkulacyjnego. |
| row | **int32_t** | Indeks wiersza komórki zaczynający się od zera. |
| column | **int32_t** | Indeks kolumny komórki zaczynający się od zera. |

### Wartość zwracana

Komórka znajdująca się w określonym miejscu.
## Uwagi



Przykład: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(int32_t, System::String) metoda


Pobiera komórkę z określonego arkusza kalkulacyjnego, używając jego indeksu oraz nazwy komórki w stylu Excel (np. "B2").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Indeks arkusza zaczynający się od zera. |
| cellName | [System::String](../../../system/string/) | Odwołanie do komórki w stylu Excel (np. "A1", "C5"). |

### Wartość zwracana

Komórka znajdująca się w określonym miejscu.
## Uwagi



Przykład: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, System::String) metoda


Pobiera komórkę z określonego arkusza kalkulacyjnego, używając nazwy komórki w stylu Excel (np. "B2").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Nazwa arkusza kalkulacyjnego. |
| cellName | [System::String](../../../system/string/) | Odwołanie do komórki w stylu Excel (np. "A1", "C5"). |

### Wartość zwracana

Komórka znajdująca się w określonym miejscu.
## Uwagi



Przykład: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IExcelDataCell](../../iexceldatacell/)
* Klasa [IExcelDataWorkbook](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)