---
title: Ref()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ مرجعًا إلى كائن DynamicWeakPtr. يستخدمه المترجم عند تمرير معاملات الدالة بالمرجع.
type: docs
weight: 2458
url: /ar/system/ref/
---
## System::Ref(DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\&) دالة

يُنشئ مرجعًا إلى كائن [DynamicWeakPtr](../dynamicweakptr/). يستخدمه المترجم عند تمرير معامل الدالة بالمرجع.

```cpp
template<typename T,SmartPtrMode,unsigned int ...> DynamicWeakPtr<T, trunkMode, weakLeafs...>::Reference System::Ref(DynamicWeakPtr<T, trunkMode, weakLeafs...> &ptr)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العنصر المشار إليه. |
| trunkMode | وضع المؤشر الذكي نفسه. |
| weakLeafs | فهارس معاملات القالب التي يجب استدعاء طريقة SetTemplateWeakPtr لها. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| ptr | [DynamicWeakPtr](../dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\& | المؤشر الذكي لإنشاء مرجع له. |

### قيمة الإرجاع

مرجع المؤشر الذكي.

## System::Ref(T\&) دالة

دالة مساعدة للحصول على مراجع إلى الكائنات. تُستخدم لضمان أن [System::DynamicWeakPtr](../dynamicweakptr/) يحدّث الكائن المشار إليه بعد عمليات الإسناد.

```cpp
template<typename T> T & System::Ref(T &value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع لإنشاء مرجع إليه. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | T\& | القيمة لإنشاء مرجع لها. |

### قيمة الإرجاع

مرجع إلى القيمة التي تم تمريرها إلى هذه الدالة.

## انظر أيضاً

* فئة [DynamicWeakPtr](../dynamicweakptr/)
* مساحة الاسم [System](../)
* مكتبة [Aspose.Slides](../../)