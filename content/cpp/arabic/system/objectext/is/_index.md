---
title: Is()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يطبق ترجمة معامل 'is'. تخصص للأنواع القابلة للصناديق (القيمة) التي هي بالضبط كذلك.
type: docs
weight: 92
url: /ar/system/objectext/is/
---
## ObjectExt::Is(const T\&) طريقة


يطبق ترجمة معامل 'is'. تخصص للأنواع القابلة للصناديق (القيمية) التي هي بالضبط كذلك.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value, bool>::type System::ObjectExt::Is(const T &obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع المستهدف. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) لاختبار معامل 'is'. تم التجاهل. |

### قيمة الإرجاع

دائمًا true

## ObjectExt::Is(const U\&) طريقة


يطبق ترجمة معامل 'is'. تخصص للأنواع المؤشرة مُحسّن للفئات 'final'.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع المستهدف. |
| U | النوع المُختبر. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) لاختبار معامل 'is'. |

### قيمة الإرجاع

صحيح إذا كان 'is' يعيد true، false وإلا.

## ObjectExt::Is(const U\&) طريقة


يطبق ترجمة معامل 'is'. تخصص للأنواع المؤشرة.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع المستهدف. |
| U | النوع المُختبر. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) لاختبار معامل 'is'. |

### قيمة الإرجاع

صحيح إذا كان 'is' يعيد true، false وإلا.

## ObjectExt::Is(const Object\&) طريقة


يطبق ترجمة معامل 'is'. تخصص للأنواع القيمية.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع المستهدف. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) لاختبار معامل 'is'. |

### قيمة الإرجاع

صحيح إذا كان 'is' يعيد true، false وإلا.

## ObjectExt::Is(const Object\&) طريقة


يطبق ترجمة معامل 'is'. تخصص للأنواع غير القابلة للتحويل.

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع المستهدف. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) لاختبار معامل 'is'. |

### قيمة الإرجاع

دائمًا يعيد false لأن الأنواع غير قابلة للتحويل.

## ObjectExt::Is(const SmartPtr\<U\>\&) طريقة


يطبق ترجمة معامل 'is'. تخصص للأنواع المؤشرة.

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع المستهدف. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) لاختبار معامل 'is'. |

### قيمة الإرجاع

صحيح إذا كان 'is' يعيد true، false وإلا.

## ObjectExt::Is(const ExceptionWrapper\<U\>\&) طريقة


يطبق ترجمة معامل 'is'. تخصص للأنواع المغلفة بالاستثناء.

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع المستهدف. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const [ExceptionWrapper](../../exceptionwrapper/)\<U\>\& | [Object](../../object/) لاختبار معامل 'is'. |

### قيمة الإرجاع

صحيح إذا كان 'is' يعيد true، false وإلا.

## ObjectExt::Is(const SmartPtr\<Object\>\&) طريقة


يطبق ترجمة معامل 'is'. تخصص للأنواع القابلة للإنكار.

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع المستهدف. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) لاختبار معامل 'is'. |

### قيمة الإرجاع

صحيح إذا كان 'is' يعيد true، false وإلا.

## ObjectExt::Is(const SmartPtr\<Object\>\&) طريقة


يطبق ترجمة معامل 'is'. تخصص للأنواع القابلة للصناديق مع تعريف معامل ==.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع المستهدف. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) لاختبار معامل 'is'. |

### قيمة الإرجاع

صحيح إذا كان 'is' يعيد true، false وإلا.

## ObjectExt::Is(const SmartPtr\<Object\>\&) طريقة


يطبق ترجمة معامل 'is'. تخصص للأنواع القابلة للصناديق بدون تعريف ==.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع المستهدف. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) لاختبار معامل 'is'. |

### قيمة الإرجاع

صحيح إذا كان 'is' يعيد true، false وإلا.

## ObjectExt::Is(const SmartPtr\<V\>\&) طريقة


يطبق ترجمة معامل 'is'. تخصص للأنواع القيمية المُغلفة إلى واجهات.

```cpp
template<class T,class V> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!std::is_same<V, Object>::value, bool>::type System::ObjectExt::Is(const SmartPtr<V> &obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع المستهدف. |
| V | نوع الكائن المشار إليه. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<V\>\& | [Object](../../object/) لاختبار معامل 'is'. |

### قيمة الإرجاع

صحيح إذا كان 'is' يعيد true، false وإلا.

## ObjectExt::Is(const SmartPtr\<U\>\&) طريقة


يطبق ترجمة معامل 'is'. تخصص للأنواع المتعددية.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع المستهدف. |
| U | نوع الكائن المشار إليه. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) لاختبار معامل 'is'. |

### قيمة الإرجاع

صحيح إذا كان 'is' يعيد true، false وإلا.

## ObjectExt::Is(const WeakPtr\<U\>\&) طريقة


يطبق ترجمة معامل 'is'. تخصص للأنواع المتعددية مقابل مؤشرات ضعيفة.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع المستهدف. |
| U | نوع الكائن المشار إليه. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const [WeakPtr](../../weakptr/)\<U\>\& | [Object](../../object/) لاختبار معامل 'is'. |

### قيمة الإرجاع

صحيح إذا كان 'is' يعيد true، false وإلا.

## ObjectExt::Is(const Nullable\<U\>\&) طريقة


يطبق ترجمة معامل 'is'. تخصص للنوع [Nullable](../../nullable/).

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع المستهدف. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [Nullable](../../nullable/)\<U\>\& | [Nullable](../../nullable/) نوع. |

### قيمة الإرجاع

صحيح إذا كان 'is' يعيد true، false وإلا.

## ObjectExt::Is(const char16_t *) طريقة


يطبق ترجمة معامل 'is'. تخصص للعبارة النصية.

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع المستهدف. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) حرفي. |

### قيمة الإرجاع

صحيح إذا كان 'is' يعيد true، false وإلا.

## ObjectExt::Is(int32_t) طريقة


يطبق ترجمة معامل 'is'. تخصص للعبارة عددية صحيحة.

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع المستهدف. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | **int32_t** | عدد صحيح حرفي. |

### قيمة الإرجاع

صحيح إذا كان 'is' يعيد true، false وإلا.

## انظر أيضًا

* فئة [ObjectExt](../)
* فئة [Object](../../object/)
* فئة [SmartPtr](../../smartptr/)
* فئة [ExceptionWrapper](../../exceptionwrapper/)
* فئة [WeakPtr](../../weakptr/)
* فئة [Nullable](../../nullable/)
* بنية [IsBoxable](../../isboxable/)
* بنية [IsSmartPtr](../../issmartptr/)
* بنية [IsExceptionWrapper](../../isexceptionwrapper/)
* بنية [IsNullable](../../isnullable/)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)