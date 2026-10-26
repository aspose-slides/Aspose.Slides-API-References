---
title: GetCells()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ดึงคอลเลกชันของเซลล์จาก workbook ที่ตรงกับสูตรที่ระบุ.
type: docs
weight: 1
url: /th/aspose.slides.excel/iexceldataworkbook/getcells/
---
## IExcelDataWorkbook::GetCells(System::String, bool) method


ดึงคอลเลกชันของเซลล์จาก workbook ที่ตรงกับสูตรที่ระบุ.

```cpp
virtual System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::IExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | สูตรหรือการแสดงช่วง (เช่น \"Sheet1!A1:B3\") ที่ใช้เพื่อระบุเซลล์เป้าหมาย. |
| skipHiddenCells | **bool** | หาก **true**, เซลล์ที่ซ่อนอยู่ (เช่น ในแถวหรือคอลัมน์ที่ซ่อน) จะถูกตัดออกจากผลลัพธ์. |

### ค่าที่คืนกลับ

รายการเซลล์แบบอ่านอย่างเดียวที่ตรงกับสูตรที่ระบุ.
## หมายเหตุ



ตัวอย่าง: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* Class [IExcelDataCell](../../iexceldatacell/)
* Class [String](../../../system/string/)
* Class [IExcelDataWorkbook](../)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)