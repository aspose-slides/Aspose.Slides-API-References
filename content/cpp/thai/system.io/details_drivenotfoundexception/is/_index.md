---
title: Is()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 27
url: /th/system.io/details_drivenotfoundexception/is/
---
## Details_DriveNotFoundException::Is(const System::TypeInfo\&) const method

```cpp
bool System::IO::Details_DriveNotFoundException::Is(const System::TypeInfo &target) const override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) โครงสร้างที่อธิบายประเภทเพื่อทดสอบวัตถุตรงกับปัจจุบัน |

### ค่าที่คืนกลับ

จริงถ้าวัตถุเป็นประเภทที่กำหนดหรือคลาสย่อยของมัน, มิฉะนั้นเป็นเท็จ.

## หมายเหตุ

ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นการเทียบเท่าของตัวดำเนินการ 'is' ของ C#.

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../../system/typeinfo/)
* คลาส [Details_DriveNotFoundException](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)