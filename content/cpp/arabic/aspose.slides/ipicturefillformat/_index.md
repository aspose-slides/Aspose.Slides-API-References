---
title: IPictureFillFormat
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل نمط تعبئة صورة.
type: docs
weight: 3225
url: /ar/aspose.slides/ipicturefillformat/
---
## فئة IPictureFillFormat

يمثل نمط تعبئة صورة.

```cpp
class IPictureFillFormat : public Aspose::Slides::IFillParamSource
```

## الطرق

| Method | Description |
| --- | --- |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) | يضغط الصورة عن طريق تقليل حجمها بناءً على حجم الشكل والدقة المحددة. اختياريًا، يحذف أيضًا المناطق المقصوصة. |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, **float**) | يضغط الصورة عن طريق تقليل حجمها بناءً على حجم الشكل والدقة المحددة. اختياريًا، يحذف أيضًا المناطق المقصوصة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() | احذف المناطق المقصوصة من التعبئة [Picture](../picture/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث يُعتبر NaNانان متساويين رغم أنه وفقًا لـ IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث يُعتبر NaNانان متساويين رغم أنه وفقًا لـ IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual **float** [get_CropBottom](./get_cropbottom/)() | يرجع عدد النسب المئوية لارتفاع الصورة الحقيقي الذي يتم قصه من أسفل الصورة. اقرأ **float**. |
| virtual **float** [get_CropLeft](./get_cropleft/)() | يرجع عدد النسب المئوية لعرض الصورة الحقيقي الذي يتم قصه من اليسار. اقرأ **float**. |
| virtual **float** [get_CropRight](./get_cropright/)() | يرجع عدد النسب المئوية لعرض الصورة الحقيقي الذي يتم قصه من اليمين. اقرأ **float**. |
| virtual **float** [get_CropTop](./get_croptop/)() | يرجع عدد النسب المئوية لارتفاع الصورة الحقيقي الذي يتم قصه من أعلى الصورة. اقرأ **float**. |
| virtual **int32_t** [get_Dpi](./get_dpi/)() | يرجع قيمة الـ dpi المستخدمة لتعبئة الصورة. اقرأ **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | يرجع الصورة. قراءة فقط [ISlidesPicture](../islidespicture/). |
| virtual [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() | يرجع وضع تعبئة الصورة. اقرأ [Slides::PictureFillMode](../picturefillmode/). |
| virtual **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() | يرجع الحافة السفلية لمستطيل التعبئة المحددة بنسبة إزاحة من الحافة السفلية لصندوق حدود الشكل. النسبة المئوية الإيجابية تشير إلى تجويف، بينما النسبة السلبية تشير إلى بروز. اقرأ **float**. |
| virtual **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() | يرجع الحافة اليسرى للمستطيل المحدد بنسبة إزاحة من الحافة اليسرى لصندوق حدود الشكل. النسبة المئوية الإيجابية تشير إلى تجويف، بينما النسبة السلبية تشير إلى بروز. اقرأ **float**. |
| virtual **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() | يرجع الحافة اليمنى للمستطيل المحدد بنسبة إزاحة من الحافة اليمنى لصندوق حدود الشكل. النسبة المئوية الإيجابية تشير إلى تجويف، بينما النسبة السلبية تشير إلى بروز. اقرأ **float**. |
| virtual **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() | يرجع الحافة العليا للمستطيل المحدد بنسبة إزاحة من الحافة العليا لصندوق حدود الشكل. النسبة المئوية الإيجابية تشير إلى تجويف، بينما النسبة السلبية تشير إلى بروز. اقرأ **float**. |
| virtual [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() | يرجع طريقة محاذاة النسيج داخل الشكل. تتحكم هذه الإعدادات في نقطة بدء نمط النسيج وكيفية تكراره عبر الشكل. اقرأ [RectangleAlignment](../rectanglealignment/). |
| virtual [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() | يقلب بلاطة النسيج حول محورها الأفقي أو العمودي أو كليهما. اقرأ [Slides::TileFlip](../tileflip/). |
| virtual **float** [get_TileOffsetX](./get_tileoffsetx/)() | يرجع الإزاحة الأفقية للنسج من أصل الشكل بالنقاط. القيمة الإيجابية تحرك النسيج إلى اليمين، والقيمة السلبية تحركه إلى اليسار. اقرأ **float**. |
| virtual **float** [get_TileOffsetY](./get_tileoffsety/)() | يرجع الإزاحة العمودية للنسج من أصل الشكل بالنقاط. القيمة الإيجابية تحرك النسيج إلى الأسفل، والسلبية إلى الأعلى. اقرأ **float**. |
| virtual **float** [get_TileScaleX](./get_tilescalex/)() | يرجع مقياس النسيج الأفقي كنسبة مئوية. اقرأ **float**. |
| virtual **float** [get_TileScaleY](./get_tilescaley/)() | يرجع مقياس النسيج العمودي كنسبة مئوية. اقرأ **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد الإشارة المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن بنية النسخ للفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن بنية النسخ للفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_CropBottom](./set_cropbottom/)(**float**) | يضبط عدد النسب المئوية لارتفاع الصورة الحقيقي الذي يتم قصه من أسفل الصورة. اكتب **float**. |
| virtual void [set_CropLeft](./set_cropleft/)(**float**) | يضبط عدد النسب المئوية لعرض الصورة الحقيقي الذي يتم قصه من اليسار. اكتب **float**. |
| virtual void [set_CropRight](./set_cropright/)(**float**) | يضبط عدد النسب المئوية لعرض الصورة الحقيقي الذي يتم قصه من اليمين. اكتب **float**. |
| virtual void [set_CropTop](./set_croptop/)(**float**) | يضبط عدد النسب المئوية لارتفاع الصورة الحقيقي الذي يتم قصه من أعلى الصورة. اكتب **float**. |
| virtual void [set_Dpi](./set_dpi/)(**int32_t**) | يضبط قيمة الـ dpi المستخدمة لتعبئة الصورة. اكتب **int32_t**. |
| virtual void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) | يضبط وضع تعبئة الصورة. اكتب [Slides::PictureFillMode](../picturefillmode/). |
| virtual void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) | يضبط الحافة السفلية للمستطيل المحدد بنسبة إزاحة من الحافة السفلية لصندوق حدود الشكل. النسبة الإيجابية تشير إلى تجويف، والنسبة السلبية إلى بروز. اكتب **float**. |
| virtual void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) | يضبط الحافة اليسرى للمستطيل المحدد بنسبة إزاحة من الحافة اليسرى لصندوق حدود الشكل. النسبة الإيجابية تشير إلى تجويف، والنسبة السلبية إلى بروز. اكتب **float**. |
| virtual void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) | يضبط الحافة اليمنى للمستطيل المحدد بنسبة إزاحة من الحافة اليمنى لصندوق حدود الشكل. النسبة الإيجابية تشير إلى تجويف، والنسبة السلبية إلى بروز. اكتب **float**. |
| virtual void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) | يضبط الحافة العليا للمستطيل المحدد بنسبة إزاحة من الحافة العليا لصندوق حدود الشكل. النسبة الإيجابية تشير إلى تجويف، والنسبة السلبية إلى بروز. اكتب **float**. |
| virtual void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) | يضبط طريقة محاذاة النسيج داخل الشكل. تتحكم هذه الإعدادات في نقطة بدء نمط النسيج وكيفية تكراره عبر الشكل. اكتب [RectangleAlignment](../rectanglealignment/). |
| virtual void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) | يقلب بلاطة النسيج حول محورها الأفقي أو العمودي أو كليهما. اكتب [Slides::TileFlip](../tileflip/). |
| virtual void [set_TileOffsetX](./set_tileoffsetx/)(**float**) | يضبط الإزاحة الأفقية للنسج من أصل الشكل بالنقاط. القيمة الإيجابية تحرك النسيج إلى اليمين، والسلبية إلى اليسار. اكتب **float**. |
| virtual void [set_TileOffsetY](./set_tileoffsety/)(**float**) | يضبط الإزاحة العمودية للنسج من أصل الشكل بالنقاط. القيمة الإيجابية تحرك النسيج إلى الأسفل، والسلبية إلى الأعلى. اكتب **float**. |
| virtual void [set_TileScaleX](./set_tilescalex/)(**float**) | يضبط مقياس النسيج الأفقي كنسبة مئوية. اكتب **float**. |
| virtual void [set_TileScaleY](./set_tilescaley/)(**float**) | يضبط مقياس النسيج العمودي كنسبة مئوية. اكتب **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | تعيين الوسيط القالب الـ n كإشارة ضعيفة (بدلاً من مشتركة). يتيح تحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية للعداد المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |
## أنظر أيضًا

* الفئة [IFillParamSource](../ifillparamsource/)
* النطاق [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)