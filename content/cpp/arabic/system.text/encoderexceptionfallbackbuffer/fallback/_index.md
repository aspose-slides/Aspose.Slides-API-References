---
title: Fallback()
second_title: Aspose.Slides لمرجع API الخاص بـ C++
description: يتعامل مع فشل التشفير.
type: docs
weight: 27
url: /ar/system.text/encoderexceptionfallbackbuffer/fallback/
---
## EncoderExceptionFallbackBuffer::Fallback(char_t, int) طريقة

يتعامل مع فشل التشفير.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| charUnknown | char_t | الأحرف غير المعروفة؛ تم تجاهلها. |
| index | int | إزاحة الأحرف غير المعروفة؛ تم تجاهلها. |

### قيمة الإرجاع

لا تُعيد أبداً فعليًا، بل ترمي استثناءً بدلاً من ذلك.

## EncoderExceptionFallbackBuffer::Fallback(char_t, char_t, int) طريقة

يتعامل مع فشل التشفير.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| charUnknownHigh | char_t | الجزء العلوي من زوج الاستبدال الذي تسبب في الخطأ. |
| charUnknownLow | char_t | الجزء السفلي من زوج الاستبدال الذي تسبب في الخطأ. |
| index | int | إزاحة الحرف غير المعروف؛ تم تجاهلها. |

### قيمة الإرجاع

لا تُعيد أبداً فعليًا، بل ترمي استثناءً بدلاً من ذلك.

## انظر أيضًا

* الفئة [EncoderExceptionFallbackBuffer](../)
* النطاق [System::Text](../../)
* المكتبة [Aspose.Slides](../../../)