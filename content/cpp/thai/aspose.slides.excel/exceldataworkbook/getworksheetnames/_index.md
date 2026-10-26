---
title: GetWorksheetNames()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ดึงชื่อของแผ่นงานทั้งหมดที่อยู่ในสมุดงาน Excel.
type: docs
weight: 53
url: /th/aspose.slides.excel/exceldataworkbook/getworksheetnames/
---
## ExcelDataWorkbook::GetWorksheetNames() เมธอด


ดึงชื่อของแผ่นงานทั้งหมดที่อยู่ในสมุดงาน [Excel](../../).

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetWorksheetNames() override
```


### ค่าที่คืน

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
* คลาส [ExcelDataWorkbook](../)
* เนมสเปซ [Aspose::Slides::Excel](../../)
* ไลบรารี [Aspose.Slides](../../../)