---
title: IsEmpty()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ตรวจสอบว่าข้อความเป็นค่าว่างหรือไม่.
type: docs
weight: 14
url: /th/system/testtools/isempty/
---
## TestTools::IsEmpty(const System::String\&) เมธอด

ตรวจสอบว่าข้อความเป็นค่าว่างหรือไม่.

```cpp
static bool System::TestTools::IsEmpty(const System::String &str)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) เพื่อตรวจสอบว่ามีค่าเป็นค่าว่างหรือไม่. |

### ค่าที่ส่งกลับ

true หากข้อความเป็นค่าว่าง (ความยาวศูนย์), false ในกรณีอื่น.

## TestTools::IsEmpty(const SharedPtr\<T\>\&) เมธอด

ตรวจสอบว่าคอลเลกชันว่างหรือไม่.

```cpp
template<typename T> static bool System::TestTools::IsEmpty(const SharedPtr<T> &collection)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของคอลเลกชัน. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | คอลเลกชันที่ต้องการตรวจสอบ. |

### ค่าที่ส่งกลับ

true หากคอลเลกชันมีจำนวนสมาชิกเป็นศูนย์, false ในกรณีอื่น.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* คลาส [String](../../string/)
* Struct [TestTools](../)
* เนมสเปซ [System](../../)
* Library [Aspose.Slides](../../../)