---
title: Default()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คืนค่าอ้างอิงไปยังอินสแตนซ์ที่สร้างค่าเริ่มต้นโดยอัตโนมัติหนึ่งตัวของชนิดข้อยกเว้น
type: docs
weight: 2224
url: /th/system/default/
---
## System::Default() ฟังก์ชัน

คืนค่าอ้างอิงไปยังอินสแตนซ์ที่สร้างค่าเริ่มต้นโดยอัตโนมัติหนึ่งตัวของชนิดข้อยกเว้น

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทที่ส่งกลับอินสแตนซ์ |

## System::Default() ฟังก์ชัน

คืนค่าอ้างอิงไปยังอินสแตนซ์ที่สร้างค่าเริ่มต้นโดยอัตโนมัติหนึ่งตัวของชนิดที่ไม่ใช่ข้อยกเว้น

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทที่ส่งกลับอินสแตนซ์ |

## ดูเพิ่มเติม

* โครงสร้าง [IsExceptionWrapper](../isexceptionwrapper/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)