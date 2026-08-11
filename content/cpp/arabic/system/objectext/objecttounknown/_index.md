---
title: ObjectToUnknown()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تحول Object إلى نوع غير معروف، مع معالجة كل من نوع المؤشر الذكي وحالات القيمة المعبأة.
type: docs
weight: 131
url: /ar/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) طريقة

تحويل [Object](../../object/) إلى نوع غير معروف، مع معالجة كل من نوع المؤشر الذكي وحالات القيمة bpxed.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع الذي يتم تحويل [Object](../../object/) إليه. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) المراد تحويله. |

### قيمة الإرجاع

إما قيمة غير معبأة أو مؤشر محول.

## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) طريقة

تحويل [Object](../../object/) إلى نوع غير معروف، مع معالجة كل من نوع المؤشر الذكي وحالات القيمة المعبأة.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع الذي يتم تحويل [Object](../../object/) إليه. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) المراد تحويله. |

### قيمة الإرجاع

إما قيمة غير معبأة أو مؤشر محول.

## انظر أيضًا

* فئة [SmartPtr](../../smartptr/)
* فئة [Object](../../object/)
* فئة [ObjectExt](../)
* بنية [IsSmartPtr](../../issmartptr/)
* مساحة اسم [System](../../)
* مكتبة [Aspose.Slides](../../../)