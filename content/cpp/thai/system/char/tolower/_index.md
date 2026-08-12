---
title: ToLower()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: แปลงอักขระที่ระบุให้เป็นตัวพิมพ์เล็ก
type: docs
weight: 235
url: /th/system/char/tolower/
---
## Char::ToLower(char_t) เมธอด

แปลงอักขระที่ระบุให้เป็นตัวพิมพ์เล็ก

```cpp
static char_t System::Char::ToLower(char_t c)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| c | char_t | อักขระที่ต้องการแปลง |

### ค่าที่ส่งคืน

อักขระที่ระบุในรูปตัวพิมพ์เล็ก หากอักขระที่ระบุเป็นอักษรตัวพิมพ์ใหญ่ มิฉะนั้นคืออักขระที่ระบุ

## Char::ToLower(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) เมธอด

แปลงอักขระที่ระบุให้เป็นตัวพิมพ์เล็ก

```cpp
static char_t System::Char::ToLower(char_t c, const SharedPtr<Globalization::CultureInfo> &culture)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| c | char_t | อักขระที่ต้องการแปลง |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | อ็อบเจ็กต์ที่จัดหากฎการแปลงตัวอักษรตามวัฒนธรรม |

### ค่าที่ส่งคืน

อักขระที่ระบุในรูปตัวพิมพ์เล็ก หากอักขระที่ระบุเป็นอักษรตัวพิมพ์ใหญ่ มิฉะนั้นคืออักขระที่ระบุ

## ดูเพิ่มเติม

* กำหนดชนิด [SharedPtr](../../sharedptr/)
* คลาส [Char](../)
* คลาส [CultureInfo](../../../system.globalization/cultureinfo/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)