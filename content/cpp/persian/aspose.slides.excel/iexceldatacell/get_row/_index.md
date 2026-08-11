---
title: get_Row()
second_title: مرجع API Aspose.Slides برای C++
description: اندیس صفر مبنا ردیف در کاربرگی که سلول در آن قرار دارد را بر می‌گرداند. فقط-خواندنی int32_t.
type: docs
weight: 27
url: /fa/aspose.slides.excel/iexceldatacell/get_row/
---
## IExcelDataCell::get_Row() متد

دستگاه صفر مبنا ایندکس ردیف در کاربرگ که سلول در آن قرار دارد را بر می‌گرداند. فقط-خواندنی **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Row()=0
```

## توضیحات

مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```




## مراجعه

* کلاس [IExcelDataCell](../)
* فضای‌نام [Aspose::Slides::Excel](../../)
* کتابخانه [Aspose.Slides](../../../)