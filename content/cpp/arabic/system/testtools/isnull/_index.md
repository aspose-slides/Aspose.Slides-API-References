---
title: IsNull()
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة C++
description: يتحقق مما إذا كانت القيمة المحددة فارغة. نسخة للأنواع العددية وأنواع التعداد.
type: docs
weight: 1
url: /ar/system/testtools/isnull/
---
## TestTools::IsNull(T) طريقة

يتحقق مما إذا كانت القيمة المحددة فارغة. [Version](../../version/) للأنواع العددية وأنواع التعداد.

```cpp
template<typename T> static std::enable_if<std::is_arithmetic<T>::value||std::is_enum<T>::value, bool>::type System::TestTools::IsNull(T obj)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع القيمة التي يتم فحصها. |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | T | القيمة للتحقق من كونها فارغة. |

### قيمة الإرجاع

دائمًا ما تُعيد false.

## TestTools::IsNull(const T&) طريقة

يتحقق مما إذا كانت القيمة المحددة فارغة. [Version](../../version/) للأنواع غير العددية وغير أنوع التعداد.

```cpp
template<typename T> static std::enable_if<!std::is_arithmetic<T>::value &&!std::is_enum<T>::value, bool>::type System::TestTools::IsNull(const T &obj)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع القيمة التي يتم فحصها. |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const T& | القيمة للتحقق من كونها فارغة. |

### قيمة الإرجاع

True إذا تمت مقارنة الكائن بـ nullptr كصحيح، وإلا false.

## TestTools::IsNull(const SharedPtr\<T\>\&) طريقة

يتحقق مما إذا كانت القيمة المحددة فارغة. [Version](../../version/) للأنواع غير العددية.

```cpp
template<typename T> static bool System::TestTools::IsNull(const SharedPtr<T> &obj)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع القيمة التي يتم فحصها. |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<T\>\& | القيمة للتحقق من كونها فارغة. |

### قيمة الإرجاع

True إذا تمت مقارنة الكائن بـ nullptr كصحيح، وإلا false.

## TestTools::IsNull(System::Collections::Generic::KeyValuePair\<K, V\>\&) طريقة

يتحقق مما إذا كانت القيمة المحددة فارغة. [Version](../../version/) لأزواج المفتاح والقيمة.

```cpp
template<typename K,typename V> static bool System::TestTools::IsNull(System::Collections::Generic::KeyValuePair<K, V> &kvp)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| K | نوع المفتاح. |
| V | نوع القيمة. |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| kvp | [System::Collections::Generic::KeyValuePair](../../../system.collections.generic/keyvaluepair/)\<K, V\>\& | كائن الزوج. |

### قيمة الإرجاع

True إذا كان الزوج يعتبر فارغًا، وإلا false.

## TestTools::IsNull(const System::String&) طريقة

يتحقق مما إذا كان السلسلة فارغة.

```cpp
static bool System::TestTools::IsNull(const System::String &str)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) للتحقق. |

### قيمة الإرجاع

True إذا كان السلسلة يعتبر فارغًا، وإلا false.

## انظر أيضا

* Typedef [SharedPtr](../../sharedptr/)
* الفئة [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* الفئة [String](../../string/)
* بنية [TestTools](../)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)