---
title: MasterSlide
second_title: مرجع API ل Aspose.Slides للـ C++
description: يمثل شريحة رئيسية في عرض تقديمي.
type: docs
weight: 4473
url: /ar/aspose.slides/masterslide/
---
## فئة MasterSlide

يمثل شريحة رئيسية في عرض تقديمي.

```cpp
class MasterSlide : public Aspose::Slides::BaseSlide,
                    public Aspose::Slides::IMasterSlide
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\> [ApplyExternalThemeToDependingSlides](./applyexternalthemetodependingslides/)([System::String](../../system/string/)) override | ينشئ شريحة رئيسية جديدة بناءً على الحالية، يطبق سمة خارجية عليها ويطبق الشريحة الرئيسية المنشأة على جميع الشرائح التابعة. |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../baseslide/createthemeeffective/)() override | يرجع سمة فعالة لهذه الشريحة. |
| **bool** [Equals](../baseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) override | يحدد ما إذا كان مثلي [IBaseSlide](../ibaseslide/) متساويين. تُحسب القيمة المرجعة بناءً على بنية الشريحة والمحتوى الثابت. تكون الشريحتان متساويتان إذا كانت جميع الأشكال والأنماط والنصوص والرسوم المتحركة والإعدادات الأخرى... متساوية. لا تأخذ المقارنة في الاعتبار قيم المعرف الفريد، مثل SlideId والمحتوى الديناميكي، مثل قيمة التاريخ الحالية في Date [Placeholder](../placeholder/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة الأعداد العشرية بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن IEC 60559:1989 يُعرّف NaN بأنه غير مساوي لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة الأعداد العشرية بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن IEC 60559:1989 يُعرّف NaN بأنه غير مساوي لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../baseslide/findshapebyalttext/)([System::String](../../system/string/)) override | يعثر على أول ظهور لشكل بالنص البديل المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../baseslide/get_background/)() override | يرجع خلفية الشريحة. للقراءة فقط [IBackground](../ibackground/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_BodyStyle](./get_bodystyle/)() override | يرجع نمط نص الجسم. للقراءة فقط [ITextStyle](../itextstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../baseslide/get_control/)(**int32_t**) override | يرجع عنصر التحكم ActiveX في الفهرس المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../baseslide/get_controls/)() override | يرجع مجموعة عناصر التحكم ActiveX في شريحة. للقراءة فقط [IControlCollection](../icontrolcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../baseslide/get_customdata/)() override | يرجع البيانات المخصصة للشريحة. للقراءة فقط [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDrawingGuidesCollection](../idrawingguidescollection/)\> [get_DrawingGuides](./get_drawingguides/)() override | يرجع مجموعة من إرشادات الرسم للشريحة الرئيسية. للقراءة فقط [IDrawingGuidesCollection](../idrawingguidescollection/) |
| **bool** [get_HasDependingSlides](./get_hasdependingslides/)() override | يرجع true إذا كان هناك على الأقل شريحة واحدة تعتمد على هذه الشريحة الرئيسية. للقراءة فقط **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() override | يرجع مدير HeaderFooter للشريحة الرئيسية. للقراءة فقط [IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../baseslide/get_hyperlinkqueries/)() override | يوفر وصولاً سهلاً إلى الروابط التشعبية المضمنة. للقراءة فقط [IHyperlinkQueries](../ihyperlinkqueries/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)(**int32_t**) override | يرجع شريحة تخطيط الطفل لهذه الشريحة الرئيسية في الفهرس المحدد. للقراءة فقط [Aspose::Slides::ILayoutSlide](../ilayoutslide/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterLayoutSlideCollection](../imasterlayoutslidecollection/)\> [get_LayoutSlides](./get_layoutslides/)() override | يرجع مجموعة شرائح تخطيط الطفل لهذه الشريحة الرئيسية. للقراءة فقط [IMasterLayoutSlideCollection](../imasterlayoutslidecollection/). |
| [System::String](../../system/string/) [get_Name](./get_name/)() override | يرجع اسم الشريحة الرئيسية. للقراءة [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_OtherStyle](./get_otherstyle/)() override | يرجع نمط نص آخر. للقراءة فقط [ITextStyle](../itextstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../baseslide/get_presentation/)() override | يرجع واجهة [IPresentation](../ipresentation/). للقراءة فقط [IPresentation](../ipresentation/). |
| **bool** [get_Preserve](./get_preserve/)() override | يحدد ما إذا كان يتم حذف الشريحة الرئيسية المقابلة عند حذف جميع الشرائح التي تتبعها. ملاحظة: [Aspose.Slides](../) لن يزيل أي شريحة رئيسية غير مستخدمة بنفسه، لإزالة الشرائح الرئيسية غير المستخدمة فعليًا استدعِ [MasterSlideCollection::RemoveUnused](../masterslidecollection/removeunused/) للقراءة **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../baseslide/get_shape/)(**int32_t**) override | يرجع الشكل في الفهرس المحدد. للقراءة فقط [Aspose::Slides::IShape](../ishape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../baseslide/get_shapes/)() override | يرجع أشكال الشريحة. للقراءة فقط [IShapeCollection](../ishapecollection/). |
| **bool** [get_ShowMasterShapes](./get_showmastershapes/)() override | يحدد ما إذا كان يجب إظهار الأشكال على الشريحة الرئيسية على الشرائح أم لا. بالنسبة للشريحة الرئيسية نفسها، تُعيد هذه الخاصية دائمًا **false**. للقراءة **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | يرجع الشريحة الأساسية. للقراءة فقط [IBaseSlide](../ibaseslide/). |
| **uint32_t** [get_SlideId](../baseslide/get_slideid/)() override | يرجع معرف الشريحة. للقراءة فقط **uint32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../baseslide/get_slideshowtransition/)() override | يرجع كائن Transition الذي يحتوي على معلومات حول كيف تتقدم الشريحة المحددة خلال عرض الشرائح. للقراءة فقط [ISlideShowTransition](../islideshowtransition/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/)\> [get_ThemeManager](./get_thememanager/)() override | يرجع مدير السمة. للقراءة فقط [Theme::IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../baseslide/get_timeline/)() override | يرجع كائن خط زمن الرسوم المتحركة. للقراءة فقط [IAnimationTimeLine](../ianimationtimeline/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TitleStyle](./get_titlestyle/)() override | يرجع نمط نص العنوان. للقراءة فقط [ITextStyle](../itextstyle/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يُحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [GetDependingSlides](./getdependingslides/)() override | يرجع مصفوفة تحتوي على جميع الشرائح التي تعتمد على هذه الشريحة الرئيسية. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثيلاً للنوع الموصوف بـ targetType. تناظر عامل 'is' في C#. |
| void [JoinPortionsWithSameFormatting](../baseslide/joinportionswithsameformatting/)() override | يجمع المقاطع ذات التنسيق نفسه في جميع الفقرات داخل جميع الأشكال المقبولة. |
| virtual void [JoinPortionsWithSameFormatting](../baseslide/joinportionswithsameformatting/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\>) | يجمع المقاطع ذات التنسيق نفسه في جميع الفقرات داخل جميع الأشكال المقبولة. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن المرجعية لكائن من نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) للحالة التي يكون فيها السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_Name](./set_name/)([System::String](../../system/string/)) override | يضبط اسم الشريحة الرئيسية. للكتابة [System::String](../../system/string/). |
| void [set_Preserve](./set_preserve/)(**bool**) override | يحدد ما إذا كان يتم حذف الشريحة الرئيسية المقابلة عندما تُحذف جميع الشرائح التي تتبعها. ملاحظة: [Aspose.Slides](../) لن يزيل أي شريحة رئيسية غير مستخدمة بنفسه، لإزالة الشرائح الرئيسية غير المستخدمة فعليًا استدعِ [MasterSlideCollection::RemoveUnused](../masterslidecollection/removeunused/) للكتابة **bool**. |
| void [set_ShowMasterShapes](./set_showmastershapes/)(**bool**) override | يحدد ما إذا كان يجب إظهار الأشكال على الشريحة الرئيسية على الشرائح أم لا. بالنسبة للشريحة الرئيسية نفسها، تُعيد هذه الخاصية دائمًا **false**. للكتابة **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي رقم n إلى مؤشر ضعيف (بدلاً من مشترك). يتيح تحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلاسل. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [BaseSlide](../baseslide/)
* الفئة [IMasterSlide](../imasterslide/)
* فضاء الأسماء [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)