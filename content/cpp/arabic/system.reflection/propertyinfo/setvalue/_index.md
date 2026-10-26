---
title: SetValue()
second_title: مرجع API Aspose.Slides للغة C++
description: يضبط قيمة الخاصية لكائن محدد.
type: docs
weight: 14
url: /ar/system.reflection/propertyinfo/setvalue/
---
## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>) طريقة

يضبط قيمة الخاصية لكائن محدد.

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) لكتابة الخاصية إلى. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | قيمة الخاصية التي سيتم تعيينها. |

## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) طريقة

يضبط قيمة الخاصية لكائن محدد.

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) لكتابة الخاصية إلى. |
| indexer | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | هذه قيم الفهرسة الاختيارية للخصائص المفهرسة. بالنسبة للخصائص غير المفهرسة، يجب أن تكون هذه القيمة فارغة. |
| value | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | قيمة الخاصية التي سيتم تعيينها. |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [Object](../../../system/object/)
* فئة [PropertyInfo](../)
* مساحة الأسماء [System::Reflection](../../)
* مكتبة [Aspose.Slides](../../../)