---
title: UnknownToObject()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتحويل النوع غير المعروف إلى Object، مع معالجة كل من حالات مؤشر ذكي ونوع قيمة.
type: docs
weight: 118
url: /ar/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(T) طريقة

يقوم بتحويل النوع غير المعروف إلى [Object](../../object/)، مع معالجة كل من حالات مؤشر ذكي ونوع قيمة.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T | النوع للتحويل إلى [Object](../../object/). |

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | T | [Object](../../object/) للتحويل. |

### قيمة الإرجاع

مؤشر ذكي إلى [Object](../../object/) يكون إما مؤشرًا محوّلاً أو قيمةً معبأة.

## ObjectExt::UnknownToObject(const T&) طريقة

يقوم بتحويل النوع غير المعروف إلى [Object](../../object/)، مع معالجة كل من حالات مؤشر ذكي ونوع قيمة.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T | النوع للتحويل إلى [Object](../../object/). |

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) للتحويل. |

### قيمة الإرجاع

مؤشر ذكي إلى [Object](../../object/) يكون إما مؤشرًا محوّلاً أو قيمةً معبأة.

## أنظر أيضًا

* فئة [SmartPtr](../../smartptr/)
* فئة [Object](../../object/)
* فئة [ObjectExt](../)
* بنية [IsSmartPtr](../../issmartptr/)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)