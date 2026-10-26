---
title: get_Row()
second_title: Aspose.Slides برای مرجع API C++
description: دریافت ایندکس صفر مبنا از ردیف در ورق کاری که سلول در آن قرار دارد. فقط-خواندنی int32_t.
type: docs
weight: 27
url: /fa/aspose.slides.excel/exceldatacell/get_row/
---
## ExcelDataCell::get_Row() متد


دریافت مقدار ایندکس صفر مبنا از ردیف در ورق کاری که سلول در آن قرار دارد. فقط-خواندنی **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Row() override
```

## توضیحات


مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```




## موارد مرتبط

* کلاس [ExcelDataCell](../)
* فضای نام [Aspose::Slides::Excel](../../)
* کتابخانه [Aspose.Slides](../../../)