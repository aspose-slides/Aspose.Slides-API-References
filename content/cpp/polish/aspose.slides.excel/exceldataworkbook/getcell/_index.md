---
title: GetCell()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Pobiera komórkę z określonego arkusza, używając jego indeksu i współrzędnych komórki.
type: docs
weight: 27
url: /pl/aspose.slides.excel/exceldataworkbook/getcell/
---
## ExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) metoda

Pobiera komórkę z określonego arkusza, używając jego indeksu i współrzędnych komórki.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Indeks zerowy arkusza. |
| row | **int32_t** | Indeks zerowy wiersza komórki. |
| column | **int32_t** | Indeks zerowy kolumny komórki. |

### Wartość zwracana

Komórka w określonej lokalizacji.

## Uwagi



Przykład: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) metoda

Pobiera komórkę z określonego arkusza, używając jego nazwy i współrzędnych komórki.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Nazwa arkusza. |
| row | **int32_t** | Indeks zerowy wiersza komórki. |
| column | **int32_t** | Indeks zerowy kolumny komórki. |

### Wartość zwracana

Komórka w określonej lokalizacji.

## Uwagi



Przykład: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(int32_t, System::String) metoda

Pobiera komórkę z określonego arkusza, używając jego indeksu i nazwy komórki w stylu Excel (np. "B2").

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Indeks zerowy arkusza. |
| cellName | [System::String](../../../system/string/) | Odwołanie do komórki w stylu Excel (np. "A1", "C5"). |

### Wartość zwracana

Komórka w określonej lokalizacji.

## Uwagi



Przykład: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, System::String) metoda

Pobiera komórkę z określonego arkusza, używając nazwy komórki w stylu Excel (np. "B2").

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Nazwa arkusza. |
| cellName | [System::String](../../../system/string/) | Odwołanie do komórki w stylu Excel (np. "A1", "C5"). |

### Wartość zwracana

Komórka w określonej lokalizacji.

## Uwagi



Przykład: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## Zobacz też

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IExcelDataCell](../../iexceldatacell/)
* Klasa [ExcelDataWorkbook](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::Excel](../../)
* Biblioteka [Aspose.Slides](../../../)