---
title: Fallback()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: จัดการการล้มเหลวของการเข้ารหัส.
type: docs
weight: 27
url: /th/system.text/encoderexceptionfallbackbuffer/fallback/
---
## EncoderExceptionFallbackBuffer::Fallback(char_t, int) เมธอด

จัดการการล้มเหลวของการเข้ารหัส.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### หน่วยรับค่า

| Parameter | Type | Description |
| --- | --- | --- |
| charUnknown | char_t | อักขระที่ไม่รู้จัก; เพิกเฉย. |
| index | int | ค่าออฟเซ็ตของอักขระที่ไม่รู้จัก; เพิกเฉย. |

### ค่าที่ส่งกลับ

จะไม่คืนค่าเลยจริง ๆ จะโยนข้อยกเว้นแทน.

## EncoderExceptionFallbackBuffer::Fallback(char_t, char_t, int) เมธอด

จัดการการล้มเหลวของการเข้ารหัส.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### หน่วยรับค่า

| Parameter | Type | Description |
| --- | --- | --- |
| charUnknownHigh | char_t | ส่วนสูงของคู่ surrogate ที่ทำให้เกิดข้อผิดพลาด. |
| charUnknownLow | char_t | ส่วนต่ำของคู่ surrogate ที่ทำให้เกิดข้อผิดพลาด. |
| index | int | ค่าออฟเซ็ตของอักขระที่ไม่รู้จัก; เพิกเฉย. |

### ค่าที่ส่งกลับ

จะไม่คืนค่าเลยจริง ๆ จะโยนข้อยกเว้นแทน.

## ดูเพิ่มเติม

* คลาส [EncoderExceptionFallbackBuffer](../)
* เนมสเปซ [System::Text](../../)
* ไลบรารี [Aspose.Slides](../../../)