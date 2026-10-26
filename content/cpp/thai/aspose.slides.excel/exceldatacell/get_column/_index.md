---
title: get_Column()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: ดึงดัชนีที่เริ่มจากศูนย์ของคอลัมน์ในเวิร์กชีตที่เซลล์ตั้งอยู่. อ่านอย่างเดียว int32_t.
type: docs
weight: 40
url: /th/aspose.slides.excel/exceldatacell/get_column/
---
## ExcelDataCell::get_Column() เมธอด


ดึงค่าดัชนีที่เริ่มจากศูนย์ของคอลัมน์ในเวิร์กชีตที่เซลล์ตั้งอยู่. อ่านอย่างเดียว **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Column() override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## ดูเพิ่มเติม

* คลาส [ExcelDataCell](../)
* เนมสเปซ [Aspose::Slides::Excel](../../)
* ไลบรารี [Aspose.Slides](../../../)