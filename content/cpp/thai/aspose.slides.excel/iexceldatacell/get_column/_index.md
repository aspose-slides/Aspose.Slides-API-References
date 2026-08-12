---
title: get_Column()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: รับดัชนีตั้งแต่ศูนย์ของคอลัมน์ในแผ่นงานที่เซลล์ตั้งอยู่ อ่านอย่างเดียว int32_t.
type: docs
weight: 40
url: /th/aspose.slides.excel/iexceldatacell/get_column/
---
## IExcelDataCell::get_Column() เมธอด

รับดัชนีตั้งแต่ศูนย์ของคอลัมน์ในแผ่นงานที่เซลล์ตั้งอยู่ อ่านอย่างเดียว **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Column()=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## ดูเพิ่มเติม

* คลาส [IExcelDataCell](../)
* เนมส페ซ [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)