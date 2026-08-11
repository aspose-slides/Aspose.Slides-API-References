---
title: UnknownIsNull()
second_title: Aspose.Slides لمرجع API الخاص بـ C++
description: يتحقق مما إذا كان كائن من نوع غير معروف هو nullptr. تحميل زائد للأنواع غير العددية.
type: docs
weight: 144
url: /ar/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) طريقة

يتحقق مما إذا كان كائن من نوع غير معروف هو nullptr. تحميل زائد للأنواع غير العددية.

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | [Object](../../object/) نوع. |

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T | [Object](../../object/) للتحقق. |

### قيمة الإرجاع

True إذا كان 'obj == nullptr' صحيح، false خلاف ذلك.

## ObjectExt::UnknownIsNull(T) طريقة

يتحقق مما إذا كان كائن من نوع غير معروف هو nullptr. تحميل زائد للأنواع العددية.

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | [Object](../../object/) نوع. |

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T | [Object](../../object/) للتحقق. |

### قيمة الإرجاع

دائمًا ما تُعيد false.

## انظر أيضًا

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)