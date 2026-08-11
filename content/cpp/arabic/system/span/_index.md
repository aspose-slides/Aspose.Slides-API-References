---
title: Span
second_title: Aspose.Slides لمرجع واجهة برمجة تطبيقات C++
description: "يمثل منطقة متصلة من الذاكرة العشوائية مشابهة لـ std::span في C++20."
type: docs
weight: 1262
url: /ar/system/span/
---
## فئة Span

يمثل منطقة متصلة من الذاكرة العشوائية مماثلة لـ std::span في C++20.

```cpp
template<typename T>class Span : public System::Details::SpanCore<T, Span<T>, Span<T>>
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T | نوع العناصر في الـ span. توفر هذه الفئة طريقة آمنة من النوع للعمل مع تسلسلات متصلة من الكائنات. يمكن استخدامها لتغليف المصفوفات، أو مصفوفات المكدس، أو المؤشرات الخام مع الحفاظ على فحص الحدود. الـ [Span](./) لا يملك الذاكرة التي يشير إليها - إنه مجرد عرض للذاكرة الموجودة. |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| void [Clear](./clear/)() const | يمسح محتويات الـ span بتعيين جميع العناصر إلى القيمة الافتراضية. |
| void [Fill](./fill/)(const T\&) const | يملأ الـ span بالقيمة المحددة. |
| static [ThisType](./) [to_Span](./to_span/)(const typename BaseType::ArrayPtrT\&) | يحول مصفوفة إلى [Span](./). |

## انظر أيضاً

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)