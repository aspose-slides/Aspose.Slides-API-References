---
title: get_Value()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: รับค่าที่บรรจุอยู่ในเซลล์ Excel.
type: docs
weight: 1
url: /th/aspose.slides.excel/exceldatacell/get_value/
---
## ExcelDataCell::get_Value() เมธอด


รับค่าที่บรรจุอยู่ในเซลล์ [Excel](../../).

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Excel::ExcelDataCell::get_Value() override
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
* คลาส [ExcelDataCell](../)
* เนมสเปซ [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)