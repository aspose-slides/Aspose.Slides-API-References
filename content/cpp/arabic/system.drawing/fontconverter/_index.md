---
title: FontConverter
second_title: "مرجع API لـ Aspose.Slides للغة C++"
description: "يحوِّل كائنات Font من نوع بيانات إلى آخر. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام operator new، لأن ذلك سيسبب أخطاء زمن التنفيذ و/أو أعطال التأكيد. دائمًا غلف هذه الفئة إلى مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط."
type: docs
weight: 92
url: /ar/system.drawing/fontconverter/
---
## FontConverter فئة

يحوِّل كائنات [Font](../font/) من نوع بيانات إلى آخر. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام operator new، لأن ذلك سيسبب أخطاء زمن التنفيذ و/أو أعطال التأكيد. دائمًا غلف هذه الفئة إلى مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط.

```cpp
class FontConverter : public System::ComponentModel::TypeConverter
```

## الأساليب

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFrom](./convertfrom/)(const [System::SharedPtr](../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../system.componentmodel/itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) override | يقوم بتحويل الكائنات. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFrom](../../system.componentmodel/typeconverter/convertfrom/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | يقوم بتحويل الكائنات. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFrom](../../system.componentmodel/typeconverter/convertfrom/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../../system.componentmodel/itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | يقوم بتحويل الكائنات. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFrom](../../system.componentmodel/typeconverter/convertfrom/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../../system.componentmodel/itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::String](../../system/string/)\&) | يحول سلسلة إلى كائن. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFromInvariantString](../../system.componentmodel/typeconverter/convertfrominvariantstring/)(const [System::String](../../system/string/)\&) | يحول سلسلة ثابتة إلى كائن. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFromInvariantString](../../system.componentmodel/typeconverter/convertfrominvariantstring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../../system.componentmodel/itypedescriptorcontext/)\>\&, const [System::String](../../system/string/)\&) | يحول سلسلة ثابتة إلى كائن. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFromString](../../system.componentmodel/typeconverter/convertfromstring/)(const [System::String](../../system/string/)\&) | يحول سلسلة إلى كائن. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFromString](../../system.componentmodel/typeconverter/convertfromstring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../../system.componentmodel/itypedescriptorcontext/)\>\&, const [System::String](../../system/string/)\&) | يحول سلسلة إلى كائن. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFromString](../../system.componentmodel/typeconverter/convertfromstring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../../system.componentmodel/itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::String](../../system/string/)\&) | يحول سلسلة إلى كائن. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertTo](./convertto/)(const [System::SharedPtr](../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../system.componentmodel/itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&, const [System::TypeInfo](../../system/typeinfo/)\&) override | يحول الكائن إلى نوع محدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertTo](../../system.componentmodel/typeconverter/convertto/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&, const [System::TypeInfo](../../system/typeinfo/)\&) | يحول الكائن إلى نوع محدد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertTo](../../system.componentmodel/typeconverter/convertto/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../../system.componentmodel/itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&, const [System::TypeInfo](../../system/typeinfo/)\&) | يحول الكائن إلى نوع محدد. |
| [System::String](../../system/string/) [ConvertToInvariantString](../../system.componentmodel/typeconverter/converttoinvariantstring/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | يحول الكائن إلى سلسلة ثابتة. |
| [System::String](../../system/string/) [ConvertToInvariantString](../../system.componentmodel/typeconverter/converttoinvariantstring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../../system.componentmodel/itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | يحول الكائن إلى سلسلة ثابتة. |
| [System::String](../../system/string/) [ConvertToString](../../system.componentmodel/typeconverter/converttostring/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | يحول الكائن إلى سلسلة. |
| [System::String](../../system/string/) [ConvertToString](../../system.componentmodel/typeconverter/converttostring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../../system.componentmodel/itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | يحول الكائن إلى سلسلة. |
| [System::String](../../system/string/) [ConvertToString](../../system.componentmodel/typeconverter/converttostring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../../system.componentmodel/itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | يحول الكائن إلى سلسلة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر NaN-انان متساويتين رغم أن IEC 60559:1989 تُعرّف NaN بأنها غير مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر NaN-انان متساويتين رغم أن IEC 60559:1989 تُعرّف NaN بأنها غير مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للأغراض الداخلية فقط. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يجلب بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يجلب النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق ما إذا كان الكائن يمثل نسخة من النوع الموضّح بـ targetType. مماثل لمشغل C# ‎'is'‎. |
| void [Lock](../../system/object/lock/)() | ينفّذ عملية القفل lock() الخاصة بـ C#. يُستدعى مباشرة أو عبر كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّئ جميع الهياكل الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | مُنشئ نسخة. لا ينسخ شيئًا فعليًا، بل يهيّئ كائنًا جديدًا ويسمح بنسخ بناء الفئات المشتقة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيّئ كائنًا جديدًا ويسمح بنسخ بناء الفئات المشتقة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائنًا من النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص خاص للـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص خاص للـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يحدد الوسيط القالب رقم n كمؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يجلب القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يُستدعى مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عداد المرجع المشترك ويعيد قيمته. لا يُستدعى مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية typeof([System.Object](../../system/object/)) الخاصة بـ C#. |
|  [TypeConverter](../../system.componentmodel/typeconverter/typeconverter/)() | مُنشئ. |
| void [Unlock](../../system/object/unlock/)() | ينفّذ فك القفل lock() الخاص بـ C#. يُستدعى مباشرة أو عبر كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يُستدعى مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا يُستدعى مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع الهياكل الداخلية. |

## أنظر أيضًا

* الفئة [TypeConverter](../../system.componentmodel/typeconverter/)
* النطاق [System::Drawing](../)
* المكتبة [Aspose.Slides](../../)