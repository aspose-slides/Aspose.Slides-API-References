---
title: Fallback()
second_title: Aspose.Slides لمرجع API C++
description: ينفّذ إجراء الرجوع الفعلي.
type: docs
weight: 14
url: /ar/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) طريقة

ينفّذ إجراء الرجوع الفعلي.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| charUnknown | char_t | مُشفّر الأحرف يفشل في الترميز. |
| index | int | [Index](../../../system/index/) من الحرف الذي تسبب في الخطأ. |

### قيمة الإرجاع

True إذا عالجت الذاكرة المؤقتة الأحرف غير المعروفة، false إذا تجاهلتها.

## EncoderFallbackBuffer::Fallback(char_t, char_t, int) طريقة

ينفّذ إجراء الرجوع الفعلي.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| charUnknownHigh | char_t | الجزء العلوي من زوج البدائل الذي سبب الخطأ. |
| charUnknownLow | char_t | الجزء السفلي من زوج البدائل الذي سبب الخطأ. |
| index | int | [Index](../../../system/index/) من الحرف الذي تسبب في الخطأ. |

### قيمة الإرجاع

True إذا عالجت الذاكرة المؤقتة الأحرف غير المعروفة، false إذا تجاهلتها.

## أنظر أيضًا

* فئة [EncoderFallbackBuffer](../)
* مساحة الأسماء [System::Text](../../)
* مكتبة [Aspose.Slides](../../../)