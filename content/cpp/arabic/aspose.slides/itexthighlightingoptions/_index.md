---
title: ITextHighlightingOptions
second_title: Aspose.Slides لمرجع واجهة برمجة التطبيقات C++
description: يمثل الخيارات التي يمكن استخدامها لتسليط الضوء على النص داخل إطار النص.
type: docs
weight: 4109
url: /ar/aspose.slides/itexthighlightingoptions/
---
## ITextHighlightingOptions فئة


يمثل الخيارات التي يمكن استخدامها لتسليط الضوء على النص داخل إطار النص.

```cpp
class ITextHighlightingOptions : public virtual System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سي شارب [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي على نمط سي شارب. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي على نمط سي شارب. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط سي شارب حيث تُعتبر قيمتا NaN متساويتين على الرغم من أن IEC 60559:1989 يحدد أن NaN غير مساوية لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط سي شارب حيث تُعتبر قيمتا NaN متساويتين على الرغم من أن IEC 60559:1989 يحدد أن NaN غير مساوية لأي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual **bool** [get_CaseSensitive](./get_casesensitive/)() | اضبط القيمة إلى true لاستخدام البحث بحساسيات حالة الأحرف، false خلاف ذلك. قراءة **bool**. |
| virtual **bool** [get_WholeWordsOnly](./get_wholewordsonly/)() | اضبط القيمة إلى true لتطابق الكلمات الكاملة فقط، false خلاف ذلك. قراءة **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة سي شارب [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء سي شارب [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثالًا للنمط الموضح بواسطة targetType. تماثل عامل 'is' في سي شارب. |
| void [Lock](../../system/object/lock/)() | يطبق قفل عبارة lock() في سي شارب. استدعِ مباشرة أو استخدم كائن المراقبة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة سي شارب [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يتهيئ جميع تراكيب البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | مُنشئ النسخة. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_CaseSensitive](./set_casesensitive/)(**bool**) | اضبط القيمة إلى true لاستخدام البحث بحساسيات حالة الأحرف، false خلاف ذلك. كتابة **bool**. |
| virtual void [set_WholeWordsOnly](./set_wholewordsonly/)(**bool**) | اضبط القيمة إلى true لتطابق الكلمات الكاملة فقط، false خلاف ذلك. كتابة **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يعيّن المتغير القالب الـ n إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عداد المرجع المشترك ويعيد قيمته. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة سي شارب [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بنية سي شارب typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبق قفل عبارة lock() في سي شارب لإلغاء القفل. استدعِ مباشرة أو استخدم كائن المراقبة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع تراكيب البيانات الداخلية. |

مهمل
:   الواجهة [ITextHighlightingOptions](./) ستُزال بعد إصدار الإصدار 24.10.

## أنظر أيضًا

* فئة [Object](../../system/object/)
* مساحة الاسم [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)