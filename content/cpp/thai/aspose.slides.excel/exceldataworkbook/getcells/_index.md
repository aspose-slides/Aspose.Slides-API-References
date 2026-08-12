---
title: GetCells()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ดึงคอลเลกชันของเซลล์จากเวิร์กบุ๊กที่ตรงกับสูตรที่ระบุ
type: docs
weight: 14
url: /th/aspose.slides.excel/exceldataworkbook/getcells/
---
## ExcelDataWorkbook::GetCells(System::String, bool) เมธอด

ดึงคอลเลกชันของเซลล์จากเวิร์กบุ๊กที่ตรงกับสูตรที่ระบุ

```cpp
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::ExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | สูตรหรือการแสดงช่วง (เช่น \"Sheet1!A1:B3\") ที่ใช้ระบุเซลล์เป้าหมาย |
| skipHiddenCells | **bool** | หาก **true**, เซลล์ที่ซ่อนอยู่ (เช่นในแถวหรือคอลัมน์ที่ซ่อน) จะไม่รวมอยู่ในผลลัพธ์ |

### ค่าที่ส่งกลับ

รายการเซลล์แบบอ่านอย่างเดียวที่ตรงกับสูตรที่ระบุ

## หมายเหตุ

ตัวอย่าง: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* คลาส [IExcelDataCell](../../iexceldatacell/)
* คลาส [String](../../../system/string/)
* คลาส [ExcelDataWorkbook](../)
* เนมสเปซ [Aspose::Slides::Excel](../../)
* ไลบรารี [Aspose.Slides](../../../)