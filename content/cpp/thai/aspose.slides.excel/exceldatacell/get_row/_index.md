---
title: get_Row()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับดัชนีที่เริ่มจากศูนย์ของแถวในแผ่นงานที่เซลล์ตั้งอยู่ อ่านอย่างเดียว int32_t.
type: docs
weight: 27
url: /th/aspose.slides.excel/exceldatacell/get_row/
---
## ExcelDataCell::get_Row() เมธอด

รับดัชนีที่เริ่มต้นจากศูนย์ของแถวในแผ่นงานที่เซลล์ตั้งอยู่ อ่านอย่างเดียว **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Row() override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```




## ดูเพิ่มเติม

* คลาส [ExcelDataCell](../)
* เนมสเปซ [Aspose::Slides::Excel](../../)
* ไลบรารี [Aspose.Slides](../../../)