---
title: ArrayInitializerCast()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: แปลงค่าพื้นฐานของอาเรย์ (ซึ่ง C# ทำโดยอัตโนมัติแต่ C++ ดูเหมือนจะไม่ทำ)
type: docs
weight: 209
url: /th/system/objectext/arrayinitializercast/
---
## ObjectExt::ArrayInitializerCast(From ...) เมธอด


แปลงค่าพื้นฐานของอาเรย์ (ซึ่ง C# ทำโดยอัตโนมัติแต่ C++ ดูเหมือนจะไม่ทำ).

```cpp
template<typename To,typename ...> static std::enable_if<(std::is_fundamental<To>::value), std::array<To, sizeof...(From)>>::type System::ObjectExt::ArrayInitializerCast(From ...args)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| To | ประเภทเป้าหมาย. |
| From | ประเภทแหล่งที่มา. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| args | From ... | ค่าที่จะทำการแปลงและผลักเข้าสู่อาเรย์เป้าหมาย. |

### ค่าที่ส่งกลับ

[Array](../../array/) ที่มีสำเนาที่แปลงแล้วของอาร์กิวเมนต์ทั้งหมดในลำดับเดียวกัน.

## ดูเพิ่มเติม

* คลาส [ObjectExt](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)