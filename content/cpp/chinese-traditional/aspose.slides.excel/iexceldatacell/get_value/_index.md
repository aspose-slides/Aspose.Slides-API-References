---
title: get_Value()
second_title: Aspose.Slides for C++ API 參考文件
description: "取得 Excel 單元格中包含的值。唯讀 System::Object."
type: docs
weight: 1
url: /zh-hant/aspose.slides.excel/iexceldatacell/get_value/
---
## IExcelDataCell::get_Value() 方法

取得 [Excel](../../) 單元格中包含的值。唯讀 [System::Object](../../../system/object/)。

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Excel::IExcelDataCell::get_Value()=0
```

## 備註

範例：
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```




## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [IExcelDataCell](../)
* 命名空間 [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)