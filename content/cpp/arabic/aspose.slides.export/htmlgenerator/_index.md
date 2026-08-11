---
title: HtmlGenerator
second_title: مرجع API لـ Aspose.Slides للغة C++
description: مولد HTML.
type: docs
weight: 105
url: /ar/aspose.slides.export/htmlgenerator/
---
## HtmlGenerator فئة

Html generator.

```cpp
class HtmlGenerator : public Aspose::Slides::Export::IHtmlGenerator
```

## الطرق

| Method | Description |
| --- | --- |
| void [AddAttributeValue](./addattributevalue/)([System::String](../../system/string/)) override | يقتبس قيمة السمة ويضيفها إلى ملف html. |
| void [AddAttributeValue](./addattributevalue/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>) override | يقتبس قيمة السمة ويضيفها إلى ملف html. |
| void [AddAttributeValue](./addattributevalue/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | يقتبس قيمة السمة ويضيفها إلى ملف html. |
| void [AddHtml](./addhtml/)([System::String](../../system/string/)) override | يضيف نص HTML منسق. |
| void [AddHtml](./addhtml/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>) override | يضيف نص HTML منسق. |
| void [AddHtml](./addhtml/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | يضيف نص HTML منسق. |
| void [AddText](./addtext/)([System::String](../../system/string/)) override | يضيف نصًا عاديًا إلى ملفات html، مع استبدال الأحرف الخاصة بكيانات html. لا يتم استبدال فواصل الأسطر والمسافات البيضاء. |
| void [AddText](./addtext/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>) override | يضيف نصًا عاديًا إلى ملفات html، مع استبدال الأحرف الخاصة بكيانات html. لا يتم استبدال فواصل الأسطر والمسافات البيضاء. |
| void [AddText](./addtext/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | يضيف نصًا عاديًا إلى ملفات html، مع استبدال الأحرف الخاصة بكيانات html. لا يتم استبدال فواصل الأسطر والمسافات البيضاء. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانين متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانين متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **int32_t** [get_NextSlideIndex](./get_nextslideindex/)() override | يرجع فهرس الشريحة التي سيتم عرضها بعد الشريحة الحالية أو -1 إذا كانت الشريحة الأخيرة تُعرض حاليًا. **int32_t** للقراءة فقط. |
| **int32_t** [get_PreviousSlideIndex](./get_previousslideindex/)() override | يرجع فهرس الشريحة السابقة أو -1 إذا كانت الشريحة الأولى تُعرض. **int32_t** للقراءة فقط. |
| [System::Drawing::SizeF](../../system.drawing/sizef/) [get_SlideImageSize](./get_slideimagesize/)() override | يرجع حجم صورة الشريحة. [System::Drawing::SizeF](../../system.drawing/sizef/) للقراءة فقط. |
| [SvgCoordinateUnit](../svgcoordinateunit/) [get_SlideImageSizeUnit](./get_slideimagesizeunit/)() override | يرجع وحدة قياس حجم صورة الشريحة. [SvgCoordinateUnit](../svgcoordinateunit/) للقراءة فقط. |
| [System::String](../../system/string/) [get_SlideImageSizeUnitCode](./get_slideimagesizeunitcode/)() override | يرجع كود css للوحدة التي يُحدَّد بها حجم صورة الشريحة. [System::String](../../system/string/) للقراءة فقط. |
| **int32_t** [get_SlideIndex](./get_slideindex/)() override | يرجع فهرس الشريحة الحالية المعروضة. **int32_t** للقراءة فقط. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد الإشارة المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). تمكّن تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. تماثل معامل C# ‎'is'‎. |
| void [Lock](../../system/object/lock/)() | ينفّذ عملية القفل في بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). تمكّن استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يتهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، بل يتهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يتهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد الإشارة المشتركة بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النوني للقالب كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع الضعيفة. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). تمكّن تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ عملية إلغاء القفل في بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [IHtmlGenerator](../ihtmlgenerator/)
* نطاق [Aspose::Slides::Export](../)
* مكتبة [Aspose.Slides](../../)