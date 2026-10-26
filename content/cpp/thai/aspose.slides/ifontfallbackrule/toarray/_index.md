---
title: ToArray()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างและคืนค่าอาเรย์ที่มีฟอนต์ FallBack ทั้งหมดสำหรับกฎนี้.
type: docs
weight: 105
url: /th/aspose.slides/ifontfallbackrule/toarray/
---
## IFontFallBackRule::ToArray() เมธอด

สร้างและคืนค่าอาเรย์ที่มีแบบอักษร FallBack ทั้งหมดสำหรับกฎนี้.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray()=0
```

### ค่าที่ส่งคืน

อาเรย์ของ [System::String](../../../system/string/)
## หมายเหตุ



```cpp
// สร้างกฎที่มีรายชื่อแบบอักษร.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// ดึงชื่อแบบอักษรทั้งหมดเป็นอาเรย์
ArrayPtr<String> fontNames = newRule->ToArray();
```

## IFontFallBackRule::ToArray(int32_t, int32_t) เมธอด

สร้างและคืนค่าอาเรย์ที่มีแบบอักษร FallBack ทั้งหมดจากช่วงที่ระบุในรายการ.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray(int32_t startIndex, int32_t count)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| startIndex | **int32_t** | ดัชนีของแบบอักษรแรกที่ต้องการเพิ่ม. |
| count | **int32_t** | จำนวนแบบอักษรที่ต้องการเพิ่ม. |

### ค่าที่ส่งคืน

อาเรย์ของ [System::String](../../../system/string/)
## หมายเหตุ



```cpp
// สร้างกฎที่มีรายการแบบอักษร.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//ดึงชื่อแบบอักษรสองตัวสุดท้ายเป็นอาเรย์
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```

## ดูเพิ่มเติม

* การกำหนดประเภท [ArrayPtr](../../../system/arrayptr/)
* คลาส [String](../../../system/string/)
* คลาส [IFontFallBackRule](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)