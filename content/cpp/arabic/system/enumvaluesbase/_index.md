---
title: EnumValuesBase
second_title: مرجع API لـ Aspose.Slides للغة C++
description: فئة أساسية لفئة تمثل معلومات تعريفية لنوع التعداد.
type: docs
weight: 807
url: /ar/system/enumvaluesbase/
---
## EnumValuesBase فئة

فئة أساسية لفئة تمثل معلومات تعريفية لنوع التعداد.

```cpp
class EnumValuesBase
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)(const [TypeInfo](../typeinfo/)\&) | تسترجع مصفوفة بأسماء الثوابت في تعداد محدد. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | تُعيد النوع الأساسي للتعداد المحدد. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)(const [TypeInfo](../typeinfo/)\&) | تُعيد مصفوفة تحتوي على جميع قيم نوع التعداد المحدد. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | تُعيد كائنًا يمثل قيمة ثابت تعداد من النوع المحدد بالاسم المحدد. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | تحول القيمة العددية غير الموقعة 64-بت المحددة إلى عضو تعددي. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | تحول الكائن المحدد ذو القيمة العددية إلى عضو تعددي. |
## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)