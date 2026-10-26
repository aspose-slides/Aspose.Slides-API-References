---
title: ITrendline
second_title: مرجع API لـ Aspose.Slides للغة C++
description: الفئة تمثل خط الاتجاه لسلسلة المخطط
type: docs
weight: 1223
url: /ar/aspose.slides.charts/itrendline/
---
## فئة ITrendline

الفئة تمثل خط الاتجاه لسلسلة المخطط

```cpp
class ITrendline : public Aspose::Slides::Charts::IOverridableText
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | تهيئ TextFrameForOverriding بالنص الموجود في المعامل "text". إذا كان TextFrameForOverriding مُهيأً مسبقًا فإنها تغير نصه ببساطة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين على الرغم من أنه وفقًا للمعيار IEC 60559:1989 فإن NaN لا تكون مساوية لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين على الرغم من أنه وفقًا للمعيار IEC 60559:1989 فإن NaN لا تكون مساوية لأي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual **double** [get_Backward](./get_backward/)() | يحدد عدد الفئات (أو الوحدات في مخطط مبعثر) التي يمتد إليها خط الاتجاه قبل البيانات الخاصة بالسلسلة التي يتم تتبعها. في المخططات المبعثرة وغير المبعثرة، يجب أن تكون القيمة أي قيمة غير سالبة. قراءة **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | يعيد المخطط. قراءة فقط [IChart](../ichart/). |
| virtual **bool** [get_DisplayEquation](./get_displayequation/)() | يحدد أن معادلة خط الاتجاه تُعرض على المخطط (في نفس التسمية مثل Rsquaredvalue). قراءة **bool**. |
| virtual **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() | يحدد أن قيمة R-squared لخط الاتجاه تُعرض على المخطط (في نفس التسمية مثل المعادلة). قراءة **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | يمثل تنسيق خط الاتجاه. قراءة [IFormat](../iformat/). |
| virtual **double** [get_Forward](./get_forward/)() | يحدد عدد الفئات (أو الوحدات في مخطط مبعثر) التي يمتد إليها خط الاتجاه بعد البيانات الخاصة بالسلسلة التي يتم تتبعها. في المخططات المبعثرة وغير المبعثرة، يجب أن تكون القيمة أي قيمة غير سالبة. قراءة **double**. |
| virtual **double** [get_Intercept](./get_intercept/)() | يحدد القيمة التي يتقاطع فيها خط الاتجاه مع محور الصادي. هذه الخاصية تدعم فقط عندما يكون نوع خط الاتجاه هو exp أو linear أو poly. قراءة **double**. |
| virtual **uint8_t** [get_Order](./get_order/)() | يحدد ترتيب خط الاتجاه المتعدد الحدود. يتم تجاهله للأنواع الأخرى من خطوط الاتجاه. يجب أن تكون القيمة بين 2 و6. قراءة **uint8_t**. |
| virtual **uint8_t** [get_Period](./get_period/)() | يحدد فترة خط الاتجاه لخط الاتجاه المتوسط المتحرك. يتم تجاهله للأنواع الأخرى من خطوط الاتجاه. يجب أن تكون القيمة بين 2 و255. قراءة **uint8_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | يعيد العرض التقديمي. قراءة فقط [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | يمثل عنصر الأسطورة المرتبط بهذا خط الاتجاه. قراءة فقط [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | يعيد الشريحة الأساسية. قراءة فقط [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | يعيد تنسيق نص المخطط. قراءة فقط [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | يمكن أن يحتوي على نص منسق غني. إذا لم تكن هذه الخاصية فارغة (null) فإن قيمة النص المنسق تتجاوز النص المُولد تلقائيًا. النص المُولد تلقائيًا هو خاصية ضمنية لتسمية البيانات، وتسمية وحدة العرض للمحور القيمي، وعنوان المحور، وعنوان المخطط، وتسمية خط الاتجاه. يتم تنسيق النص المُولد تلقائيًا باستخدام الخاصية [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). قراءة فقط [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() | يحصل على اسم خط الاتجاه. قراءة [System::String](../../system/string/). |
| virtual [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() | يحصل على نوع خط الاتجاه. قراءة [TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المراجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح إنشاء تجزئة للكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، فقط يهيء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا، فقط يهيء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعياً كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_Backward](./set_backward/)(**double**) | يحدد عدد الفئات (أو الوحدات في مخطط مبعثر) التي يمتد إليها خط الاتجاه قبل البيانات الخاصة بالسلسلة التي يتم تتبعها. في المخططات المبعثرة وغير المبعثرة، يجب أن تكون القيمة أي قيمة غير سالبة. كتابة **double**. |
| virtual void [set_DisplayEquation](./set_displayequation/)(**bool**) | يحدد أن معادلة خط الاتجاه تُعرض على المخطط (في نفس التسمية مثل Rsquaredvalue). كتابة **bool**. |
| virtual void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) | يحدد أن قيمة R-squared لخط الاتجاه تُعرض على المخطط (في نفس التسمية مثل المعادلة). كتابة **bool**. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | يمثل تنسيق خط الاتجاه. كتابة [IFormat](../iformat/). |
| virtual void [set_Forward](./set_forward/)(**double**) | يحدد عدد الفئات (أو الوحدات في مخطط مبعثر) التي يمتد إليها خط الاتجاه بعد البيانات الخاصة بالسلسلة التي يتم تتبعها. في المخططات المبعثرة وغير المبعثرة، يجب أن تكون القيمة أي قيمة غير سالبة. كتابة **double**. |
| virtual void [set_Intercept](./set_intercept/)(**double**) | يحدد القيمة التي يتقاطع فيها خط الاتجاه مع محور الصادي. هذه الخاصية تدعم فقط عندما يكون نوع خط الاتجاه هو exp أو linear أو poly. كتابة **double**. |
| virtual void [set_Order](./set_order/)(**uint8_t**) | يحدد ترتيب خط الاتجاه المتعدد الحدود. يتم تجاهله للأنواع الأخرى من خطوط الاتجاه. يجب أن تكون القيمة بين 2 و6. كتابة **uint8_t**. |
| virtual void [set_Period](./set_period/)(**uint8_t**) | يحدد فترة خط الاتجاه لخط الاتجاه المتوسط المتحرك. يتم تجاهله للأنواع الأخرى من خطوط الاتجاه. يجب أن تكون القيمة بين 2 و255. كتابة **uint8_t**. |
| virtual void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) | يضبط اسم خط الاتجاه. كتابة [System::String](../../system/string/). |
| virtual void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) | يضبط نوع خط الاتجاه. كتابة [TrendlineType](../trendlinetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي الـ n إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتبديل المؤشرات في الحاويات إلى وضع الضعف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ مُنشئ C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |
## انظر أيضًا

* فئة [IOverridableText](../ioverridabletext/)
* نطاق [Aspose::Slides::Charts](../)
* مكتبة [Aspose.Slides](../../)