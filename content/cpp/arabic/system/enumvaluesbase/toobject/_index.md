---
title: ToObject()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتحويل القيمة المحددة لعدد صحيح غير موقع 64-بت إلى عنصر تعددي.
type: docs
weight: 40
url: /ar/system/enumvaluesbase/toobject/
---
## طريقة EnumValuesBase::ToObject(const TypeInfo\&, uint64_t)

يقوم بتحويل قيمة عدد صحيح غير موقع 64-بت المحددة إلى عنصر تعددي.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, uint64_t value)
```

### المعلمات

| معاملة | النوع | الوصف |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | نوع التعداد للإرجاع. |
| value | **uint64_t** | القيمة لتحويلها إلى عنصر تعددي. |

### قيمة الإرجاع

كائن من التعداد مضبوط على القيمة.

## طريقة EnumValuesBase::ToObject(const TypeInfo\&, const SharedPtr\<Object\>\&)

يقوم بتحويل الكائن المحدد ذو القيمة العددية إلى عنصر تعددي.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, const SharedPtr<Object> &value)
```

### المعلمات

| معاملة | النوع | الوصف |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | نوع التعداد للإرجاع. |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | القيمة لتحويلها إلى عنصر تعددي. |

### قيمة الإرجاع

كائن تعددي تكون قيمته مساوية للقيمة.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [Object](../../object/)
* فئة [TypeInfo](../../typeinfo/)
* فئة [EnumValuesBase](../)
* مساحة اسم [System](../../)
* مكتبة [Aspose.Slides](../../../)