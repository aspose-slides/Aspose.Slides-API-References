---
title: ToArray()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างและคืนค่าอาร์เรย์ที่มีแบบอักษร FallBack ทั้งหมดสำหรับกฎนี้.
type: docs
weight: 144
url: /th/aspose.slides/fontfallbackrule/toarray/
---
## FontFallBackRule::ToArray() เมธอด


สร้างและคืนค่าอาร์เรย์ที่มีแบบอักษร FallBack ทั้งหมดสำหรับกฎนี้.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray() override
```


### ค่าที่ส่งคืน

อาร์เรย์ของ [System::String](../../../system/string/)
## หมายเหตุ



```cpp
// สร้างกฎที่บรรจุรายการแบบอักษร.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// รับชื่อแบบอักษรทั้งหมดเป็นอาร์เรย์.
ArrayPtr<String> fontNames = newRule->ToArray();
```


## FontFallBackRule::ToArray(int32_t, int32_t) เมธอด


สร้างและคืนค่าอาร์เรย์ที่มีแบบอักษร FallBack ทั้งหมดจากช่วงที่ระบุในรายการ.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray(int32_t startIndex, int32_t count) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| startIndex | **int32_t** | ดัชนีของแบบอักษรแรกที่ต้องเพิ่ม. |
| count | **int32_t** | จำนวนแบบอักษรที่ต้องเพิ่ม. |

### ค่าที่ส่งคืน

อาร์เรย์ของ [System::String](../../../system/string/)
## หมายเหตุ



```cpp
// สร้างกฎที่บรรจุรายการแบบอักษร.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// รับชื่อแบบอักษรสองตัวสุดท้ายเป็นอาร์เรย์.
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```


## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [String](../../../system/string/)
* คลาส [FontFallBackRule](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)