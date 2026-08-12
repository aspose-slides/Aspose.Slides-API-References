---
title: TryParse()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: พยายามแปลงสตริงที่ระบุให้เป็นค่าคงที่ enum ที่เทียบเท่า.
type: docs
weight: 79
url: /th/system/enum/tryparse/
---
## Enum::TryParse(const String\&, E\&) เมธอด

พยายามแปลงสตริงที่ระบุให้เป็นค่าคงที่ enum ที่เทียบเท่า

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, E &result)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) ที่ถูกตีความว่าเป็นชื่อของค่าคงที่ enum |
| result | E\& | พารามิเตอร์ผลลัพธ์ที่หากการแปลงสำเร็จจะมีผลลัพธ์ของการแปลงในฟังก์ชัน |

### ค่าที่ส่งกลับ

True หากการแปลงสำเร็จ, มิฉะนั้น - false

## Enum::TryParse(const String\&, bool, E\&) เมธอด

พยายามแปลงสตริงที่ระบุให้เป็นค่าคงที่ enum ที่เทียบเท่า

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, bool ignoreCase, E &result)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) ที่ถูกตีความว่าเป็นชื่อของค่าคงที่ enum |
| ignoreCase | **bool** | ระบุว่าควรเพิกเฉยต่อการแยกตัวพิมพ์ใหญ่/เล็กหรือไม่เมื่อตีความสตริง |
| result | E\& | พารามิเตอร์ผลลัพธ์ที่หากการแปลงสำเร็จจะมีผลลัพธ์ของการแปลงในค่าที่ฟังก์ชันส่งกลับ |

### ค่าที่ส่งกลับ

True หากการแปลงสำเร็จ, มิฉะนั้น - false

## ดูเพิ่มเติม

* คลาส [String](../../string/)
* โครงสร้าง [Enum](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)