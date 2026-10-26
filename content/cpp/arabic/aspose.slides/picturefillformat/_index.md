---
title: PictureFillFormat
second_title: Aspose.Slides لمرجع API C++
description: يمثل نمط تعبئة صورة.
type: docs
weight: 4720
url: /ar/aspose.slides/picturefillformat/
---
## PictureFillFormat فئة


Represents a picture fill style.

```cpp
class PictureFillFormat : public Aspose::Slides::PVIObject,
                          public Aspose::Slides::IPictureFillFormat
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) override | يضغط الصورة عن طريق تقليل حجمها بناءً على حجم الشكل والدقة المحددة. اختياريًا، يحذف أيضًا المناطق المقصوصة. |
| **bool** [CompressImage](./compressimage/)(**bool**, **float**) override | يضغط الصورة عن طريق تقليل حجمها بناءً على حجم الشكل والدقة المحددة. اختياريًا، يحذف أيضًا المناطق المقصوصة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() override | احذف المناطق المقصوصة من تعبئة [Picture](../picture/). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يقارن مع الكائن المحدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | محاكاة مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNين متساويين على الرغم من أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | محاكاة مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNين متساويين على الرغم من أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **float** [get_CropBottom](./get_cropbottom/)() override | يعيد عدد النسب المئوية لارتفاع الصورة الحقيقي التي تم قصها من أسفل الصورة. قراءة **float**. |
| **float** [get_CropLeft](./get_cropleft/)() override | يعيد عدد النسب المئوية للعرض الحقيقي للصورة التي تم قصها من اليسار. قراءة **float**. |
| **float** [get_CropRight](./get_cropright/)() override | يعيد عدد النسب المئوية للعرض الحقيقي للصورة التي تم قصها من اليمين. قراءة **float**. |
| **float** [get_CropTop](./get_croptop/)() override | يعيد عدد النسب المئوية لارتفاع الصورة الحقيقي التي تم قصها من الأعلى. قراءة **float**. |
| **int32_t** [get_Dpi](./get_dpi/)() override | يعيد قيمة الـ dpi المستخدمة لتعبئة الصورة. قراءة **int32_t**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | يعيد كائن Parent_Immediate. قراءة فقط [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | يعيد الأصل [IPresentationComponent](../ipresentationcomponent/). قراءة فقط [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | يعيد الصورة. قراءة فقط [ISlidesPicture](../islidespicture/). |
| [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() override | يعيد نمط تعبئة الصورة. قراءة [Slides::PictureFillMode](../picturefillmode/). |
| **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() override | يعيد الحافة السفلية لمستطيل التعبئة المحدد بنسبة إزاحة من الحافة السفلية لمربع حدود الشكل. النسبة المئوية الموجبة تعني تقليل المساحة، بينما السالبة تعني توسيعها. قراءة **float**. |
| **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() override | يعيد الحافة اليسرى لمستطيل التعبئة المحدد بنسبة إزاحة من الحافة اليسرى لمربع حدود الشكل. النسبة المئوية الموجبة تعني تقليل المساحة، بينما السالبة تعني توسيعها. قراءة **float**. |
| **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() override | يعيد الحافة اليمنى لمستطيل التعبئة المحدد بنسبة إزاحة من الحافة اليمنى لمربع حدود الشكل. النسبة المئوية الموجبة تعني تقليل المساحة، والسالبة تعني توسيعها. قراءة **float**. |
| **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() override | يعيد الحافة العلوية لمستطيل التعبئة المحدد بنسبة إزاحة من الحافة العلوية لمربع حدود الشكل. النسبة المئوية الموجبة تعني تقليل المساحة، والسالبة تعني توسيعها. قراءة **float**. |
| [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() override | يعيد كيفية محاذاة القوام داخل الشكل. هذا الإعداد يتحكم بنقطة بدء نمط القوام وكيفية تكراره عبر الشكل. قراءة [RectangleAlignment](../rectanglealignment/). |
| [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() override | يقلب بلاط القوام حول محوره الأفقي أو الرأسي أو كليهما. قراءة [Slides::TileFlip](../tileflip/). |
| **float** [get_TileOffsetX](./get_tileoffsetx/)() override | يعيد الإزاحة الأفقية للقوام من أصل الشكل بوحدات النقاط. القيمة الموجبة تحرك القوام إلى اليمين، والسالبة تحركه إلى اليسار. قراءة **float**. |
| **float** [get_TileOffsetY](./get_tileoffsety/)() override | يعيد الإزاحة الرأسية للقوام من أصل الشكل بوحدات النقاط. القيمة الموجبة تحرك القوام إلى الأسفل، والسالبة تحركه إلى الأعلى. قراءة **float**. |
| **float** [get_TileScaleX](./get_tilescalex/)() override | يعيد مقياس القوام الأفقي كنسبة مئوية. قراءة **float**. |
| **float** [get_TileScaleY](./get_tilescaley/)() override | يعيد مقياس القوام الرأسي كنسبة مئوية. قراءة **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | يعيد رمز التجزئة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مكافئ لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. مكافئ لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مكافئ لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعلًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن القيمة بـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_CropBottom](./set_cropbottom/)(**float**) override | يضبط عدد النسب المئوية لارتفاع الصورة الحقيقي التي تُقص من أسفل الصورة. كتابة **float**. |
| void [set_CropLeft](./set_cropleft/)(**float**) override | يضبط عدد النسب المئوية للعرض الحقيقي للصورة التي تُقص من اليسار. كتابة **float**. |
| void [set_CropRight](./set_cropright/)(**float**) override | يضبط عدد النسب المئوية للعرض الحقيقي للصورة التي تُقص من اليمين. كتابة **float**. |
| void [set_CropTop](./set_croptop/)(**float**) override | يضبط عدد النسب المئوية لارتفاع الصورة الحقيقي التي تُقص من الأعلى. كتابة **float**. |
| void [set_Dpi](./set_dpi/)(**int32_t**) override | يضبط قيمة الـ dpi المستخدمة لتعبئة الصورة. كتابة **int32_t**. |
| void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) override | يضبط نمط تعبئة الصورة. كتابة [Slides::PictureFillMode](../picturefillmode/). |
| void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) override | يضبط الحافة السفلية لمستطيل التعبئة المحدد بنسبة إزاحة من الحافة السفلية لمربع حدود الشكل. النسبة الموجبة تعني تقليل المساحة، والسالبة تعني توسيعها. كتابة **float**. |
| void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) override | يضبط الحافة اليسرى لمستطيل التعبئة المحدد بنسبة إزاحة من الحافة اليسرى لمربع حدود الشكل. النسبة الموجبة تعني تقليل المساحة، والسالبة تعني توسيعها. كتابة **float**. |
| void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) override | يضبط الحافة اليمنى لمستطيل التعبئة المحدد بنسبة إزاحة من الحافة اليمنى لمربع حدود الشكل. النسبة الموجبة تعني تقليل المساحة، والسالبة تعني توسيعها. كتابة **float**. |
| void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) override | يضبط الحافة العلوية لمستطيل التعبئة المحدد بنسبة إزاحة من الحافة العلوية لمربع حدود الشكل. النسبة الموجبة تعني تقليل المساحة، والسالبة تعني توسيعها. كتابة **float**. |
| void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) override | يضبط كيفية محاذاة القوام داخل الشكل. هذا الإعداد يتحكم بنقطة بدء نمط القوام وكيفية تكراره عبر الشكل. كتابة [RectangleAlignment](../rectanglealignment/). |
| void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) override | يقلب بلاط القوام حول محوره الأفقي أو الرأسي أو كليهما. كتابة [Slides::TileFlip](../tileflip/). |
| void [set_TileOffsetX](./set_tileoffsetx/)(**float**) override | يضبط الإزاحة الأفقية للقوام من أصل الشكل بوحدات النقاط. القيمة الموجبة تحرك القوام إلى اليمين، والسالبة تحركه إلى اليسار. كتابة **float**. |
| void [set_TileOffsetY](./set_tileoffsety/)(**float**) override | يضبط الإزاحة الرأسية للقوام من أصل الشكل بوحدات النقاط. القيمة الموجبة تحرك القوام إلى الأسفل، والسالبة تحركه إلى الأعلى. كتابة **float**. |
| void [set_TileScaleX](./set_tilescalex/)(**float**) override | يضبط المقياس الأفقي لتعبئة القوام كنسبة مئوية. كتابة **float**. |
| void [set_TileScaleY](./set_tilescaley/)(**float**) override | يضبط المقياس الرأسي لتعبئة القوام كنسبة مئوية. كتابة **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الحجة النّمطيّة رقم n لتكون مؤشرًا ضعيفًا (بدلاً من المشترك). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مكافئ لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ فك قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |
## انظر أيضًا

* فئة [PVIObject](../pviobject/)
* فئة [IPictureFillFormat](../ipicturefillformat/)
* مساحة الاسم [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)