---
title: get_Value()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得 Excel 儲存格中包含的值。
type: docs
weight: 1
url: /zh-hant/aspose.slides.excel/exceldatacell/get_value/
---
## ExcelDataCell::get_Value() 方法


取得 [Excel](../../) 儲存格中包含的值。

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Excel::ExcelDataCell::get_Value() override
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
* 類別 [ExcelDataCell](../)
* 命名空間 [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)