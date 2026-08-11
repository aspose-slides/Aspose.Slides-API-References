---
title: operator<<()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides for C++
description: إدراج البيانات في الدفق باستخدام ترميز UTF-8.
type: docs
weight: 716
url: /ar/system.collections.generic/operator_less_less/
---
## System::Collections::Generic::operator<<(std::ostream\&, const KeyValuePair\<TKey, TValue\>\&) دالة

إدراج البيانات في الدفق باستخدام ترميز UTF-8.

```cpp
template<typename TKey,typename TValue> std::ostream & System::Collections::Generic::operator<<(std::ostream &stream, const KeyValuePair<TKey, TValue> &pair)
```

### معاملـات القالب

| المعامل | الوصف |
| --- | --- |
| TKey | نوع المفتاح. |
| TValue | نوع القيمة. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | std::ostream\& | دفق الإخراج لإدراج البيانات إليه. |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) للإدراج. |

### قيمة الإرجاع

**stream**.

## System::Collections::Generic::operator<<(std::wostream\&, const KeyValuePair\<TKey, TValue\>\&) دالة

إدراج البيانات في الدفق.

```cpp
template<typename TKey,typename TValue> std::wostream & System::Collections::Generic::operator<<(std::wostream &stream, const KeyValuePair<TKey, TValue> &pair)
```

### معاملـات القالب

| المعامل | الوصف |
| --- | --- |
| TKey | نوع المفتاح. |
| TValue | نوع القيمة. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | std::wostream\& | دفق الإخراج لإدراج البيانات إليه. |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) للإدراج. |

### قيمة الإرجاع

**stream**.

## انظر أيضًا

* Class [KeyValuePair](../keyvaluepair/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)