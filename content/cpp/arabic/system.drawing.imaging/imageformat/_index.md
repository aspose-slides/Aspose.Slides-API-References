---
title: ImageFormat
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "يمثل تنسيق ملف الصورة. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم أبداً بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغّل new، حيث سيتسبب ذلك في أخطاء وقت التشغيل أو أخطاء تأكيدية. دائمًا غلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 131
url: /ar/system.drawing.imaging/imageformat/
---
## ImageFormat الفئة

يمثل تنسيق الملف لصورة. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبداً بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغّل new، حيث سيتسبب ذلك في أخطاء وقت التشغيل أو أخطاء تأكيدية. دائمًا غلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class ImageFormat : public System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| **bool** [Equals](./equals/)([ImageFormatPtr](../imageformatptr/)) const | يحدد ما إذا كانت تنسيقات الصورة الممثلة بواسطة الكائن الحالي والكائن المحدد متماثلة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| static [ImageFormatPtr](../imageformatptr/) [get_Bmp](./get_bmp/)() | يعيد مؤشرًا مشتركًا إلى كائن [ImageFormat](./) يمثل تنسيق صورة bitmap. |
| static [ImageFormatPtr](../imageformatptr/) [get_Emf](./get_emf/)() | يعيد مؤشرًا مشتركًا إلى كائن [ImageFormat](./) يمثل تنسيق ملف الميتافايل المُحسّن. |
| static [ImageFormatPtr](../imageformatptr/) [get_Exif](./get_exif/)() | يعيد مؤشرًا مشتركًا إلى كائن [ImageFormat](./) يمثل تنسيق ملف الـ [Image](../../system.drawing/image/) القابل للتبادل (Exif). |
| static [ImageFormatPtr](../imageformatptr/) [get_Gif](./get_gif/)() | يعيد مؤشرًا مشتركًا إلى كائن [ImageFormat](./) يمثل تنسيق صورة [Graphics](../../system.drawing/graphics/) Interchange Format (GIF). |
| [System::Guid](../../system/guid/) [get_Guid](./get_guid/)() const | يعيد معرف GUID المرتبط بتنسيق الصورة الممثلة بواسطة الكائن الحالي. |
| static [ImageFormatPtr](../imageformatptr/) [get_Icon](./get_icon/)() | يعيد مؤشرًا مشتركًا إلى كائن [ImageFormat](./) يمثل تنسيق صورة أيقونة [Windows](../../system.windows/). |
| static [ImageFormatPtr](../imageformatptr/) [get_Jpeg](./get_jpeg/)() | يعيد مؤشرًا مشتركًا إلى كائن [ImageFormat](./) يمثل تنسيق صورة Joint Photographic Experts Group (JPEG). |
| static [ImageFormatPtr](../imageformatptr/) [get_MemoryBmp](./get_memorybmp/)() | يعيد مؤشرًا مشتركًا إلى كائن [ImageFormat](./) يمثل تنسيق البتات في الذاكرة. |
| static [ImageFormatPtr](../imageformatptr/) [get_Png](./get_png/)() | يعيد مؤشرًا مشتركًا إلى كائن [ImageFormat](./) يمثل تنسيق صورة W3C Portable Network [Graphics](../../system.drawing/graphics/) (PNG). |
| static [ImageFormatPtr](../imageformatptr/) [get_Tiff](./get_tiff/)() | يعيد مؤشرًا مشتركًا إلى كائن [ImageFormat](./) يمثل تنسيق صورة Tagged [Image](../../system.drawing/image/) File Format (TIFF). |
| static [ImageFormatPtr](../imageformatptr/) [get_Wmf](./get_wmf/)() | يعيد مؤشرًا مشتركًا إلى كائن [ImageFormat](./) يمثل تنسيق ملف [Windows](../../system.windows/) (WMF). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ImageFormat](./imageformat/)(const [System::Guid](../../system/guid/)\&) | يبني نسخة من الفئة [ImageFormat](./) التي تمثل تنسيق صورة مرتبط بالـ GUID المحدد. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. تماثل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ عملية القفل في عبارة C# lock(). يُستدعى مباشرة أو يستخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن بناء نسخ الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن بناء نسخ الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن المرجع لكائن من نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدد المراجع المشتركة بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط وسيطة القالب رقم n إلى مؤشر ضعيف (بدلاً من المشترك). يتيح تحويل المؤشرات في الحاويات إلى وضعية الضعيفة. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المراجع المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عدد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)() const | يحوّل هذا الكائن [ImageFormat](./) إلى سلسلة قابلة للقراءة للإنسان. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). يُستدعى مباشرة أو يستخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [Object](../../system/object/)
* النطاق [System::Drawing::Imaging](../)
* المكتبة [Aspose.Slides](../../)