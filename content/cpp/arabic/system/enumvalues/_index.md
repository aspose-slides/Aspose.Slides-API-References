---
title: EnumValues
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يوفر معلومات وصفية حول ثوابت التعداد من نوع enum E.
type: docs
weight: 794
url: /ar/system/enumvalues/
---
## فئة EnumValues

يوفر معلومات وصفية حول ثوابت التعداد من نوع التعداد **E**.

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| E | نوع التعداد |
## الطرق

| الطريقة | الوصف |
| --- | --- |
|  [EnumValues](./enumvalues/)() | يبني كائنًا. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() const override | يعيد مصفوفة تحتوي على جميع أسماء التعداد **E**. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](../enumvaluesbase/getnames/)(const [TypeInfo](../typeinfo/)\&) | يسترجع مصفوفة بأسماء الثوابت في تعداد محدد. |
| const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() const override | يعيد النوع الأساسي للتعداد المحدد. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | يعيد النوع الأساسي للتعداد المحدد. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(const [String](../string/)\&, **bool**) const override | يعيد القيمة المعبأة للثابت التعدادي بالاسم المحدد. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(long) const override | يعيد القيمة المعبأة للثابت التعدادي بالقيمة المحددة. |
| [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)() const override | يعيد مصفوفة تحتوي على جميع قيم التعداد **E**. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](../enumvaluesbase/getvalues/)(const [TypeInfo](../typeinfo/)\&) | يعيد مصفوفة تحتوي على جميع قيم نوع التعداد المحدد. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../enumvaluesbase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | يعيد كائنًا يمثل قيمة ثابت تعدادي من نوع التعداد المحدد بالاسم المحدد. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | تحول القيمة المحددة ذات 64 بت غير موقعة إلى عضو في التعداد. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | تحول الكائن المحدد ذو القيمة الصحيحة إلى عضو في التعداد. |
| virtual  [~EnumValues](./~enumvalues/)() | المدمر. |

## انظر أيضا

* الفئة [EnumValuesBase](../enumvaluesbase/)
* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)