---
title: LayoutSlide
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يمثل شريحة تخطيط.
type: docs
weight: 4291
url: /ar/aspose.slides/layoutslide/
---
## LayoutSlide فئة


يمثل شريحة تخطيط.

```cpp
class LayoutSlide : public Aspose::Slides::BaseSlide,
                    public Aspose::Slides::ILayoutSlide
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../baseslide/createthemeeffective/)() override | يعيد سمة فعالة لهذه الشريحة. |
| **bool** [Equals](../baseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) override | يحدد ما إذا كانت المثيلتين [IBaseSlide](../ibaseslide/) متساويتين. تُحسب القيمة المرجعية بناءً على بنية الشريحة والمحتوى الثابت. تكون الشريحتان متساويتين إذا كانت جميع الأشكال والأنماط والنصوص والرسوم المتحركة والإعدادات الأخرى، إلخ، متساوية. لا تأخذ المقارنة في الاعتبار قيم المعرفات الفريدة، مثل SlideId والمحتوى الديناميكي، مثل قيمة التاريخ الحالية في Date [Placeholder](../placeholder/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقوم بمحاكاة مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أنه وفقًا لـ IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقوم بمحاكاة مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أنه وفقًا لـ IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../baseslide/findshapebyalttext/)([System::String](../../system/string/)) override | يبحث عن أول ظهور لشكل يحمل النص البديل المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../baseslide/get_background/)() override | يعيد خلفية الشريحة. للقراءة فقط [IBackground](../ibackground/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../baseslide/get_control/)(**int32_t**) override | يعيد عنصر التحكم ActiveX في الفهرس المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../baseslide/get_controls/)() override | يعيد مجموعة عناصر التحكم ActiveX على شريحة. للقراءة فقط [IControlCollection](../icontrolcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../baseslide/get_customdata/)() override | يعيد البيانات المخصصة للشريحة. للقراءة فقط [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDrawingGuidesCollection](../idrawingguidescollection/)\> [get_DrawingGuides](./get_drawingguides/)() override | يعيد مجموعة من دلائل الرسم لشريحة التخطيط. للقراءة فقط [IDrawingGuidesCollection](../idrawingguidescollection/) |
| **bool** [get_HasDependingSlides](./get_hasdependingslides/)() override | يعيد true إذا كان هناك شريحة واحدة على الأقل تعتمد على شريحة التخطيط هذه. للقراءة فقط **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlideHeaderFooterManager](../ilayoutslideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() override | يعيد مدير HeaderFooter لشريحة التخطيط. للقراءة فقط [ILayoutSlideHeaderFooterManager](../ilayoutslideheaderfootermanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../baseslide/get_hyperlinkqueries/)() override | يوفر وصولًا سهلاً إلى الروابط الفائقة المحتواة. للقراءة فقط [IHyperlinkQueries](../ihyperlinkqueries/). |
| [SlideLayoutType](../slidelayouttype/) [get_LayoutType](./get_layouttype/)() override | يعيد نوع التخطيط لهذه شريحة التخطيط. للقراءة فقط [SlideLayoutType](../slidelayouttype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\> [get_MasterSlide](./get_masterslide/)() override | يعيد شريحة المُستند الرئيسي لتخطيط. قراءة [IMasterSlide](../imasterslide/). |
| [System::String](../../system/string/) [get_Name](../baseslide/get_name/)() override | يعيد اسم الشريحة. قراءة [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutPlaceholderManager](../ilayoutplaceholdermanager/)\> [get_PlaceholderManager](./get_placeholdermanager/)() override | يعيد مدير العنصر النائب لشريحة التخطيط. للقراءة فقط [ILayoutPlaceholderManager](../ilayoutplaceholdermanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../baseslide/get_presentation/)() override | يعيد واجهة [IPresentation](../ipresentation/). للقراءة فقط [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../baseslide/get_shape/)(**int32_t**) override | يعيد الشكل في الفهرس المحدد. للقراءة فقط [Aspose::Slides::IShape](../ishape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../baseslide/get_shapes/)() override | يعيد أشكال الشريحة. للقراءة فقط [IShapeCollection](../ishapecollection/). |
| **bool** [get_ShowMasterShapes](./get_showmastershapes/)() override | يحدد ما إذا كان يجب إظهار الأشكال على شريحة المستند الرئيسي على الشرائح أم لا. قراءة **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | يعيد الشريحة الأساسية. للقراءة فقط [IBaseSlide](../ibaseslide/). |
| **uint32_t** [get_SlideId](../baseslide/get_slideid/)() override | يعيد معرف الشريحة. للقراءة فقط **uint32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../baseslide/get_slideshowtransition/)() override | يعيد كائن Transition الذي يحتوي على معلومات حول كيفية تقدم الشريحة المحددة خلال عرض الشرائح. للقراءة فقط [ISlideShowTransition](../islideshowtransition/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](./get_thememanager/)() override | يعيد مدير السمة المتجاوزة. للقراءة فقط [Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../baseslide/get_timeline/)() override | يعيد كائن مخطط الرسوم المتحركة. للقراءة فقط [IAnimationTimeLine](../ianimationtimeline/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل بيانات عداد المرجع المرتبط بالكائن. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [GetDependingSlides](./getdependingslides/)() override | يعيد مصفوفة تحتوي على جميع الشرائح التي تعتمد على شريحة التخطيط هذه. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثالًا للنوع الموضّح بواسطة targetType. نظير عامل C# 'is'. |
| void [JoinPortionsWithSameFormatting](../baseslide/joinportionswithsameformatting/)() override | ينضم إلى المقاطع ذات التنسيق نفسه في جميع الفقرات وجميع الأشكال المقبولة. |
| virtual void [JoinPortionsWithSameFormatting](../baseslide/joinportionswithsameformatting/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\>) | ينضم إلى المقاطع ذات التنسيق نفسه في جميع الفقرات وجميع الأشكال المقبولة. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل جملة C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن المرجع لكائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| void [Remove](./remove/)() override | يزيل التخطيط من العرض. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد المرجع المشترك بالقيمة المحددة. |
| void [set_MasterSlide](./set_masterslide/)([System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\>) override | يضبط شريحة المُستند الرئيسي لتخطيط. كتابة [IMasterSlide](../imasterslide/). |
| void [set_Name](../baseslide/set_name/)([System::String](../../system/string/)) override | يضبط اسم الشريحة. كتابة [System::String](../../system/string/). |
| void [set_ShowMasterShapes](./set_showmastershapes/)(**bool**) override | يحدد ما إذا كان يجب إظهار الأشكال على شريحة المستند الرئيسي على الشرائح أم لا. كتابة **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل جملة C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [BaseSlide](../baseslide/)
* فئة [ILayoutSlide](../ilayoutslide/)
* فضاء الاسم [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)