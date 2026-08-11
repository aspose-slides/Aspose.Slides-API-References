---
title: ReferenceEquals()
second_title: Aspose.Slides لمرجع API الخاص بـ C++
description: "تخصيص لـ Object::ReferenceEquals للحالة الخاصة بالسلسلة و nullptr."
type: docs
weight: 261
url: /ar/system/object/referenceequals/
---
## Object::ReferenceEquals(String const\&, std::nullptr_t) طريقة


تخصيص لـ [Object::ReferenceEquals](./) للحالة الخاصة بالسلسلة و nullptr.

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | [String](../../string/) const\& | [String](../../string/) للمقارنة مع nullptr. |

### قيمة الإرجاع

صحيح إذا كانت السلسلة فارغة، خطأ غير ذلك.

## Object::ReferenceEquals(String const\&, String const\&) طريقة


تخصيص لـ [Object::ReferenceEquals](./) للحالة الخاصة بالسلاسل.

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str1 | [String](../../string/) const\& | السلسلة الأولى للمقارنة. |
| str2 | [String](../../string/) const\& | السلسلة الثانية للمقارنة. |

### قيمة الإرجاع

صحيح إذا كانت السلاسل متطابقة، خطأ غير ذلك.

## Object::ReferenceEquals(ptr const\&, ptr const\&) طريقة


يقارن الكائنات حسب المرجع.

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| objA | [ptr](../ptr/) const\& | المؤشر الأول للمقارنة. |
| objB | [ptr](../ptr/) const\& | المؤشر الثاني للمقارنة. |

### قيمة الإرجاع

صحيح إذا كانت المؤشرات متطابقة وخطأ غير ذلك.

## Object::ReferenceEquals(T const\&, T const\&) طريقة


يقارن الكائنات حسب المرجع.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع الكائنات للمقارنة. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| objA | T const\& | الكائن الأول للمقارنة. |
| objB | T const\& | الكائن الثاني للمقارنة. |

### قيمة الإرجاع

صحيح إذا كانت عناوين الكائنات متطابقة وخطأ غير ذلك.

## Object::ReferenceEquals(T const\&, std::nullptr_t) طريقة


يقارن مرجعياً كائن النوع القيمي مع nullptr.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع الكائن للمقارنة. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| objA | T const\& | الكائن الأول للمقارنة. |

### قيمة الإرجاع

دائمًا تُعيد خطأ لأن الأنواع القيمية لا يمكن أن تكون فارغة.

## انظر أيضًا

* Typedef [ptr](../ptr/)
* Class [String](../../string/)
* Class [Object](../)
* Struct [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)