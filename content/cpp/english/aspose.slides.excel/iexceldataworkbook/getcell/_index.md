---
title: GetCell()
second_title: Aspose.Slides for C++ API Reference
description: Retrieves a cell from the specified worksheet using its index and cell coordinates.
type: docs
weight: 14
url: /aspose.slides.excel/iexceldataworkbook/getcell/
---
## IExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) method


Retrieves a cell from the specified worksheet using its index and cell coordinates.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Zero-based index of the worksheet. |
| row | **int32_t** | Zero-based row index of the cell. |
| column | **int32_t** | Zero-based column index of the cell. |

### Return Value

The cell at the specified location.
## Remarks



Example: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) method


Retrieves a cell from the specified worksheet using its name and cell coordinates.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | The name of the worksheet. |
| row | **int32_t** | Zero-based row index of the cell. |
| column | **int32_t** | Zero-based column index of the cell. |

### Return Value

The cell at the specified location.
## Remarks



Example: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(int32_t, System::String) method


Retrieves a cell from the specified worksheet using its index and Excel-style cell name (e.g., \"B2\").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Zero-based index of the worksheet. |
| cellName | [System::String](../../../system/string/) | The Excel-style cell reference (e.g., \"A1\", \"C5\"). |

### Return Value

The cell at the specified location.
## Remarks



Example: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, System::String) method


Retrieves a cell from the specified worksheet using Excel-style cell name (e.g., \"B2\").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | The name of the worksheet. |
| cellName | [System::String](../../../system/string/) | The Excel-style cell reference (e.g., \"A1\", \"C5\"). |

### Return Value

The cell at the specified location.
## Remarks



Example: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IExcelDataCell](../../iexceldatacell/)
* Class [IExcelDataWorkbook](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)