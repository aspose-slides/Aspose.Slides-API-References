---
title: PrintToStringImpl()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يطبع الفئة الفرعية System::Object إلى سلسلة باستخدام طريقة ToString()."
type: docs
weight: 14
url: /ar/system.testpredicates.details/printtostringimpl/
---
## System::TestPredicates::Details::PrintToStringImpl(const SharedPtr\<T\>\&, long long) دالة


يطبع الفئة الفرعية [System::Object](../../system/object/) إلى سلسلة باستخدام طريقة ToString().

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const SharedPtr<T> &value, long long s)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع الفئة النهائية. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [SharedPtr](../../system/sharedptr/)\<T\>\& | مؤشر إلى الكائن للطباعة. |
| s | long long | معامل خدمة يستخدم كمحدد لتجاوز الدالة بناءً على نوع هذا المعامل؛ يتم تجاهل قيمة المعامل |

### قيمة الإرجاع

تمثيل [String](../../system/string/) للكائن الممرّر أو "nullptr"، إذا كانت **value** فارغة.

## System::TestPredicates::Details::PrintToStringImpl(const WeakPtr\<T\>\&, long long) دالة


يطبع الفئة الفرعية [System::Object](../../system/object/) إلى سلسلة باستخدام طريقة ToString().

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const WeakPtr<T> &value, long long s)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع الفئة النهائية. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [WeakPtr](../../system/weakptr/)\<T\>\& | مؤشر إلى الكائن للطباعة. |
| s | long long | معامل خدمة يستخدم كمحدد لتجاوز الدالة بناءً على نوع هذا المعامل؛ يتم تجاهل قيمة المعامل |

### قيمة الإرجاع

تمثيل [String](../../system/string/) للكائن الممرّر أو "nullptr"، إذا كانت **value** فارغة.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) دالة


يطبع الكائن إلى سلسلة باستخدام طريقة ToString().

```cpp
template<typename T> std::enable_if<!TypeTraits::has_print_to_method<T>::value &&System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) للطباعة. |
| s | long long | معامل خدمة يستخدم كمحدد لتجاوز الدالة بناءً على نوع هذا المعامل؛ يتم تجاهل قيمة المعامل |

### قيمة الإرجاع

تمثيل [String](../../system/string/) للكائن الممرّر.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) دالة


يطبع الكائن إلى سلسلة باستخدام طريقة PrintTo.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&!TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) للطباعة. |
| s | long long | معامل خدمة يستخدم كمحدد لتجاوز الدالة بناءً على نوع هذا المعامل؛ يتم تجاهل قيمة المعامل |

### قيمة الإرجاع

تمثيل [String](../../system/string/) للكائن الممرّر.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) دالة


يطبع الكائن إلى سلسلة باستخدام طريقة PrintTo.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) للطباعة. |
| s | long long | معامل خدمة يستخدم كمحدد لتجاوز الدالة بناءً على نوع هذا المعامل؛ يتم تجاهل قيمة المعامل |

### قيمة الإرجاع

تمثيل [String](../../system/string/) للكائن الممرّر.

## System::TestPredicates::Details::PrintToStringImpl(const std::pair\<T1, T2\>\&, long long) دالة


يطبع الزوج إلى سلسلة.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const std::pair<T1, T2> &value, long long s)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | معامل نوع الزوج الأول. |
| T2 | معامل نوع الزوج الثاني. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const std::pair\<T1, T2\>\& | [Object](../../system/object/) للطباعة. |
| s | long long | معامل خدمة يستخدم كمحدد لتجاوز الدالة بناءً على نوع هذا المعامل؛ يتم تجاهل قيمة المعامل |

### قيمة الإرجاع

تمثيلات سلسلة مشتركة لكل من مكوّنات الزوج الأول والثاني.

## System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair\<T1, T2\>\&, long long) دالة


يطبع الزوج إلى سلسلة.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair<T1, T2> &value, long long s)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | معامل نوع الزوج الأول. |
| T2 | معامل نوع الزوج الثاني. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<T1, T2\>\& | [Object](../../system/object/) للطباعة. |
| s | long long | معامل خدمة يستخدم كمحدد لتجاوز الدالة بناءً على نوع هذا المعامل؛ يتم تجاهل قيمة المعامل |

### قيمة الإرجاع

تمثيلات سلسلة مشتركة لكل من مكوّنات الزوج الأول والثاني.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) دالة


يطبع الحاويات على نمط STL إلى سلسلة عن طريق طباعة عناصرها (ليس أكثر من 32).

```cpp
template<typename T> std::enable_if<TypeTraits::IsCppContainer<T>::value &&!std::is_base_of<Object, T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &container, long long s)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| container | const T\& | [Object](../../system/object/) للطباعة. |
| s | long long | معامل خدمة يستخدم كمحدد لتجاوز الدالة بناءً على نوع هذا المعامل؛ يتم تجاهل قيمة المعامل |

### قيمة الإرجاع

تمثيلات سلسلة مشتركة للعناصر المحتواة.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, int) دالة


يطبع الأنواع الأخرى إلى سلسلة باستخدام الدوال التي يوفرها gtest.

```cpp
template<typename T> std::string System::TestPredicates::Details::PrintToStringImpl(const T &value, int s)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) للطباعة. |
| s | int | معامل خدمة يستخدم كمحدد لتجاوز الدالة بناءً على نوع هذا المعامل؛ يتم تجاهل قيمة المعامل |

### قيمة الإرجاع

تمثيلات [String](../../system/string/) للكائن الممرّر.

## انظر أيضًا

* Typedef [SharedPtr](../../system/sharedptr/)
* فئة [WeakPtr](../../system/weakptr/)
* فئة [KeyValuePair](../../system.collections.generic/keyvaluepair/)
* فئة [Object](../../system/object/)
* Struct [has_print_to_method](../../system.testpredicates.typetraits/has_print_to_method/)
* Struct [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Struct [IsCppContainer](../../system.testpredicates.typetraits/iscppcontainer/)
* مساحة الاسم [System::TestPredicates::Details](../)
* Library [Aspose.Slides](../../)