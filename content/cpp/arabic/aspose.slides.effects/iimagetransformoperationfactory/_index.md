---
title: IImageTransformOperationFactory
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يسمح بإنشاء مثيلات تأثيرات الصورة
type: docs
weight: 755
url: /ar/aspose.slides.effects/iimagetransformoperationfactory/
---
## IImageTransformOperationFactory class

يسمح بإنشاء مثيلات تأثيرات الصورة

```cpp
class IImageTransformOperationFactory : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaBiLevel](../ialphabilevel/)\> [CreateAlphaBiLevel](./createalphabilevel/)(**float**) | ينشئ تأثير Alpha [BiLevel](../bilevel/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaFloor](../ialphafloor/)\> [CreateAlphaFloor](./createalphafloor/)() | ينشئ تأثير أرضية Alpha. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaInverse](../ialphainverse/)\> [CreateAlphaInverse](./createalphainverse/)() | ينشئ تأثير عكسي Alpha. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaModulate](../ialphamodulate/)\> [CreateAlphaModulate](./createalphamodulate/)() | ينشئ تأثير تعديل Alpha. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaModulateFixed](../ialphamodulatefixed/)\> [CreateAlphaModulateFixed](./createalphamodulatefixed/)(**float**) | ينشئ تأثير تعديل ثابت Alpha. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaReplace](../ialphareplace/)\> [CreateAlphaReplace](./createalphareplace/)(**float**) | ينشئ تأثير استبدال Alpha. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaCeiling](../ialphaceiling/)\> [CreateAlphCeiling](./createalphceiling/)() | ينشئ تأثير سقف Alpha. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBiLevel](../ibilevel/)\> [CreateBiLevel](./createbilevel/)(**float**) | ينشئ تأثير [BiLevel](../bilevel/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBlur](../iblur/)\> [CreateBlur](./createblur/)(**double**, **bool**) | ينشئ تأثير [Blur](../blur/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorChange](../icolorchange/)\> [CreateColorChange](./createcolorchange/)() | ينشئ تأثير تغيير اللون. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorReplace](../icolorreplace/)\> [CreateColorReplace](./createcolorreplace/)() | ينشئ تأثير استبدال اللون. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDuotone](../iduotone/)\> [CreateDuotone](./createduotone/)() | ينشئ تأثير [Duotone](../duotone/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillOverlay](../ifilloverlay/)\> [CreateFillOverlay](./createfilloverlay/)() | ينشئ تأثير تغطية التعبئة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGrayScale](../igrayscale/)\> [CreateGrayScale](./creategrayscale/)() | ينشئ تأثير تدرج الرمادي. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHSL](../ihsl/)\> [CreateHSL](./createhsl/)(**float**, **float**, **float**) | ينشئ تأثير [Luminance](../luminance/) لتشبع الصبغة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILuminance](../iluminance/)\> [CreateLuminance](./createluminance/)(**float**, **float**) | ينشئ تأثير [Luminance](../luminance/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITint](../itint/)\> [CreateTint](./createtint/)(**float**, **float**) | ينشئ تأثير [Tint](../tint/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سمات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر القيمتين NaN متساويتين على الرغم من أن وفقًا لـ IEC 60559:1989 فإن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر القيمتين NaN متساويتين على الرغم من أن وفقًا لـ IEC 60559:1989 فإن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | ما يعادل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. ما يعادل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. ما يعادل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل جملة C# lock(). استدعِ مباشرةً أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | ما يعادل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن المرجع لكائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n كإشارة ضعيفة (بدلاً من المشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | ما يعادل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل جملة C# lock(). استدعِ مباشرةً أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |
## Remarks

لأغراض داخلية فقط.

## See Also

* الفئة [Object](../../system/object/)
* النطاق [Aspose::Slides::Effects](../)
* المكتبة [Aspose.Slides](../../)