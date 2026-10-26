---
title: Fallback()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: จัดการข้อผิดพลาดการเข้ารหัส.
type: docs
weight: 27
url: /th/system.text/encoderreplacementfallbackbuffer/fallback/
---
## EncoderReplacementFallbackBuffer::Fallback(char_t, int) เมธอด


จัดการข้อผิดพลาดการเข้ารหัส.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknown, int index) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| charUnknown | char_t | อักขระที่ไม่รู้จัก; ถูกละเลย. |
| index | int | ตำแหน่งอักขระที่ไม่รู้จัก; ถูกละเลย. |

### ค่าที่ส่งกลับ

True หากมีสตริงการแทนที่และไม่เป็นค่าว่าง, false หากไม่เป็นเช่นนั้น.

## EncoderReplacementFallbackBuffer::Fallback(char_t, char_t, int) เมธอด


จัดการข้อผิดพลาดการเข้ารหัส.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| charUnknownHigh | char_t | ส่วนบนของคู่ surrogate ที่ทำให้เกิดข้อผิดพลาด. |
| charUnknownLow | char_t | ส่วนล่างของคู่ surrogate ที่ทำให้เกิดข้อผิดพลาด. |
| index | int | ตำแหน่งอักขระที่ไม่รู้จัก; ถูกละเลย. |

### ค่าที่ส่งกลับ

True หากมีสตริงการแทนที่และไม่เป็นค่าว่าง, false หากไม่เป็นเช่นนั้น.

## ดูเพิ่มเติม

* คลาส [EncoderReplacementFallbackBuffer](../)
* เนมสเปซ [System::Text](../../)
* ไลบรารี [Aspose.Slides](../../../)