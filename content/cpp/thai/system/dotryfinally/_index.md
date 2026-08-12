---
title: DoTryFinally()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ฟังก์ชันเดียวที่จำลองพฤติกรรมของคำสั่ง try[-catch]-finally ของ C#. ในระหว่างการแปลคำสั่ง try[-catch]-finally ของ C# ด้วยตัวเลือกของตัวแปลที่ตั้งค่า finally_statement_as_lambda เป็น true คำสั่งจะถูกแปลงเป็นการเรียกเมธอดนี้
type: docs
weight: 2445
url: /th/system/dotryfinally/
---
## System::DoTryFinally(T\&&, F\&&) ฟังก์ชัน

ฟังก์ชันเดียวที่จำลองพฤติกรรมของคำสั่ง try[-catch]-finally ของ C#. ในระหว่างการแปลคำสั่ง try[-catch]-finally ของ C# ด้วยตัวเลือกของตัวแปลที่ตั้งค่า finally_statement_as_lambda เป็น true คำสั่งจะถูกแปลงเป็นการเรียกเมธอดนี้

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_void<T>::value> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของอ็อบเจ็กต์ฟังก์ชันที่ทำหน้าที่เป็นส่วน try[-catch] ของคำสั่ง try[-catch]-finally ที่กำลังจำลอง |
| F | ประเภทของอ็อบเจ็กต์ฟังก์ชันที่ทำหน้าที่เป็นส่วน finally ของคำสั่ง try[-catch]-finally ที่กำลังจำลอง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| tryBlock | T\&& | อ็อบเจ็กต์ฟังก์ชันที่ส่วนเนื้อหามีการทำงานของส่วน try[-catch] ของคำสั่ง try[-catch]-finally ที่กำลังจำลอง |
| finallyBlock | F\&& | อ็อบเจ็กต์ฟังก์ชันที่ส่วนเนื้อหามีการทำงานของส่วน finally ของคำสั่ง try[-catch]-finally ที่กำลังจำลอง |

## System::DoTryFinally(T\&&, F\&&) ฟังก์ชัน

ฟังก์ชันเดียวที่จำลองพฤติกรรมของคำสั่ง try[-catch]-finally ของ C#. ในระหว่างการแปลคำสั่ง try[-catch]-finally ของ C# ด้วยตัวเลือกของตัวแปลที่ตั้งค่า finally_statement_as_lambda เป็น true คำสั่งจะถูกแปลงเป็นการเรียกเมธอดนี้ ตัวโอเวอร์โหลดนี้จัดการกรณีที่ค่าที่ส่งคืนจากอ็อบเจ็กต์ฟังก์ชันที่ทำหน้าที่เป็นส่วน try[-catch] ของคำสั่ง try[-catch]-finally เป็น bool

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_boolref<T>::value, bool> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของอ็อบเจ็กต์ฟังก์ชันที่ทำหน้าที่เป็นส่วน try[-catch] ของคำสั่ง try[-catch]-finally ที่กำลังจำลอง |
| F | ประเภทของอ็อบเจ็กต์ฟังก์ชันที่ทำหน้าที่เป็นส่วน finally ของคำสั่ง try[-catch]-finally ที่กำลังจำลอง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| tryBlock | T\&& | อ็อบเจ็กต์ฟังก์ชันที่ส่วนเนื้อหามีการทำงานของส่วน try[-catch] ของคำสั่ง try[-catch]-finally ที่กำลังจำลอง |
| finallyBlock | F\&& | อ็อบเจ็กต์ฟังก์ชันที่ส่วนเนื้อหามีการทำงานของส่วน finally ของคำสั่ง try[-catch]-finally ที่กำลังจำลอง |

## System::DoTryFinally(T\&&, F\&&) ฟังก์ชัน

ฟังก์ชันเดียวที่จำลองพฤติกรรมของคำสั่ง try[-catch]-finally ของ C#. ในระหว่างการแปลคำสั่ง try[-catch]-finally ของ C# ด้วยตัวเลือกของตัวแปลที่ตั้งค่า finally_statement_as_lambda เป็น true คำสั่งจะถูกแปลงเป็นการเรียกเมธอดนี้ ตัวโอเวอร์โหลดนี้จัดการกรณีที่ค่าที่ส่งคืนจากอ็อบเจ็กต์ฟังก์ชันที่ทำหน้าที่เป็นส่วน try[-catch] ของคำสั่ง try[-catch]-finally เป็น bool&

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_nonovoid_boolref<T>::value, std::optional<Details::ResultOf<T, bool &>>> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของอ็อบเจ็กต์ฟังก์ชันที่ทำหน้าที่เป็นส่วน try[-catch] ของคำสั่ง try[-catch]-finally ที่กำลังจำลอง |
| F | ประเภทของอ็อบเจ็กต์ฟังก์ชันที่ทำหน้าที่เป็นส่วน finally ของคำสั่ง try[-catch]-finally ที่กำลังจำลอง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| tryBlock | T\&& | อ็อบเจ็กต์ฟังก์ชันที่ส่วนเนื้อหามีการทำงานของส่วน try[-catch] ของคำสั่ง try[-catch]-finally ที่กำลังจำลอง |
| finallyBlock | F\&& | อ็อบเจ็กต์ฟังก์ชันที่ส่วนเนื้อหามีการทำงานของส่วน finally ของคำสั่ง try[-catch]-finally ที่กำลังจำลอง |

## ดูเพิ่มเติม

* Namespace [System](../)
* Library [Aspose.Slides](../../)