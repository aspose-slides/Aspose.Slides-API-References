---
title: GetCell()
second_title: Aspose.Slides pro C++ – reference API
description: Načte buňku ze zadaného listu pomocí jeho indexu a souřadnic buňky.
type: docs
weight: 14
url: /cs/aspose.slides.excel/iexceldataworkbook/getcell/
---
## IExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) metoda


Načte buňku ze zadaného listu pomocí jeho indexu a souřadnic buňky.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index listu začínající od nuly. |
| row | **int32_t** | Index řádku buňky začínající od nuly. |
| column | **int32_t** | Index sloupce buňky začínající od nuly. |

### Návratová hodnota

Buňka na určeném místě.
## Poznámky



Příklad: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) metoda


Načte buňku ze zadaného listu pomocí jeho názvu a souřadnic buňky.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Název listu. |
| row | **int32_t** | Index řádku buňky začínající od nuly. |
| column | **int32_t** | Index sloupce buňky začínající od nuly. |

### Návratová hodnota

Buňka na určeném místě.
## Poznámky



Příklad: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(int32_t, System::String) metoda


Načte buňku ze zadaného listu pomocí jeho indexu a názvu buňky ve stylu Excel (např. "B2").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index listu začínající od nuly. |
| cellName | [System::String](../../../system/string/) | Odkaz na buňku ve stylu Excel (např. "A1", "C5"). |

### Návratová hodnota

Buňka na určeném místě.
## Poznámky



Příklad: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, System::String) metoda


Načte buňku ze zadaného listu pomocí názvu buňky ve stylu Excel (např. "B2").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Název listu. |
| cellName | [System::String](../../../system/string/) | Odkaz na buňku ve stylu Excel (např. "A1", "C5"). |

### Návratová hodnota

Buňka na určeném místě.
## Poznámky



Příklad: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IExcelDataCell](../../iexceldatacell/)
* Třída [IExcelDataWorkbook](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)