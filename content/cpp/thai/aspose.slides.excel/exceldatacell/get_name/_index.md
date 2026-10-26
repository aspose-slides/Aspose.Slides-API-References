---
title: get_Name()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รับชื่อของเซลล์ข้อมูลแผนภูมิ.
type: docs
weight: 14
url: /th/aspose.slides.excel/exceldatacell/get_name/
---
## ExcelDataCell::get_Name() เมธอด

รับชื่อของเซลล์ข้อมูลแผนภูมิ

```cpp
System::String Aspose::Slides::Excel::ExcelDataCell::get_Name() override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```


## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [ExcelDataCell](../)
* เนมสเปซ [Aspose::Slides::Excel](../../)
* ไลบรารี [Aspose.Slides](../../../)