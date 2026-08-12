---
title: GetWorksheetNames()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ดึงชื่อของแผ่นงานทั้งหมดที่อยู่ในสมุดงาน Excel.
type: docs
weight: 40
url: /th/aspose.slides.excel/iexceldataworkbook/getworksheetnames/
---
## IExcelDataWorkbook::GetWorksheetNames() เมธอด

ดึงชื่อของแผ่นงานทั้งหมดที่อยู่ในสมุดงาน [Excel](../../).

```cpp
virtual System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetWorksheetNames()=0
```

### ค่าที่ส่งคืน

รายการชื่อแผ่นงาน
## หมายเหตุ

ตัวอย่าง:
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetNames = wb->GetWorksheetNames();
for (auto&& name : sheetNames)
{
    System::Console::WriteLine(name);
}
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IList](../../../system.collections.generic/ilist/)
* คลาส [String](../../../system/string/)
* คลาส [IExcelDataWorkbook](../)
* เนมสเปซ [Aspose::Slides::Excel](../../)
* ไลบรารี [Aspose.Slides](../../../)