---
title: TryParse()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: พยายามแปลงสตริงที่ประกอบด้วยอักขระเดี่ยวเป็นอักขระ UTF-16 ฟังก์ชันจะสำเร็จเฉพาะเมื่อสตริงอินพุตไม่เป็นค่า null และมีความยาวเท่ากับหนึ่งอักขระเท่านั้น.
type: docs
weight: 300
url: /th/system/char/tryparse/
---
## Char::TryParse(const System::String\&, char_t\&) เมธอด

พยายามแปลงสตริงที่ประกอบด้วยอักขระเดียวเป็นอักขระ UTF-16 ฟังก์ชันจะสำเร็จก็ต่อเมื่อสตริงอินพุตไม่เป็นค่า null และมีความยาวเท่ากับหนึ่งอักขระเท่านั้น.

```cpp
static bool System::Char::TryParse(const System::String &s, char_t &result)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| s | const [System::String](../../string/)\& | [String](../../string/) เพื่อแปลง |
| result | char_t\& | ตัวแปรผลลัพธ์ที่จะเก็บค่าที่ได้จากการแปลงหากการแปลงสำเร็จ |

### ค่าที่คืน

True หากการแปลงสำเร็จ, มิฉะนั้น - false

## ดูเพิ่มเติม

* คลาส [String](../../string/)
* คลาส [Char](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)