---
title: IDataLabelFormat
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل خيارات التنسيق لتسمية البيانات.
type: docs
weight: 963
url: /ar/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat فئة


يمثل خيارات التنسيق لـ [DataLabel](../datalabel/).

```cpp
class IDataLabelFormat : public Aspose::Slides::Charts::IFormattedTextContainer
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يعكس مقارنة النقطة العائمة على نمط C# حيث تُعتبر NaNانان متساويتين بالرغم من أنه وفقًا لـ IEC 60559:1989 فإن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يعكس مقارنة النقطة الع浮 على نمط C# حيث تُعتبر NaNانان متساويتين بالرغم من أنه وفقًا لـ IEC 60559:1989 فإن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | يرجع المخطط. قراءة فقط [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | يمثل تنسيق تسمية البيانات. قراءة فقط [IFormat](../iformat/). |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | قراءة **bool**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | يمثل سلسلة التنسيق لكائن DataLabels. قراءة [System::String](../../system/string/). |
| virtual [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() | يمثل موضع تسمية البيانات. قراءة [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | يرجع العرض. قراءة فقط [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::String](../../system/string/) [get_Separator](./get_separator/)() | يضبط أو يرجع Variant يمثل الفاصل المستخدم لتسميات البيانات على المخطط. قراءة [System::String](../../system/string/). |
| virtual **bool** [get_ShowBubbleSize](./get_showbubblesize/)() | يمثل سلوك عرض قيمة حجم الفقعة لتسمية البيانات في مخطط محدد. True يعرض قيمة حجم الفقعة. False لإخفائها. قراءة **bool**. |
| virtual **bool** [get_ShowCategoryName](./get_showcategoryname/)() | يمثل سلوك عرض اسم الفئة لتسمية البيانات في مخطط محدد. True لعرض اسم الفئة لتسميات البيانات على المخطط. False للإخفاء. قراءة **bool**. |
| virtual **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() | يحدد ما إذا كانت تسمية البيانات في مخطط محدد ستُعرض كعلامة إشارة بيانات أو كاسم بيانات. |
| virtual **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() | يمثل سلوك عرض قيمة الخلية لتسمية البيانات في مخطط محدد. True يعرض قيمة الخلية. False لإخفائها. قراءة **bool**. |
| virtual **bool** [get_ShowLeaderLines](./get_showleaderlines/)() | يمثل سلوك عرض خطوط القائد لتسمية البيانات في مخطط محدد. True يعرض خطوط القائد. False لإخفائها. قراءة **bool**. |
| virtual **bool** [get_ShowLegendKey](./get_showlegendkey/)() | يمثل سلوك عرض مفتاح وسيلة الإيضاح لتسمية البيانات في مخطط محدد. True إذا كان مفتاح وسيلة الإيضاح لتسمية البيانات مرئياً. قراءة **bool**. |
| virtual **bool** [get_ShowPercentage](./get_showpercentage/)() | يمثل سلوك عرض قيمة النسبة المئوية لتسمية البيانات في مخطط محدد. True يعرض قيمة النسبة المئوية. False لإخفائها. قراءة **bool**. |
| virtual **bool** [get_ShowSeriesName](./get_showseriesname/)() | يرجع قيمة Boolean لتحديد سلوك عرض اسم السلسلة لتسميات البيانات على المخطط. True لإظهار اسم السلسلة. False لإخفائه. قراءة **bool**. |
| virtual **bool** [get_ShowValue](./get_showvalue/)() | يمثل سلوك عرض قيمة النسبة المئوية لتسمية البيانات في مخطط محدد. True يعرض قيمة النسبة المئوية. False لإخفائها. قراءة **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | يرجع الشريحة الأساسية. قراءة فقط [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | يرجع تنسيق نص المخطط. قراءة فقط [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد الإشارة المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بواسطة targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعياً كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد الإشارة المشتركة بالقيمة المحددة. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | كتابة **bool**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | يمثل سلسلة التنسيق لكائن DataLabels. كتابة [System::String](../../system/string/). |
| virtual void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) | يمثل موضع تسمية البيانات. كتابة [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual void [set_Separator](./set_separator/)([System::String](../../system/string/)) | يضبط أو يرجع Variant يمثل الفاصل المستخدم لتسميات البيانات على المخطط. كتابة [System::String](../../system/string/). |
| virtual void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) | يمثل سلوك عرض قيمة حجم الفقعة لتسمية البيانات في مخطط محدد. True يعرض قيمة حجم الفقعة. False لإخفائها. كتابة **bool**. |
| virtual void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) | يمثل سلوك عرض اسم الفئة لتسمية البيانات في مخطط محدد. True لعرض اسم الفئة لتسميات البيانات على المخطط. False للإخفاء. كتابة **bool**. |
| virtual void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) | يحدد ما إذا كانت تسمية البيانات في مخطط محدد ستُعرض كعلامة إشارة بيانات أو كاسم بيانات. |
| virtual void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) | يمثل سلوك عرض قيمة الخلية لتسمية البيانات في مخطط محدد. True يعرض قيمة الخلية. False لإخفائها. كتابة **bool**. |
| virtual void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) | يمثل سلوك عرض خطوط القائد لتسمية البيانات في مخطط محدد. True يعرض خطوط القائد. False لإخفائها. كتابة **bool**. |
| virtual void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) | يمثل سلوك عرض مفتاح وسيلة الإيضاح لتسمية البيانات في مخطط محدد. True إذا كان مفتاح وسيلة الإيضاح لتسمية البيانات مرئياً. كتابة **bool**. |
| virtual void [set_ShowPercentage](./set_showpercentage/)(**bool**) | يمثل سلوك عرض قيمة النسبة المئوية لتسمية البيانات في مخطط محدد. True يعرض قيمة النسبة المئوية. False لإخفائها. كتابة **bool**. |
| virtual void [set_ShowSeriesName](./set_showseriesname/)(**bool**) | يحدد قيمة Boolean لتحديد سلوك عرض اسم السلسلة لتسميات البيانات على المخطط. True لإظهار اسم السلسلة. False لإخفائه. كتابة **bool**. |
| virtual void [set_ShowValue](./set_showvalue/)(**bool**) | يمثل سلوك عرض قيمة النسبة المئوية لتسمية البيانات في مخطط محدد. True يعرض قيمة النسبة المئوية. False لإخفائها. كتابة **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يحدد الحجة النونية القالب كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشتركة. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد الإشارة المشتركة. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ تعبير C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |
## انظر أيضًا

* فئة [IFormattedTextContainer](../iformattedtextcontainer/)
* نطاق [Aspose::Slides::Charts](../)
* مكتبة [Aspose.Slides](../../)