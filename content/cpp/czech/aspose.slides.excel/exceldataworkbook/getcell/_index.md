---
title: GetCell()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Načte buňku ze specifikovaného listu pomocí jejího indexu a souřadnic buňky.
type: docs
weight: 27
url: /cs/aspose.slides.excel/exceldataworkbook/getcell/
---
## ExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) metoda


Retrieves a cell from the specified worksheet using its index and cell coordinates.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Zero-based index of the worksheet. |
| row | **int32_t** | Zero-based row index of the cell. |
| column | **int32_t** | Zero-based column index of the cell. |

### Návratová hodnota

The cell at the specified location.
## Poznámky



Příklad: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) metoda


Retrieves a cell from the specified worksheet using its name and cell coordinates.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | The name of the worksheet. |
| row | **int32_t** | Zero-based row index of the cell. |
| column | **int32_t** | Zero-based column index of the cell. |

### Návratová hodnota

The cell at the specified location.
## Poznámky



Příklad: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(int32_t, System::String) metoda


Retrieves a cell from the specified worksheet using its index and Excel-style cell name (e.g., "B2").

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Zero-based index of the worksheet. |
| cellName | [System::String](../../../system/string/) | The Excel-style cell reference (e.g., "A1", "C5"). |

### Návratová hodnota

The cell at the specified location.
## Poznámky



Příklad: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, System::String) metoda


Retrieves a cell from the specified worksheet using Excel-style cell name (e.g., "B2").

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | The name of the worksheet. |
| cellName | [System::String](../../../system/string/) | The Excel-style cell reference (e.g., "A1", "C5"). |

### Návratová hodnota

The cell at the specified location.
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
* Třída [ExcelDataWorkbook](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides::Excel](../../)
* Knihovna [Aspose.Slides](../../../)