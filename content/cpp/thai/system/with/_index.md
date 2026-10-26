---
title: With()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ทำสำเนาบันทึกอ้างอิงและใช้ functor ตัวเริ่มต้นกับมัน.
type: docs
weight: 2614
url: /th/system/with/
---
## System::With(const SharedPtr\<T\>\&, const A\&) ฟังก์ชัน

ทำสำเนาบันทึกอ้างอิงและใช้ functor ตัวเริ่มต้นกับมัน.

```cpp
template<typename T,typename A> SharedPtr<T> System::With(const SharedPtr<T> &record, const A &initializer)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดของบันทึกที่จะทำสำเนา |
| A | ชนิดของ functor ตัวเริ่มต้น |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| record | const [SharedPtr](../sharedptr/)\<T\>\& | Shared pointer ไปยังอ็อบเจ็กต์ที่จะทำสำเนาและเริ่มต้น |
| initializer | const A\& | functor ตัวเริ่มต้นที่กำลังใช้กับสำเนาบันทึก |

### ค่าที่ส่งกลับ

Shared pointer ไปยังบันทึกที่ทำสำเนา.

## System::With(const T\&, const A\&) ฟังก์ชัน

ทำสำเนาโครงสร้างบันทึกและใช้ functor ตัวเริ่มต้นกับมัน.

```cpp
template<typename T,typename A> T System::With(const T &record, const A &initializer)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดของบันทึกที่จะคัดลอก |
| A | ชนิดของ functor ตัวเริ่มต้น |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| record | const T\& | บันทึกที่จะคัดลอกและเริ่มต้น |
| initializer | const A\& | functor ตัวเริ่มต้นที่กำลังใช้กับบันทึกที่คัดลอก |

### ค่าที่ส่งกลับ

บันทึกที่คัดลอก.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../sharedptr/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)