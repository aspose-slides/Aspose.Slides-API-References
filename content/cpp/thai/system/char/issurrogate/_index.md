---
title: IsSurrogate()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: กำหนดว่าตัวอักษรที่ระบุเป็นหน่วยโค้ดเซอร์รอกเรตแบบ UTF-16 หรือไม่
type: docs
weight: 14
url: /th/system/char/issurrogate/
---
## Char::IsSurrogate(char_t) เมธอด


กำหนดว่าตัวอักษรที่ระบุเป็นหน่วยโค้ดเซอร์รอกเรตแบบ UTF-16 หรือไม่

```cpp
static bool System::Char::IsSurrogate(char_t c)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| c | char_t | ตัวอักษร |

### ค่าที่คืนกลับ

จริง หากตัวอักษรที่ระบุเป็นหน่วยโค้ดเซอร์รอกเรตแบบ UTF-16, มิฉะนั้น - เท็จ

## Char::IsSurrogate(const String\&, int) เมธอด


กำหนดว่าตัวอักษรที่ตำแหน่งที่ระบุในสตริงที่ระบุเป็นหน่วยโค้ดเซอร์รอกเรตแบบ UTF-16 หรือไม่

```cpp
static bool System::Char::IsSurrogate(const String &s, int index)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| s | const [String](../../string/)\& | สตริง |
| index | int | ดัชนีของตัวอักษรในสตริงที่ระบุ |

### ค่าที่คืนกลับ

จริง หากตัวอักษรที่ตำแหน่งที่ระบุเป็นหน่วยโค้ดเซอร์รอกเรตแบบ UTF-16, มิฉะนั้น - เท็จ

## ดูเพิ่มเติม

* คลาส [Char](../)
* คลาส [String](../../string/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)