---
title: ToUpper()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงอักขระที่ระบุเป็นตัวอักษรตัวพิมพ์ใหญ่.
type: docs
weight: 222
url: /th/system/char/toupper/
---
## Char::ToUpper(char_t) method


แปลงอักขระที่ระบุเป็นตัวอักษรตัวพิมพ์ใหญ่.

```cpp
static char_t System::Char::ToUpper(char_t c)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| c | char_t | อักขระที่ต้องการแปลง |

### ค่าที่คืนค่า

อักขระที่ระบุในรูปพิมพ์ใหญ่หากอักขระที่ระบุเป็นตัวอักษรพิมพ์เล็ก, มิฉะนั้น - อักขระที่ระบุ

## Char::ToUpper(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) method


แปลงอักขระที่ระบุเป็นตัวอักษรตัวพิมพ์ใหญ่.

```cpp
static char_t System::Char::ToUpper(char_t c, const SharedPtr<Globalization::CultureInfo> &culture)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| c | char_t | อักขระที่ต้องการแปลง |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | อ็อบเจกต์ที่ให้กฎการแปลงตัวอักษรตามวัฒนธรรมเฉพาะ |

### ค่าที่คืนค่า

อักขระที่ระบุในรูปพิมพ์ใหญ่หากอักขระที่ระบุเป็นตัวอักษรพิมพ์เล็ก, มิฉะนั้น - อักขระที่ระบุ

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* คลาส [Char](../)
* คลาส [CultureInfo](../../../system.globalization/cultureinfo/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)