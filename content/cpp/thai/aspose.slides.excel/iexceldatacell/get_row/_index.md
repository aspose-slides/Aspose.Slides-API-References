---
title: get_Row()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รับดัชนีแถวที่เริ่มจากศูนย์ในแผ่นงานที่เซลล์อยู่. อ่านอย่างเดียว int32_t.
type: docs
weight: 27
url: /th/aspose.slides.excel/iexceldatacell/get_row/
---
## IExcelDataCell::get_Row() เมธอด

รับดัชนีแถวที่เริ่มจากศูนย์ในแผ่นงานที่เซลล์อยู่. อ่านอย่างเดียว **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Row()=0
```

## หมายเหตุ

ตัวอย่าง: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```

## ดูเพิ่มเติม

* คลาส [IExcelDataCell](../)
* เนมส페ซ [Aspose::Slides::Excel](../../)
* ไลบรารี [Aspose.Slides](../../../)