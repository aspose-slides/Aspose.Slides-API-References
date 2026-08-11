---
title: Fallback()
second_title: مرجع API Aspose.Slides للغة C++
description: يتعامل مع فشل الترميز.
type: docs
weight: 27
url: /ar/system.text/encoderreplacementfallbackbuffer/fallback/
---
## EncoderReplacementFallbackBuffer::Fallback(char_t, int) طريقة

يتعامل مع فشل الترميز.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| charUnknown | char_t | حرف غير معروف؛ يتم تجاهله. |
| index | int | موضع الحرف غير المعروف؛ يتم تجاهله. |

### قيمة الإرجاع

صحيح إذا تم توفير سلسلة الاستبدال وكانت غير فارغة، وإلا خطأ.

## EncoderReplacementFallbackBuffer::Fallback(char_t, char_t, int) طريقة

يتعامل مع فشل الترميز.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| charUnknownHigh | char_t | الجزء العلوي من الزوج البديل الذي تسبب بالخطأ. |
| charUnknownLow | char_t | الجزء السفلي من الزوج البديل الذي تسبب بالخطأ. |
| index | int | موضع الحرف غير المعروف؛ يتم تجاهله. |

### قيمة الإرجاع

صحيح إذا تم توفير سلسلة الاستبدال وكانت غير فارغة، وإلا خطأ.

## انظر أيضًا

* الفئة [EncoderReplacementFallbackBuffer](../)
* النطاق [System::Text](../../)
* المكتبة [Aspose.Slides](../../../)