---
title: Box()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتغليف أنواع القيم للتحويل إلى Object. تنفيذ لأنواع التعداد.
type: docs
weight: 40
url: /ar/system/objectext/box/
---
## ObjectExt::Box(const T\&) method


يُغلف أنواع القيم للتحويل إلى [Object](../../object/). تنفيذ لأنواع التعداد.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### معلمات القالب

| معلمة | وصف |
| --- | --- |
| T | نوع [Enum](../../enum/). |

### الوسائط

| معلمة | النوع | وصف |
| --- | --- | --- |
| value | const T\& | قيمة [Enum](../../enum/) لتغليفها. |

### قيمة الإرجاع

مؤشر ذكي إلى كائن يحتفظ بالقيمة المُغلفة.

## ObjectExt::Box(const T\&) method


يُغلف أنواع القيم للتحويل إلى [Object](../../object/). تنفيذ لأنواع غير تعداد.

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### معلمات القالب

| معلمة | وصف |
| --- | --- |
| T | نوع القيمة. |

### الوسائط

| معلمة | النوع | وصف |
| --- | --- | --- |
| value | const T\& | القيمة لتغليفها. |

### قيمة الإرجاع

مؤشر ذكي إلى كائن يحتفظ بالقيمة المُغلفة.

## ObjectExt::Box(const T\&) method


يُغلف أنواع [Nullable](../../nullable/) للتحويل إلى [Object](../../object/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### معلمات القالب

| معلمة | وصف |
| --- | --- |
| T | نوع القيمة. |

### الوسائط

| معلمة | النوع | وصف |
| --- | --- | --- |
| value | const T\& | القيمة لتغليفها. |

### قيمة الإرجاع

مؤشر ذكي إلى كائن يحتفظ بالقيمة المُغلفة.

## ObjectExt::Box(const String\&) method


يُغلف قيم السلسلة.

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```


### الوسائط

| معلمة | النوع | وصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | القيمة لتغليفها. |

### قيمة الإرجاع

القيمة المُغلفة أو null إذا كانت سلسلة المصدر null.

## See Also

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Class [String](../../string/)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)