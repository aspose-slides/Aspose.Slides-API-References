---
title: DataLabelFormat
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل خيارات التنسيق لتسمية البيانات.
type: docs
weight: 391
url: /ar/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat فئة

يمثل خيارات تنسيق لـ [DataLabel](../datalabel/).

```cpp
class DataLabelFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::Charts::IDataLabelFormat
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يقارن مع الكائن المحدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNين مساويين على الرغم من أن IEC 60559:1989 يوضح أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة ذات الدقة المزدوجة بأسلوب C# حيث يُعتبر NaNين مساويين على الرغم من أن IEC 60559:1989 يوضح أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لغرض داخلي فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | يرجع المخطط. قراءة فقط [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | يمثل تنسيق تسمية البيانات. قراءة فقط [IFormat](../iformat/). |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | قراءة **bool**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | يمثل سلسلة التنسيق لكائن DataLabels. قراءة [System::String](../../system/string/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | يرجع كائن Parent_Immediate. قراءة فقط [IDOMObject](../../aspose.slides/idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | يرجع الأب [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). قراءة فقط [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() override | يمثل موضع تسمية البيانات. قراءة [LegendDataLabelPosition](../legenddatalabelposition/). |
| [System::String](../../system/string/) [get_Separator](./get_separator/)() override | يضبط أو يرجع Variant يمثل الفاصل المستخدم لتسميات البيانات على المخطط. قراءة [System::String](../../system/string/). |
| **bool** [get_ShowBubbleSize](./get_showbubblesize/)() override | يمثل سلوك عرض قيمة حجم الفقاعة لتسمية البيانات في المخطط المحدد. True يعرض قيمة حجم الفقاعة. False لإخفائها. قراءة **bool**. |
| **bool** [get_ShowCategoryName](./get_showcategoryname/)() override | يمثل سلوك عرض اسم الفئة لتسمية البيانات في المخطط المحدد. True لعرض اسم الفئة لتسميات البيانات على المخطط. False للإخفاء. قراءة **bool**. |
| **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() override | يحدد ما إذا كانت تسمية البيانات في المخطط المحدد ستُعرض كإشارة بيانات أو كتسمية بيانات. |
| **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() override | يمثل سلوك عرض قيمة الخلية لتسمية البيانات في المخطط المحدد. True يعرض قيمة الخلية. False لإخفائها. قراءة **bool**. |
| **bool** [get_ShowLeaderLines](./get_showleaderlines/)() override | يمثل سلوك عرض خطوط القائد لتسمية البيانات في المخطط المحدد. True يعرض خطوط القائد. False لإخفائها. قراءة **bool**. |
| **bool** [get_ShowLegendKey](./get_showlegendkey/)() override | يمثل سلوك عرض مفتاح وسيلة الإيضاح لتسمية البيانات في المخطط المحدد. True إذا كان مفتاح وسيلة الإيضاح مرئيًا. قراءة **bool**. |
| **bool** [get_ShowPercentage](./get_showpercentage/)() override | يمثل سلوك عرض قيمة النسبة المئوية لتسمية البيانات في المخطط المحدد. True يعرض قيمة النسبة المئوية. False لإخفائها. قراءة **bool**. |
| **bool** [get_ShowSeriesName](./get_showseriesname/)() override | يرجع قيمة منطقية لتحديد سلوك عرض اسم السلسلة لتسميات البيانات على المخطط. True لإظهار اسم السلسلة. False للإخفاء. قراءة **bool**. |
| **bool** [get_ShowValue](./get_showvalue/)() override | يمثل سلوك عرض قيمة النسبة المئوية لتسمية البيانات في المخطط المحدد. True يعرض قيمة النسبة المئوية. False لإخفائها. قراءة **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | يرجع تنسيق نص المخطط. قراءة فقط [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | يرجع الكود التجزيئي. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مشابه لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص إذا كان الكائن يمثل مثيلاً للنوع الموصوف بـ targetType. مشابه لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يطبق قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويفعّل إنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويفعّل إنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بواسطة المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بواسطة المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة بـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | اكتب **bool**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | يمثل سلسلة تنسيق كائن DataLabels. كتابة [System::String](../../system/string/). |
| void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) override | يمثل موضع تسمية البيانات. كتابة [LegendDataLabelPosition](../legenddatalabelposition/). |
| void [set_Separator](./set_separator/)([System::String](../../system/string/)) override | يضبط أو يرجع Variant يمثل الفاصل المستخدم لتسميات البيانات على المخطط. كتابة [System::String](../../system/string/). |
| void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) override | يمثل سلوك عرض قيمة حجم الفقاعة لتسمية البيانات في المخطط المحدد. True يعرض قيمة حجم الفقاعة. False للإخفاء. كتابة **bool**. |
| void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) override | يمثل سلوك عرض اسم الفئة لتسمية البيانات في المخطط المحدد. True لعرض اسم الفئة لتسميات البيانات على المخطط. False للإخفاء. كتابة **bool**. |
| void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) override | يحدد ما إذا كانت تسمية البيانات في المخطط المحدد ستُعرض كإشارة بيانات أو كتسمية بيانات. |
| void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) override | يمثل سلوك عرض قيمة الخلية لتسمية البيانات في المخطط المحدد. True يعرض قيمة الخلية. False للإخفاء. كتابة **bool**. |
| void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) override | يمثل سلوك عرض خطوط القائد لتسمية البيانات في المخطط المحدد. True يعرض خطوط القائد. False للإخفاء. كتابة **bool**. |
| void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) override | يمثل سلوك عرض مفتاح وسيلة الإيضاح لتسمية البيانات في المخطط المحدد. True إذا كان مفتاح وسيلة الإيضاح مرئيًا. كتابة **bool**. |
| void [set_ShowPercentage](./set_showpercentage/)(**bool**) override | يمثل سلوك عرض قيمة النسبة المئوية لتسمية البيانات في المخطط المحدد. True يعرض قيمة النسبة المئوية. False للإخفاء. كتابة **bool**. |
| void [set_ShowSeriesName](./set_showseriesname/)(**bool**) override | يضبط قيمة منطقية لتحديد سلوك عرض اسم السلسلة لتسميات البيانات على المخطط. True لإظهار اسم السلسلة. False للإخفاء. كتابة **bool**. |
| void [set_ShowValue](./set_showvalue/)(**bool**) override | يمثل سلوك عرض قيمة النسبة المئوية لتسمية البيانات في المخطط المحدد. True يعرض قيمة النسبة المئوية. False للإخفاء. كتابة **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يعيّن الوسيط القالبي الـ n'th كمؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقوم بخفض وإرجاع عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبق إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقوم بخفض عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [PVIObject](../../aspose.slides/pviobject/)
* فئة [IDataLabelFormat](../idatalabelformat/)
* نطاق [Aspose::Slides::Charts](../)
* مكتبة [Aspose.Slides](../../)