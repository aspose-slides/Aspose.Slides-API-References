---
title: Equals()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقارن الكائنات باستخدام سلوكيات C# Object.Equals.
type: docs
weight: 157
url: /ar/system/object/equals/
---
## Object::Equals(ptr) الطريقة

Compares objects using C# [Object.Equals](./) semantics.

```cpp
virtual bool System::Object::Equals(ptr obj)
```

### Arguments

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | [ptr](../ptr/) | [Object](../) لمقارنة الكائن الحالي به. |

### قيمة الإرجاع

صحيح إذا تم اعتبار الكائنات متساوية وإلا خطأ.

## Object::Equals(T1 const&, T2 const&) الطريقة

Compares reference type objects in C# style.

```cpp
template<typename T1,typename T2> static std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | Type of first object to compare. |
| T2 | Type of second object to compare. |

### Arguments

| المعامل | النوع | الوصف |
| --- | --- | --- |
| objA | T1 const& | First object to compare. |
| objB | T2 const& | Second object to compare. |

### قيمة الإرجاع

صحيح إذا تطابقت الكائنات إما بالمرجع أو دلاليًا (بمقارنة شبيهة بـ [Object.Equals](./))، وإلا خطأ.

## Object::Equals(T1 const&, T2 const&) الطريقة

Compares value type objects in C# style.

```cpp
template<typename T1,typename T2> static std::enable_if<!IsSmartPtr<T1>::value &&!IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | Type of first object to compare. |
| T2 | Type of second object to compare. |

### Arguments

| المعامل | النوع | الوصف |
| --- | --- | --- |
| objA | T1 const& | First object to compare. |
| objB | T2 const& | Second object to compare. |

### قيمة الإرجاع

صحيح إذا اعتُبرت الكائنات متساوية باستخدام عامل المساواة المتاح، وإلا خطأ.

## Object::Equals(float const&, float const&) الطريقة

Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN.

```cpp
bool System::Object::Equals(float const &objA, float const &objB)
```

### Arguments

| المعامل | النوع | الوصف |
| --- | --- | --- |
| objA | **float** const& | قيمة نقطة عائمة على الجانب الأيسر. |
| objB | **float** const& | قيمة نقطة عائمة على الجانب الأيمن. |

### قيمة الإرجاع

صحيح إذا كان **objA** و **objB** كلاهما NaN أو متساويين، وإلا خطأ.

## Object::Equals(double const&, double const&) الطريقة

Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN.

```cpp
bool System::Object::Equals(double const &objA, double const &objB)
```

### Arguments

| المعامل | النوع | الوصف |
| --- | --- | --- |
| objA | **double** const& | قيمة نقطة عائمة على الجانب الأيسر. |
| objB | **double** const& | قيمة نقطة عائمة على الجانب الأيمن. |

### قيمة الإرجاع

صحيح إذا كان **objA** و **objB** كلاهما NaN أو متساويين، وإلا خطأ.

## انظر أيضًا

* Typedef [ptr](../ptr/)
* الفئة [Object](../)
* Struct [IsSmartPtr](../../issmartptr/)
* النطاق [System](../../)
* Library [Aspose.Slides](../../../)