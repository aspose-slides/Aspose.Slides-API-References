---
title: operator!=()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ตัวดำเนินการเปรียบเทียบไม่เท่ากัน.
type: docs
weight: 313
url: /th/system/string/operator_not_equal/
---
## String::operator!=(const String\&) const เมธอด

ตัวดำเนินการเปรียบเทียบไม่เท่ากัน.

```cpp
bool System::String::operator!=(const String &str) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) เพื่อเปรียบเทียบกับอ็อบเจ็กต์ปัจจุบัน |

### ค่าที่คืน

false หากสตริงทั้งสองเป็น null หรือทั้งสองไม่เป็น null และตรงกัน, true หากไม่เป็นเช่นนั้น.

## String::operator!=(std::nullptr_t) const เมธอด

ตรวจสอบว่า string ไม่เป็น null. ใช้ตรรกะเดียวกับการเรียก [IsNull()](../isnull/).

```cpp
bool System::String::operator!=(std::nullptr_t) const
```

### ค่าที่คืน

false หากสตริงเป็น null, true หากไม่เป็นเช่นนั้น.

## ดูเพิ่มเติม

* คลาส [String](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)