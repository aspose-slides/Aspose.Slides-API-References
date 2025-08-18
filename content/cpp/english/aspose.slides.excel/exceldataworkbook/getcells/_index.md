---
title: GetCells()
second_title: Aspose.Slides for C++ API Reference
description: Retrieves a collection of cells from the workbook that match the specified formula.
type: docs
weight: 14
url: /aspose.slides.excel/exceldataworkbook/getcells/
---
## ExcelDataWorkbook::GetCells(System::String, bool) method


Retrieves a collection of cells from the workbook that match the specified formula.

```cpp
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::ExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | A formula or range expression (e.g., \"Sheet1!A1:B3\") used to identify target cells. |
| skipHiddenCells | **bool** | If **true**, hidden cells (e.g., in hidden rows or columns) will be excluded from the result. |

### Return Value

A read-only list of cells that match the specified formula.
## Remarks



Example: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* Class [IExcelDataCell](../../iexceldatacell/)
* Class [String](../../../system/string/)
* Class [ExcelDataWorkbook](../)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)