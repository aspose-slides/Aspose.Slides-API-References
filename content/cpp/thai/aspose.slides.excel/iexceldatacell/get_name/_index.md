---
title: get_Name()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: "รับชื่อของเซลล์ข้อมูลแผนภูมิ. อ่านอย่างเดียว System::String."
type: docs
weight: 14
url: /th/aspose.slides.excel/iexceldatacell/get_name/
---
## IExcelDataCell::get_Name() method

รับชื่อของเซลล์ข้อมูล chart. อ่านอย่างเดียว [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Excel::IExcelDataCell::get_Name()=0
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
* คลาส [IExcelDataCell](../)
* เนมส페ซ [Aspose::Slides::Excel](../../)
* ไลบรารี [Aspose.Slides](../../../)