---
title: operator==()
second_title: مرجع API Aspose.Slides للـ C++
description: يقارن زوجي مفتاح-قيمة باستخدام دلالات 'equals'. يستخدم operator == أو طريقة EqualsTo لكلا المفتاحين والقيم، أيهما معرف.
type: docs
weight: 690
url: /ar/system.collections.generic/operator_equal_equal/
---
## System::Collections::Generic::operator==(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) دالة

يقارن زوجي مفتاح-قيمة باستخدام معاني 'equals'. يستخدم العملية operator == أو الطريقة EqualsTo لكلا المفتاحين والقيم، أيهما معرف.

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator==(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TKey | نوع المفتاح. |
| TValue | نوع القيمة. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| left | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | المعامل الأيسر. |
| right | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | المعامل الأيمن. |

### قيمة الإرجاع

صحيح إذا كان كلا المفتاحين والقيم متطابقة، خطأ خلاف ذلك.

## انظر أيضًا

* الفئة [KeyValuePair](../keyvaluepair/)
* مساحة الاسم [System::Collections::Generic](../)
* المكتبة [Aspose.Slides](../../)