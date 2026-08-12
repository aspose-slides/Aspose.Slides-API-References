---
title: ToByteArray()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: แปลงสตริงหรือส่วนย่อยของสตริงเป็นอาร์เรย์ของไบต์.
type: docs
weight: 508
url: /th/system/string/tobytearray/
---
## String::ToByteArray(int32_t, int32_t, bool) const เมธอด

แปลงสตริงหรือส่วนย่อยของสตริงเป็นอาร์เรย์ของไบต์.

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=1) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| startIndex | **int32_t** | ดัชนีเริ่มต้นของส่วนย่อย |
| length | **int32_t** | ความยาวของส่วนย่อย |
| LE | **bool** | ถ้าเป็นจริง, เข้ารหัสอักขระโดยใช้ลิเทิลเอ็นดิแอนน์; มิฉะนั้น, ใช้บิ๊กเอ็นดิแอนน์ |

### ค่าที่คืน

[Array](../../array/) ซึ่งประกอบด้วยไบต์ที่แสดงอักขระของสตริง.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* คลาส [String](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)