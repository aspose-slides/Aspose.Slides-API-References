---
title: Font
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثّل تنسيقًا معينًا للنص، بما في ذلك عائلة الخط، الحجم، والنمط. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم أبدًا بإنشاء مثال لهذا النوع على المكدس أو باستخدام المشغّل new، حيث سيتسبب ذلك في أخطاء وقت التشغيل أو أخطاء التحقق. احِط دائمًا هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدالات كمعامل."
type: docs
weight: 79
url: /ar/system.drawing/font/
---
## الفئة Font


يمثل تنسيقًا معينًا للنص، بما في ذلك نوع الخط وحجمه ونمطه. يجب تخصيص الكائنات من هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبدًا بإنشاء مثيل لهذا النوع على المكدس أو باستخدام operator new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل و/أو أخطاء التحقق. احِط دائمًا هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدالات كمعامل.

```cpp
class Font : public System::Object
```

## الأساليب

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Font](./)\> [Clone](./clone/)() | يعيد نسخة من الخط الحالي. |
| void [Dispose](./dispose/)() | يحرّر جميع موارد نظام التشغيل التي حصل عليها الكائن الحالي. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يحدّد ما إذا كان الكائنان الحاليان والمحددان متماثلان. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع على نمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقلّد مقارنة النقطة العائمة على نمط C# حيث يُعتَبر NaNانان متساويين رغم أن وفقًا لـ IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقلّد مقارنة النقطة العائمة على نمط C# حيث يُعتَبر NaNانان متساويين رغم أن وفقًا لـ IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[Font](./)\>\&, [FontStyle](../fontstyle/)) | يبني مثيلًا جديدًا من الفئة [Font](./) التي تمثل الخط الموجود المحدد مع نمط الخط المحدد. |
| [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\>\&, **float**, [FontStyle](../fontstyle/), [GraphicsUnit](../graphicsunit/), **uint8_t**, **bool**) | يبني مثيلًا جديدًا من الفئة [Font](./). |
| [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\>\&, **float**, [GraphicsUnit](../graphicsunit/)) | يبني مثيلًا جديدًا من الفئة [Font](./). |
| [Font](./font/)(const [String](../../system/string/)\&, **float**, [FontStyle](../fontstyle/), [GraphicsUnit](../graphicsunit/), **uint8_t**, **bool**) | يبني مثيلًا جديدًا من الفئة [Font](./). |
| [Font](./font/)(const [String](../../system/string/)\&, **float**, [GraphicsUnit](../graphicsunit/)) | يبني مثيلًا جديدًا من الفئة [Font](./). |
| static [SharedPtr](../../system/sharedptr/)\<[Font](./)\> [FromLogFont](./fromlogfont/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | غير مُنفّذ. |
| **bool** [get_Bold](./get_bold/)() | يحدّد ما إذا كان الخط الممثَّل بواسطة الكائن الحالي يمتلك نمط الغامق. |
| [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\> [get_FontFamily](./get_fontfamily/)() | يعيد عائلة الخط للخط الممثَّل بواسطة الكائن الحالي. |
| [FontStyle](../fontstyle/) [get_FontStyle](./get_fontstyle/)() | يعيد نمط الخط للخط الممثَّل بواسطة الكائن الحالي. |
| **uint8_t** [get_GdiCharSet](./get_gdicharset/)() | يعيد قيمة تشير إلى مجموعة الأحرف GDI المستخدمة من قبل الخط الممثَّل بالكائن الحالي. |
| int [get_Height](./get_height/)() | يعيد تباعد الأسطر للخط الممثَّل بواسطة الكائن الحالي بوحدات البكسل. |
| **bool** [get_Italic](./get_italic/)() | يحدّد ما إذا كان الخط الممثَّل بواسطة الكائن الحالي يمتلك نمط المائل. |
| [String](../../system/string/) [get_Name](./get_name/)() | يعيد اسم الوجه للخط الممثَّل بواسطة الكائن الحالي. |
| [String](../../system/string/) [get_OriginalFontName](./get_originalfontname/)() | يعيد الاسم الأصلي المحدد للخط. |
| **float** [get_Size](./get_size/)() | يعيد حجم الـ em للخط الممثَّل بواسطة الكائن الحالي مقاسًا بالوحدات المحددة في خاصية Unit. |
| **float** [get_SizeInPoints](./get_sizeinpoints/)() | يعيد حجم الـ em للخط الممثَّل بواسطة الكائن الحالي بالنقاط. |
| **bool** [get_Strikeout](./get_strikeout/)() | يحدّد ما إذا كان الخط الممثَّل بواسطة الكائن الحالي يمتلك نمط الشطب. |
| [FontStyle](../fontstyle/) [get_Style](./get_style/)() | يعيد نمط الخط للخط الممثَّل بواسطة الكائن الحالي. |
| **bool** [get_Underline](./get_underline/)() | يحدّد ما إذا كان الخط الممثَّل بواسطة الكائن الحالي يمتلك نمط التحتي. |
| [GraphicsUnit](../graphicsunit/) [get_Unit](./get_unit/)() | يعيد وحدة القياس للخط الممثَّل بواسطة الكائن الحالي. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| **float** [GetHeight](./getheight/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | يعيد تباعد الأسطر للخط الممثَّل بواسطة الكائن الحالي، بالوحدة الحالية لكائن [Graphics](../graphics/) المحدد. |
| **float** [GetHeight](./getheight/)(**float**) | يعيد ارتفاع الخط الممثَّل بواسطة الكائن الحالي عند رسمه على جهاز عرض بالدقة العمودية المحددة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثيلًا للنوع الموصَّف بـ targetType. مماثل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ عملية القفل الخاصة بعبارة C# lock(). استدعِه مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل إسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات عن طريق المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات عن طريق المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) للحالة التي يكون فيها السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ فك قفل عبارة C# lock(). استدعِه مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [Object](../../system/object/)
* النطاق [System::Drawing](../)
* المكتبة [Aspose.Slides](../../)