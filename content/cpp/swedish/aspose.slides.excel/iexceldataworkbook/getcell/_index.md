---
title: GetCell()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar en cell från det angivna arbetsbladet med hjälp av dess index och cellkoordinater.
type: docs
weight: 14
url: /sv/aspose.slides.excel/iexceldataworkbook/getcell/
---
## IExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) metod

Hämtar en cell från det angivna arbetsbladet med hjälp av dess index och cellkoordinater.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Nollbaserat index för arbetsbladet. |
| row | **int32_t** | Nollbaserat radindex för cellen. |
| column | **int32_t** | Nollbaserat kolumnindex för cellen. |

### Returvärde

Cellen på den angivna platsen.
## Anmärkningar



Exempel: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) metod

Hämtar en cell från det angivna arbetsbladet med hjälp av dess namn och cellkoordinater.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Namnet på arbetsbladet. |
| row | **int32_t** | Nollbaserat radindex för cellen. |
| column | **int32_t** | Nollbaserat kolumnindex för cellen. |

### Returvärde

Cellen på den angivna platsen.
## Anmärkningar



Exempel: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(int32_t, System::String) metod

Hämtar en cell från det angivna arbetsbladet med hjälp av dess index och Excel-formatets cellnamn (t.ex. "B2").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Nollbaserat index för arbetsbladet. |
| cellName | [System::String](../../../system/string/) | Excel-formatets cellreferens (t.ex. "A1", "C5"). |

### Returvärde

Cellen på den angivna platsen.
## Anmärkningar



Exempel: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, System::String) metod

Hämtar en cell från det angivna arbetsbladet med hjälp av Excel-formatets cellnamn (t.ex. "B2").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Namnet på arbetsbladet. |
| cellName | [System::String](../../../system/string/) | Excel-formatets cellreferens (t.ex. "A1", "C5"). |

### Returvärde

Cellen på den angivna platsen.
## Anmärkningar



Exempel: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IExcelDataCell](../../iexceldatacell/)
* Klass [IExcelDataWorkbook](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::Excel](../../)
* Bibliotek [Aspose.Slides](../../../)