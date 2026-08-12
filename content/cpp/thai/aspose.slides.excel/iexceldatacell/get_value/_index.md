---
title: get_Value()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "ดึงค่าที่อยู่ในเซลล์ Excel. อ่านอย่างเดียว System::Object."
type: docs
weight: 1
url: /th/aspose.slides.excel/iexceldatacell/get_value/
---
## IExcelDataCell::get_Value() method

ดึงค่าที่อยู่ในเซลล์ [Excel](../../). อ่านอย่างเดียว [System::Object](../../../system/object/).

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Excel::IExcelDataCell::get_Value()=0
```

## หมายเหตุ

ตัวอย่าง:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [IExcelDataCell](../)
* เนมสเปซ [Aspose::Slides::Excel](../../)
* ไลบรารี [Aspose.Slides](../../../)