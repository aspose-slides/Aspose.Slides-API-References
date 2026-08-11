---
title: Equals()
second_title: مرجع API Aspose.Slides للـ C++
description: 
type: docs
weight: 14
url: /ar/system/objectext/equals/
---
## ObjectExt::Equals(const T\&, const T2\&) طريقة




```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## ObjectExt::Equals(const T\&, const T2\&) طريقة


الاستبدال لاستدعاءات C# [Object.Equals](../../object/equals/) التي تعمل مع أي نوع في C++. التحميل الزائد لأنواع المؤشرات الذكية.

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | نوع الكائن الأول. |
| T2 | نوع الكائن الثاني. |

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | الكائن الأول. |
| another | const T2\& | الكائن الثاني. |

### قيمة الإرجاع

True إذا كان الكائنان يعتبران متساويين، false خلاف ذلك.

## ObjectExt::Equals(T, const T2\&) طريقة


الاستبدال لاستدعاءات C# [Object.Equals](../../object/equals/) التي تعمل مع أي نوع في C++. التحميل الزائد لأنواع البُنى.

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | نوع الكائن الأول. |
| T2 | نوع الكائن الثاني. |

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T | الكائن الأول. |
| another | const T2\& | الكائن الثاني. |

### قيمة الإرجاع

True إذا كان الكائنان يعتبران متساويين، false خلاف ذلك.

## ObjectExt::Equals(const T\&, const T2\&) طريقة


الاستبدال لاستدعاءات C# [Object.Equals](../../object/equals/) التي تعمل مع أي نوع في C++. التحميل الزائد لأنواع القيم البسيطة.

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | نوع الكائن الأول. |
| T2 | نوع الكائن الثاني. |

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | الكائن الأول. |
| another | const T2\& | الكائن الثاني. |

### قيمة الإرجاع

True إذا كان الكائنان يعتبران متساويين، false خلاف ذلك.

## ObjectExt::Equals(const char_t(&), String) طريقة


الاستبدال لاستدعاءات C# [Object.Equals](../../object/equals/) التي تعمل مع أي نوع في C++. التحميل الزائد للثوابت النصية مع مقارنة السلاسل.

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| N | [String](../../string/) حجم الثابت. |

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) الثابت. |
| another | [String](../../string/) | [String](../../string/). |

### قيمة الإرجاع

True إذا كانت السلاسل مطابقة، false خلاف ذلك.

## ObjectExt::Equals(const float\&, const float\&) طريقة


يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعتَبَر اثنان من NaN متساويين على الرغم من أن IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN.

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const **float**\& | قيمة النقطة العائمة على الطرف الأيسر. |
| another | const **float**\& | قيمة النقطة العائمة على الطرف الأيمن. |

### قيمة الإرجاع

True إذا كان **obj** و **another** كلاهما NaN أو متساويين، false خلاف ذلك.

## ObjectExt::Equals(const double\&, const double\&) طريقة


يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعتَبَر اثنان من NaN متساويين على الرغم من أن IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN.

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const **double**\& | قيمة النقطة العائمة على الطرف الأيسر. |
| another | const **double**\& | قيمة النقطة العائمة على الطرف الأيمن. |

### قيمة الإرجاع

True إذا كان **obj** و **another** كلاهما NaN أو متساويين، false خلاف ذلك.

## راجع أيضًا

* Class [ObjectExt](../)
* Class [String](../../string/)
* Struct [IsExceptionWrapper](../../isexceptionwrapper/)
* Struct [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)