---
title: Unbox()
second_title: مرجع API Aspose.Slides للغة C++
description: يفكّ تغليف أنواع القيم بعد التحويل إلى Object. تنفيذ لأنواع التعداد.
type: docs
weight: 53
url: /ar/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) طريقة


يفكّ تغليف أنواع القيم بعد التحويل إلى [Object](../../object/). تنفيذ لأنواع التعداد.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### معلمات القالب

| معاملة | وصف |
| --- | --- |
| T | [Enum](../../enum/) type. |

### المعاملات

| معاملة | نوع | وصف |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) لفك التغليف. |

### قيمة الإرجاع

[Enum](../../enum/) قيمة.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) طريقة


يفكّ تغليف أنواع القيم بعد التحويل إلى [Object](../../object/). تنفيذ للأنواع غير التعدادية غير القابلة للإلغاء.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### معلمات القالب

| معاملة | وصف |
| --- | --- |
| T | Value type. |

### المعاملات

| معاملة | نوع | وصف |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) لفك التغليف. |

### قيمة الإرجاع

قيمة مفكوكة.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) طريقة


يفكّ تغليف أنواع القيم بعد التحويل إلى [Object](../../object/). تنفيذ للأنواع غير التعدادية غير القابلة للإلغاء.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### معلمات القالب

| معاملة | وصف |
| --- | --- |
| T | Value type. |

### المعاملات

| معاملة | نوع | وصف |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) لفك التغليف. |

### قيمة الإرجاع

قيمة مفكوكة.

## ObjectExt::Unbox(E) طريقة


يفكّ تغليف أنواع التعداد إلى عدد صحيح.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```


### معلمات القالب

| معاملة | وصف |
| --- | --- |
| T | Destination integer type. |
| E | Source enum type. |

### المعاملات

| معاملة | نوع | وصف |
| --- | --- | --- |
| e | E | Value to unbox. |

### قيمة الإرجاع

تمثيل عدد صحيح للتعداد.

## ObjectExt::Unbox(E) طريقة


يحوّل أنواع التعداد.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```


### معلمات القالب

| معاملة | وصف |
| --- | --- |
| T | Destination enum type. |
| E | Source enum type. |

### المعاملات

| معاملة | نوع | وصف |
| --- | --- | --- |
| e | E | Value to unbox. |

### قيمة الإرجاع

قيمة التعداد المحوّلة.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) طريقة


يفكّ تغليف قيم السلاسل.

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### المعاملات

| معاملة | نوع | وصف |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) لفك التغليف |

### قيمة الإرجاع

[String](../../string/) تمثيل السلسلة المعبأة، يمكن أن يكون فارغاً إذا كانت السلسلة المعبأة فارغة.

## انظر أيضًا

* الفئة [SmartPtr](../../smartptr/)
* الفئة [Object](../../object/)
* الفئة [ObjectExt](../)
* الفئة [String](../../string/)
* مساحة الاسم [System](../../)
* المكتبة [Aspose.Slides](../../../)