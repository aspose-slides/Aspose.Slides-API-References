---
title: IMasterHandoutSlide
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تمثّل الشريحة الرئيسية للنشرات.
type: docs
weight: 2835
url: /ar/aspose.slides/imasterhandoutslide/
---
## IMasterHandoutSlide فئة

يمثل الشريحة الرئيسية للنشرات.

```cpp
class IMasterHandoutSlide : public virtual Aspose::Slides::IBaseSlide,
                            public Aspose::Slides::Theme::IMasterThemeable
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | إرجاع سمة فعالة لهذا الكائن القابل للتنسيق. |
| virtual **bool** [Equals](../ibaseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) | تحدد ما إذا كانت النسختان [IBaseSlide](../ibaseslide/) متساويتين. يتم حساب القيمة المرجعة بناءً على بنية الشريحة والمحتوى الثابت. تكون الشريحتان متساويتين إذا كانت جميع الأشكال والأنماط والنصوص والرسوم المتحركة والإعدادات الأخرى، إلخ، متساوية. لا تأخذ المقارنة في الاعتبار قيم المعرفات الفريدة، مثل SlideId والمحتوى الديناميكي، مثل قيمة التاريخ الحالية في Date [Placeholder](../placeholder/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر قيمتي NaN متساويتين رغم أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر قيمتي NaN متساويتين رغم أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../ibaseslide/findshapebyalttext/)([System::String](../../system/string/)) | يبحث عن أول ظهور لشكل يحتوي على النص البديل المحدد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../ibaseslide/get_background/)() | إرجاع خلفية الشريحة. للقراءة فقط [IBackground](../ibackground/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../ibaseslide/get_control/)(**int32_t**) | إرجاع عنصر التحكم ActiveX في الفهرس المحدد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../ibaseslide/get_controls/)() | إرجاع مجموعة عناصر التحكم ActiveX على شريحة. للقراءة فقط [IControlCollection](../icontrolcollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ibaseslide/get_customdata/)() | إرجاع البيانات المخصصة للشريحة. للقراءة فقط [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDrawingGuidesCollection](../idrawingguidescollection/)\> [get_DrawingGuides](./get_drawingguides/)() | إرجاع مجموعة من دلائل الرسم للشريحة الرئيسية للنشرات. للقراءة فقط [IDrawingGuidesCollection](../idrawingguidescollection/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterHandoutSlideHeaderFooterManager](../imasterhandoutslideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() | إرجاع مدير رأس وتذيل الشريحة الرئيسية للنشرات. للقراءة فقط [IMasterHandoutSlideHeaderFooterManager](../imasterhandoutslideheaderfootermanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../ibaseslide/get_hyperlinkqueries/)() | يوفر وصولًا سهلًا إلى الروابط التشعبية المحتواة. للقراءة فقط [IHyperlinkQueries](../ihyperlinkqueries/). |
| virtual [System::String](../../system/string/) [get_Name](../ibaseslide/get_name/)() | إرجاع اسم الشريحة. قراءة [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | إرجاع العرض التقديمي. للقراءة فقط [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../ibaseslide/get_shape/)(**int32_t**) | إرجاع الشكل في الفهرس المحدد. للقراءة فقط [Aspose::Slides::IShape](../ishape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../ibaseslide/get_shapes/)() | إرجاع أشكال الشريحة. للقراءة فقط [IShapeCollection](../ishapecollection/). |
| virtual **bool** [get_ShowMasterShapes](../ibaseslide/get_showmastershapes/)() | تحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية في الشرائح أم لا. بالنسبة للشريحة الرئيسية نفسها، تُعيد هذه الخاصية دائمًا **false**. قراءة **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | إرجاع الشريحة الأساسية. للقراءة فقط [IBaseSlide](../ibaseslide/). |
| virtual **uint32_t** [get_SlideId](../ibaseslide/get_slideid/)() | إرجاع معرّف الشريحة. للقراءة فقط **uint32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../ibaseslide/get_slideshowtransition/)() | إرجاع كائن TransitionEx الذي يحتوي على معلومات حول كيفية تقدم الشريحة المحددة خلال عرض الشرائح. للقراءة فقط [ISlideShowTransition](../islideshowtransition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/)\> [get_ThemeManager](../../aspose.slides.theme/imasterthemeable/get_thememanager/)() | إرجاع مدير سمة الرئيس. للقراءة فقط [IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../ibaseslide/get_timeline/)() | إرجاع كائن جدول زمني للرسوم المتحركة. للقراءة فقط [IAnimationTimeLine](../ianimationtimeline/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. تماثل مشغل C# 'is'. |
| virtual void [JoinPortionsWithSameFormatting](../ibaseslide/joinportionswithsameformatting/)() | يجمع الجمل ذات التنسيق نفسه في جميع الفقرات في جميع الأشكال القابلة للقبول. |
| void [Lock](../../system/object/lock/)() | ينفذ عبارة القفل C# lock(). استدعِ مباشرة أو استخدم كائن [LockContext](../../system/lockcontext/) الحارس. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | يقوم بإنشاء الكائن. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعلاً، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعلاً، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_Name](../ibaseslide/set_name/)([System::String](../../system/string/)) | يحدد اسم الشريحة. كتابة [System::String](../../system/string/). |
| virtual void [set_ShowMasterShapes](../ibaseslide/set_showmastershapes/)(**bool**) | تحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية في الشرائح أم لا. بالنسبة للشريحة الرئيسية نفسها، تُعيد هذه الخاصية دائمًا **false**. كتابة **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط وسيط القالب n مؤشراً ضعيفًا (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل C# lock(). استدعِ مباشرة أو استخدم كائن [LockContext](../../system/lockcontext/) الحارس. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعلم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [IBaseSlide](../ibaseslide/)
* فئة [IMasterThemeable](../../aspose.slides.theme/imasterthemeable/)
* مساحة الاسم [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)