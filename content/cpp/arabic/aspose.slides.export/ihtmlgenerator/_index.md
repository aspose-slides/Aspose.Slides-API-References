---
title: IHtmlGenerator
second_title: Aspose.Slides لواجهة برمجة تطبيقات C++
description: منشئ HTML.
type: docs
weight: 209
url: /ar/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator الصنف

Html generator.

```cpp
class IHtmlGenerator : public virtual System::Object
```

## الطرق

| Method | الوصف |
| --- | --- |
| virtual void [AddAttributeValue](./addattributevalue/)([System::String](../../system/string/)) | يضع علامات اقتباس حول قيمة السمة ويضيفها إلى ملف الـ html. |
| virtual void [AddAttributeValue](./addattributevalue/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>) | يضع علامات اقتباس حول قيمة السمة ويضيفها إلى ملف الـ html. |
| virtual void [AddAttributeValue](./addattributevalue/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | يضع علامات اقتباس حول قيمة السمة ويضيفها إلى ملف الـ html. |
| virtual void [AddHtml](./addhtml/)([System::String](../../system/string/)) | يضيف نص HTML منسق. |
| virtual void [AddHtml](./addhtml/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>) | يضيف نص HTML منسق. |
| virtual void [AddHtml](./addhtml/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | يضيف نص HTML منسق. |
| virtual void [AddText](./addtext/)([System::String](../../system/string/)) | يضيف نصًا عاديًا إلى ملفات الـ html، مستبدلاً الأحرف الخاصة بكيانات الـ html. لا يتم استبدال فواصل الأسطر والمسافات البيضاء. |
| virtual void [AddText](./addtext/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>) | يضيف نصًا عاديًا إلى ملفات الـ html، مستبدلاً الأحرف الخاصة بكيانات الـ html. لا يتم استبدال فواصل الأسطر والمسافات البيضاء. |
| virtual void [AddText](./addtext/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | يضيف نصًا عاديًا إلى ملفات الـ html، مستبدلاً الأحرف الخاصة بكيانات الـ html. لا يتم استبدال فواصل الأسطر والمسافات البيضاء. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات [Object.Equals](../../system/object/equals/) في C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع الإشارة بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | تحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتَبر NaNان متساويين على الرغم من أن معيار IEC 60559:1989 يوضح أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | تحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتَبر NaNان متساويين على الرغم من أن معيار IEC 60559:1989 يوضح أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual **int32_t** [get_NextSlideIndex](./get_nextslideindex/)() | يعيد فهرس شريحة سيتم عرضها بعد الشريحة الحالية أو -1 إذا كانت الشريحة الحالية هي الأخيرة. قراءة فقط **int32_t**. |
| virtual **int32_t** [get_PreviousSlideIndex](./get_previousslideindex/)() | يعيد فهرس الشريحة التي عُرضت مسبقًا أو -1 إذا كانت الشريحة الأولى هي التي يتم عرضها. قراءة فقط **int32_t**. |
| virtual [System::Drawing::SizeF](../../system.drawing/sizef/) [get_SlideImageSize](./get_slideimagesize/)() | يعيد حجم صورة الشريحة. قراءة فقط [System::Drawing::SizeF](../../system.drawing/sizef/). |
| virtual [SvgCoordinateUnit](../svgcoordinateunit/) [get_SlideImageSizeUnit](./get_slideimagesizeunit/)() | يعيد الوحدة التي يُحدَّد بها حجم صورة الشريحة. قراءة فقط [SvgCoordinateUnit](../svgcoordinateunit/). |
| virtual [System::String](../../system/string/) [get_SlideImageSizeUnitCode](./get_slideimagesizeunitcode/)() | يعيد رمز CSS للوحدة التي يُحدَّد بها حجم صورة الشريحة. قراءة فقط [System::String](../../system/string/). |
| virtual **int32_t** [get_SlideIndex](./get_slideindex/)() | يعيد فهرس الشريحة التي تُعرض حاليًا. قراءة فقط **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عدّاد الإشارة المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مكافئ طريقة [Object.GetHashCode()](../../system/object/gethashcode/) في C#. يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مكافئ لاستدعاء [System.Object.GetType()](../../system/object/gettype/) في C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلًا للنوع الوارد في targetType. مكافئ لمشغل 'is' في C#. |
| void [Lock](../../system/object/lock/)() | تنفذ قفل عبارة lock() في C#. استدعِها مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مكافئ طريقة [Object.MemberwiseClone()](../../system/object/memberwiseclone/) في C#. يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يتهيّئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، بل يتهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يتهيئ ك-object جديد ويتيح إنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالإشارة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد الإشارة المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n كإشارة ضعيفة (بدلاً من المشتركة). يتيح تحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص عداد الإشارة المشتركة ويعيد قيمته. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مكافئ طريقة [Object.ToString()](../../system/object/tostring/) في C#. يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | تنفذ بناء typeof([System.Object](../../system/object/)) في C#. |
| void [Unlock](../../system/object/unlock/)() | تنفذ إلغاء قفل عبارة lock() في C#. استدعِها مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* الفئة [Object](../../system/object/)
* النطاق [Aspose::Slides::Export](../)
* المكتبة [Aspose.Slides](../../)