---
title: PrintToString()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: พิมพ์อ็อบเจ็กต์เป็นสตริงโดยเลือกฟังก์ชันซีเรียลไลเซอร์ที่เหมาะสม.
type: docs
weight: 1
url: /th/system.testpredicates.details/printtostring/
---
## System::TestPredicates::Details::PrintToString(const T\&) ฟังก์ชัน

พิมพ์อ็อบเจ็กต์เป็นสตริงโดยเลือกฟังก์ชันซีเรียลไลเซอร์ที่เหมาะสม.

```cpp
template<typename T> std::enable_if_t<!TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | [Object](../../system/object/) ชนิด. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) เพื่อพิมพ์. |

### ค่าที่ส่งกลับ

[String](../../system/string/) การแสดงผลของอ็อบเจ็กต์ที่ส่งผ่านมา.

## System::TestPredicates::Details::PrintToString(const T\&) ฟังก์ชัน

พิมพ์คอนเทนเนอร์แบบ ICollection ไปเป็นสตริงโดยพิมพ์องค์ประกอบของพวกมัน (ไม่เกิน 32).

```cpp
template<typename T> std::enable_if_t<TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | [Object](../../system/object/) ชนิด. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) เพื่อพิมพ์. |

### ค่าที่ส่งกลับ

การแสดงผลสตริงรวมขององค์ประกอบที่บรรจุอยู่.

## System::TestPredicates::Details::PrintToString(std::nullptr_t) ฟังก์ชัน

พิมพ์ nullptr ไปเป็นสตริง.

```cpp
std::string System::TestPredicates::Details::PrintToString(std::nullptr_t)
```

### ค่าที่ส่งกลับ

\"nullptr\" สตริง.

## System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable\<bool\>\&) ฟังก์ชัน

พิมพ์คอลเลกชัน [IEnumerable<bool>](../../system.collections.generic/ienumerable/) ไปเป็นสตริงโดยพิมพ์องค์ประกอบของพวกมัน (ไม่เกิน 32).

```cpp
std::string System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable<bool> &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | [Object](../../system/object/) ชนิด. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<**bool**\>\& | [Object](../../system/object/) เพื่อพิมพ์. |

### ค่าที่ส่งกลับ

การแสดงผลสตริงรวมขององค์ประกอบที่บรรจุอยู่.

## ดูเพิ่มเติม

* คลาส [IEnumerable](../../system.collections.generic/ienumerable/)
* โครงสร้าง [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* เนมสเปซ [System::TestPredicates::Details](../)
* ไลบรารี [Aspose.Slides](../../)