---
title: Fallback()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: ดำเนินการขั้นตอน fallback จริง.
type: docs
weight: 14
url: /th/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) เมธอด

Implements actual fallback procedure.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| charUnknown | char_t | ตัวเข้ารหัสอักขระไม่สามารถเข้ารหัสได้. |
| index | int | [Index](../../../system/index/) ของอักขระที่ทำให้เกิดข้อผิดพลาด. |

### ค่าที่ส่งกลับ

True หากบัฟเฟอร์ประมวลผลอักขระที่ไม่รู้จัก, false หากบัฟเฟอร์ละเลย.

## EncoderFallbackBuffer::Fallback(char_t, char_t, int) เมธอด

Implements actual fallback procedure.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| charUnknownHigh | char_t | ส่วนสูงของคู่ surrogate ที่ทำให้เกิดข้อผิดพลาด. |
| charUnknownLow | char_t | ส่วนต่ำของคู่ surrogate ที่ทำให้เกิดข้อผิดพลาด. |
| index | int | [Index](../../../system/index/) ของอักขระที่ทำให้เกิดข้อผิดพลาด. |

### ค่าที่ส่งกลับ

True หากบัฟเฟอร์ประมวลผลอักขระที่ไม่รู้จัก, false หากบัฟเฟอร์ละเลย.

## ดูเพิ่มเติม

* คลาส [EncoderFallbackBuffer](../)
* เนมสเปซ [System::Text](../../)
* ไลบรารี [Aspose.Slides](../../../)