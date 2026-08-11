---
title: ComparerType
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقارن العناصر باستخدام دلالة 'less'.
type: docs
weight: 144
url: /ar/system.collections.generic.details/comparertype/
---
## ComparerType هيكل

يقارن العناصر باستخدام دلالة 'less'.

```cpp
template<typename T>class ComparerType
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر المقارنة. |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | يقارن أنواع القيمة التي تنفّذ واجهة [IComparable](../../system/icomparable/). |
| std::enable_if<\!(std::is_base_of\<[IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value)&&\!std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | يقارن أنواع القيمة الأولية والكائنات التي لا تنفّذ واجهة [IComparable](../../system/icomparable/). |
| std::enable_if\<std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | يقارن أنواع النقطة العائمة. |

## انظر أيضًا

* مساحة الأسماء [System::Collections::Generic::Details](../)
* مكتبة [Aspose.Slides](../../)