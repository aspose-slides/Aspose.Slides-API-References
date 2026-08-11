---
title: Slide
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل شريحة في عرض تقديمي.
type: docs
weight: 5175
url: /ar/aspose.slides/slide/
---
## Slide فئة

يمثل شريحة في عرض تقديمي.

```cpp
class Slide : public Aspose::Slides::BaseSlide,
              public Aspose::Slides::ISlide
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../baseslide/createthemeeffective/)() override | يعيد سمة فعّالة لهذه الشريحة. |
| **bool** [Equals](../baseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) override | يحدد ما إذا كان المثالان [IBaseSlide](../ibaseslide/) متساويين. يتم حساب القيمة المرجعة بناءً على بنية الشريحة والمحتوى الثابت. تكون الشريحتان متساويتين إذا كان جميع الأشكال والأنماط والنصوص والرسوم المتحركة والإعدادات الأخرى ... متساوية. لا يأخذ المقارنة في الاعتبار قيم المعرفات الفريدة، مثل SlideId والمحتوى الديناميكي، مثل قيمة التاريخ الحالية في Date [Placeholder](../placeholder/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يُقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../baseslide/findshapebyalttext/)([System::String](../../system/string/)) override | يبحث عن أول ظهور لشكل يحتوي على النص البديل المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../baseslide/get_background/)() override | يعيد خلفية الشريحة. [IBackground](../ibackground/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../baseslide/get_control/)(**int32_t**) override | يعيد عنصر التحكم ActiveX في الفهرس المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../baseslide/get_controls/)() override | يعيد مجموعة عناصر التحكم ActiveX على الشريحة. [IControlCollection](../icontrolcollection/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../baseslide/get_customdata/)() override | يعيد البيانات المخصصة للشريحة. [ICustomData](../icustomdata/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideHeaderFooterManager](../islideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() override | يعيد مدير الترويسات والتذييلات للشريحة. [ISlideHeaderFooterManager](../islideheaderfootermanager/) للقراءة فقط. |
| **bool** [get_Hidden](./get_hidden/)() override | يحدد ما إذا كانت الشريحة المحددة مخفية أثناء عرض الشرائح. **bool** للقراءة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../baseslide/get_hyperlinkqueries/)() override | يوفر وصولًا سهلًا إلى الروابط التشعبية الموجودة. [IHyperlinkQueries](../ihyperlinkqueries/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)() override | يعيد شريحة التخطيط للشريحة الحالية. [ILayoutSlide](../ilayoutslide/) للقراءة. |
| [System::String](../../system/string/) [get_Name](../baseslide/get_name/)() override | يعيد اسم الشريحة. [System::String](../../system/string/) للقراءة. |
| [System::SharedPtr](../../system/sharedptr/)\<[INotesSlideManager](../inotesslidemanager/)\> [get_NotesSlideManager](./get_notesslidemanager/)() override | يسمح بالوصول إلى شريحة الملاحظات، وإضافتها وإزالتها. [INotesSlideManager](../inotesslidemanager/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../baseslide/get_presentation/)() override | يعيد واجهة [IPresentation](../ipresentation/). [IPresentation](../ipresentation/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../baseslide/get_shape/)(**int32_t**) override | يعيد الشكل في الفهرس المحدد. [Aspose::Slides::IShape](../ishape/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../baseslide/get_shapes/)() override | يعيد أشكال الشريحة. [IShapeCollection](../ishapecollection/) للقراءة فقط. |
| **bool** [get_ShowMasterShapes](./get_showmastershapes/)() override | يحدد ما إذا كان ينبغي إظهار الأشكال على الشريحة الرئيسة في الشرائح أم لا. **bool** للقراءة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | يعيد الشريحة الأساسية. [IBaseSlide](../ibaseslide/) للقراءة فقط. |
| **uint32_t** [get_SlideId](../baseslide/get_slideid/)() override | يعيد معرف الشريحة. **uint32_t** للقراءة فقط. |
| **int32_t** [get_SlideNumber](./get_slidenumber/)() override | يعيد رقم الشريحة. فهرس الشريحة في مجموعة [Presentation::get_Slides()](../presentation/get_slides/) يساوي دائمًا SlideNumber - Presentation::get(set)_FirstSlideNumber. **int32_t** للقراءة. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../baseslide/get_slideshowtransition/)() override | يعيد كائن Transition الذي يحتوي على معلومات حول كيفية تقدم الشريحة المحددة أثناء عرض الشرائح. [ISlideShowTransition](../islideshowtransition/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](./get_thememanager/)() override | يعيد مدير السمة المتجاوز. [Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../baseslide/get_timeline/)() override | يعيد كائن خط الزمن للرسوم المتحركة. [IAnimationTimeLine](../ianimationtimeline/) للقراءة فقط. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد الإشارة المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)(**float**, **float**) override | يعيد كائن صورة مصغرة مع قياس مخصص. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)() override | يعيد كائن صورة مصغرة (20% من الحجم الحقيقي). |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::Drawing::Size](../../system.drawing/size/)) override | يعيد كائن صورة مصغرة بالحجم المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::SharedPtr](../../system/sharedptr/)\<[Export::ITiffOptions](../../aspose.slides.export/itiffoptions/)\>) override | يعيد كائن صورة مصغرة بصيغة tiff مع المعلمات المحددة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) override | يعيد كائن صورة مصغرة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, **float**, **float**) override | يعيد كائن صورة مصغرة مع قياس مخصص. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::Drawing::Size](../../system.drawing/size/)) override | يعيد كائن صورة مصغرة بالحجم المحدد. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>\> [GetSlideComments](./getslidecomments/)([System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\>) override | يعيد كل تعليقات الشريحة المضافة من قبل مؤلف محدد. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلاً للنوع الموصوف بـ targetType. نظير معامل C# 'is'. |
| void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() override | يجمع المقاطع ذات التنسيق نفسه في جميع الفقرات داخل جميع الأشكال القابلة للمعالجة. |
| virtual void [JoinPortionsWithSameFormatting](../baseslide/joinportionswithsameformatting/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\>) | يجمع المقاطع ذات التنسيق نفسه في جميع الفقرات داخل جميع الأشكال القابلة للمعالجة. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). يُستدعى مباشرة أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعياً كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| void [Remove](./remove/)() override | يزيل الشريحة من العرض التقديمي. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [Reset](./reset/)() override | يُعيد تعيين الموضع والحجم والتنسيق لكل شكل لديه نموذج على [LayoutSlide](../layoutslide/). |
| void [set_Hidden](./set_hidden/)(**bool**) override | يحدد ما إذا كانت الشريحة المحددة مخفية أثناء عرض الشرائح. اكتب **bool**. |
| void [set_LayoutSlide](./set_layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>) override | يضبط شريحة التخطيط للشريحة الحالية. اكتب [ILayoutSlide](../ilayoutslide/). |
| void [set_Name](../baseslide/set_name/)([System::String](../../system/string/)) override | يضبط اسم الشريحة. اكتب [System::String](../../system/string/). |
| void [set_ShowMasterShapes](./set_showmastershapes/)(**bool**) override | يحدد ما إذا كان ينبغي إظهار الأشكال على الشريحة الرئيسة في الشرائح أم لا. اكتب **bool**. |
| void [set_SlideNumber](./set_slidenumber/)(**int32_t**) override | يعيد رقم الشريحة. فهرس الشريحة في مجموعة [Presentation::get_Slides()](../presentation/get_slides/) يساوي دائمًا SlideNumber - Presentation::get(set)_FirstSlideNumber. اكتب **int32_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي n كإشارة ضعيفة (بدلاً من مشاركة). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل يُستعمل المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل يُستعمل المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). يُستدعى مباشرة أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ بل يُستعمل المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ بل يُستعمل المؤشرات الذكية أو ThisProtector. |
| void [WriteAsEmf](./writeasemf/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | يحفظ محتوى الشريحة كملف EMF. |
| void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | يحفظ محتوى الشريحة كملف SVG. |
| void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | يحفظ محتوى الشريحة كملف SVG. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [BaseSlide](../baseslide/)
* فئة [ISlide](../islide/)
* فضاء أسماء [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)