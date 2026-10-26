---
title: ReadOnlySpan
second_title: مرجع API لـ Aspose.Slides للغة C++
description: توجيه للاستخدام داخل فئة Span.
type: docs
weight: 1210
url: /ar/system/readonlyspan/
---
## ReadOnlySpan فئة

Forward to use within [Span](../span/) فئة.

```cpp
template<typename T>class ReadOnlySpan : public System::Details::SpanCore<const T, ReadOnlySpan<T>, Span<T>>
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| T | نوع العناصر في المقاطع. توفر هذه الفئة طريقة آمنة من النوع للعمل مع تسلسلات متجاورة من الكائنات بطريقة قراءة فقط. يمكن استخدامها لتغليف المصفوفات، مصفوفات المكدس، أو المؤشرات الأولية مع الحفاظ على فحص الحدود. الـ [ReadOnlySpan](./) لا تملك الذاكرة التي تشير إليها - إنها مجرد عرض للذاكرة الموجودة. |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [ReadOnlySpan](./readonlyspan/)(const [Span](../span/)\<T\>\&) | ينشئ مقطعًا للقراءة فقط من مقطع عادي. |
| static [ThisType](./) [to_ReadOnlySpan](./to_readonlyspan/)(const typename BaseType::ArrayPtrT\&) | يحول مصفوفة إلى [ReadOnlySpan](./). |

## ملاحظات

يمثل منطقة متجاورة للذاكرة عشوائية تُقرأ فقط.

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)