---
title: GetCell()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar en cell från det angivna arbetsbladet med dess index och cellkoordinater.
type: docs
weight: 27
url: /sv/aspose.slides.excel/exceldataworkbook/getcell/
---
## ExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) metod


Hämtar en cell från det angivna arbetsbladet med dess index och cellkoordinater.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
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

## ExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) metod


Hämtar en cell från det angivna arbetsbladet med dess namn och cellkoordinater.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
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

## ExcelDataWorkbook::GetCell(int32_t, System::String) metod


Hämtar en cell från det angivna arbetsbladet med dess index och Excel-liknande cellnamn (t.ex. "B2").

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Nollbaserat index för arbetsbladet. |
| cellName | [System::String](../../../system/string/) | Excel-liknande cellreferens (t.ex. "A1", "C5"). |

### Returvärde

Cellen på den angivna platsen.
## Anmärkningar



Exempel: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, System::String) metod


Hämtar en cell från det angivna arbetsbladet med Excel-liknande cellnamn (t.ex. "B2").

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Namnet på arbetsbladet. |
| cellName | [System::String](../../../system/string/) | Excel-liknande cellreferens (t.ex. "A1", "C5"). |

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
* Klass [ExcelDataWorkbook](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)