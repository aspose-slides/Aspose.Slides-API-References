---
title: GetValue()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يسترجع قيمة الخاصية من كائن محدد.
type: docs
weight: 1
url: /ar/system.reflection/propertyinfo/getvalue/
---
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>) طريقة

يسترجع قيمة الخاصية من كائن محدد.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) لقراءة الخاصية من. |

### قيمة الإرجاع

قيمة الخاصية المحددة للكائن المحدد.

## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) طريقة

يسترجع قيمة الخاصية من كائن محدد.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) لقراءة الخاصية من. |
| indexer | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | هذه قيم فهرسة اختيارية للخصائص المفهرسة. بالنسبة للخصائص غير المفهرسة، يجب أن تكون هذه القيمة null. |

### قيمة الإرجاع

قيمة الخاصية المحددة للكائن المحدد.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [Object](../../../system/object/)
* فئة [PropertyInfo](../)
* نطاق [System::Reflection](../../)
* Library [Aspose.Slides](../../../)