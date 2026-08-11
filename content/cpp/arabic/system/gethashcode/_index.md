---
title: GetHashCode()
second_title: Aspose.Slides للـ C++ – مرجع API
description: يرجم رمز تجزئة للقيمة العددية المحددة.
type: docs
weight: 2484
url: /ar/system/gethashcode/
---
## System::GetHashCode(const T\&) function


يرجع رمز تجزئة للقيمة العددية المحددة.

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع القيمة التي تُولّد الدالة رمز التجزئة لها |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const T\& | القيمة التي تُولّد رمز التجزئة لها |

### قيمة الإرجاع

رمز التجزئة المولّد للقيمة المحددة

## System::GetHashCode(const T\&) function


يرجع رمز تجزئة للكائن المحدد.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع الكائن الذي تُولّد الدالة رمز التجزئة له |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const T\& | الـ [SmartPtr](../smartptr/) الذي يشير إلى الكائن الذي تُولّد رمز التجزئة له |

### قيمة الإرجاع

رمز التجزئة المولّد للكائن المحدد

## System::GetHashCode(const T\&) function


يرجع رمز تجزئة للكائن المحدد الذي هو استثناء.

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع الكائن الذي تُولّد الدالة رمز التجزئة له |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const T\& | غلاف الاستثناء الذي يحتوي على الكائن الذي تُولّد رمز التجزئة له |

### قيمة الإرجاع

رمز التجزئة المولّد للكائن المحدد

## System::GetHashCode(const T\&) function


يرجع رمز تجزئة للكائن المحدد الذي ليس مؤشراً ذكياً ولا استثناءً.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع الكائن الذي تُولّد الدالة رمز التجزئة له |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const T\& | إشارة ثابتة إلى الكائن الذي تُولّد رمز التجزئة له |

### قيمة الإرجاع

رمز التجزئة المولّد للكائن المحدد

## System::GetHashCode(const std::thread::id\&) function


تخصيص لـ std::thread::id؛ يرجع رمز التجزئة للكائن الخيط المحدد.

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## انظر أيضاً

* بنية [IsSmartPtr](../issmartptr/)
* بنية [IsExceptionWrapper](../isexceptionwrapper/)
* نطاق [System](../)
* مكتبة [Aspose.Slides](../../)