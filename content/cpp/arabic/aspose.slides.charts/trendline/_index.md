---
title: Trendline
second_title: Aspose.Slides لـ C++ مرجع API
description: الفئة تمثل خط الاتجاه لسلسلة المخطط
type: docs
weight: 1366
url: /ar/aspose.slides.charts/trendline/
---
## Trendline الفئة

الفئة تمثل خط الاتجاه لسلسلة المخطط

```cpp
class Trendline : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::TrendlineCollection>>,
                  public Aspose::Slides::Charts::ITrendline
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | تقوم بتهيئة TextFrameForOverriding بالنص في المعامل "text". إذا كان TextFrameForOverriding مُهيئًا مسبقًا فسيتم ببساطة تغيير نصه. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقوم بمحاكاة مقارنة الأعداد العائمة بأسلوب C# حيث تُعتبر القيم NaN مزدوجة متساوية رغم أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقوم بمحاكاة مقارنة الأعداد العائمة بأسلوب C# حيث تُعتبر القيم NaN مزدوجة متساوية رغم أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **double** [get_Backward](./get_backward/)() override | يحدد عدد الفئات (أو الوحدات في مخطط مبعثر) التي يمتد خط الاتجاه قبل البيانات للسلسلة التي يتم تتبعها. في المخططات المبعثرة وغير المبعثرة، يجب أن تكون القيمة أي قيمة غير سالبة. قراءة **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | يرجع الرسم البياني الأصل. قراءة فقط [IChart](../ichart/). |
| **bool** [get_DisplayEquation](./get_displayequation/)() override | يحدد أن معادلة خط الاتجاه تُعرض على المخطط (في نفس التسمية مثل Rsquaredvalue). قراءة **bool**. |
| **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() override | يحدد أن قيمة R-squared لخط الاتجاه تُعرض على المخطط (في نفس التسمية مع المعادلة). قراءة **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | يمثل تنسيق خط الاتجاه. قراءة [IFormat](../iformat/). |
| **double** [get_Forward](./get_forward/)() override | يحدد عدد الفئات (أو الوحدات في مخطط مبعثر) التي يمتد خط الاتجاه بعد البيانات للسلسلة التي يتم تتبعها. في المخططات المبعثرة وغير المبعثرة، يجب أن تكون القيمة أي قيمة غير سالبة. قراءة **double**. |
| **double** [get_Intercept](./get_intercept/)() override | يحدد القيمة التي يقطع فيها خط الاتجاه المحور ص. يجب دعم هذه الخاصية فقط عندما يكون نوع خط الاتجاه exp أو linear أو poly. قراءة **double**. |
| **uint8_t** [get_Order](./get_order/)() override | يحدد ترتيب خط الاتجاه المتعدد الحدود. يتم تجاهله للأنواع الأخرى من خطوط الاتجاه. يجب أن تكون القيمة بين 2 و 6. قراءة **uint8_t**. |
| **uint8_t** [get_Period](./get_period/)() override | يحدد فترة خط الاتجاه لخط المتوسط المتحرك. يتم تجاهله للمتغيرات الأخرى من خطوط الاتجاه. يجب أن تكون القيمة بين 2 و 255. قراءة **uint8_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | يمثل إدخال دليل مرتبط بهذا خط الاتجاه. قراءة فقط [ILegendEntryProperties](../ilegendentryproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | يرجع تنسيق النص. قراءة فقط [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | يمكن أن يحتوي على نص منسق غني. إذا لم تكن هذه الخاصية فارغة (null) فإن قيمة النص المنسق تتجاوز النص المُولد تلقائيًا لتسمية البيانات. النص المُولد تلقائيًا لتسمية البيانات يعني النص الذي يديره ShowSeriesName، ShowValue، ... ويتم تنسيقه بخصائص TextFormatManager.TextFormat. قراءة فقط [ITextFrame](../../aspose.slides/itextframe/). |
| [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() override | يحصل على اسم خط الاتجاه. قراءة [System::String](../../system/string/). |
| [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() override | يحصل على نوع خط الاتجاه. قراءة [Charts::TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموضح بواسطة targetType. تناظر لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن بالمرجع كائن من النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجعية المشتركة بالقيمة المحددة. |
| void [set_Backward](./set_backward/)(**double**) override | يحدد عدد الفئات (أو الوحدات في مخطط مبعثر) التي يمتد خط الاتجاه قبل البيانات للسلسلة التي يتم تتبعها. في المخططات المبعثرة وغير المبعثرة، يجب أن تكون القيمة أي قيمة غير سالبة. كتابة **double**. |
| void [set_DisplayEquation](./set_displayequation/)(**bool**) override | يحدد أن معادلة خط الاتجاه تُعرض على المخطط (في نفس التسمية مثل Rsquaredvalue). كتابة **bool**. |
| void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) override | يحدد أن قيمة R-squared لخط الاتجاه تُعرض على المخطط (في نفس التسمية مع المعادلة). كتابة **bool**. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | يمثل تنسيق خط الاتجاه. كتابة [IFormat](../iformat/). |
| void [set_Forward](./set_forward/)(**double**) override | يحدد عدد الفئات (أو الوحدات في مخطط مبعثر) التي يمتد خط الاتجاه بعد البيانات للسلسلة التي يتم تتبعها. في المخططات المبعثرة وغير المبعثرة، يجب أن تكون القيمة أي قيمة غير سالبة. كتابة **double**. |
| void [set_Intercept](./set_intercept/)(**double**) override | يحدد القيمة التي يقطع فيها خط الاتجاه المحور ص. يجب دعم هذه الخاصية فقط عندما يكون نوع خط الاتجاه exp أو linear أو poly. كتابة **double**. |
| void [set_Order](./set_order/)(**uint8_t**) override | يحدد ترتيب خط الاتجاه المتعدد الحدود. يتم تجاهله للأنواع الأخرى من خطوط الاتجاه. يجب أن تكون القيمة بين 2 و 6. كتابة **uint8_t**. |
| void [set_Period](./set_period/)(**uint8_t**) override | يحدد فترة خط الاتجاه لخط المتوسط المتحرك. يتم تجاهله للمتغيرات الأخرى من خطوط الاتجاه. يجب أن تكون القيمة بين 2 و 255. كتابة **uint8_t**. |
| void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) override | يضبط اسم خط الاتجاه. كتابة [System::String](../../system/string/). |
| void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) override | يضبط نوع خط الاتجاه. كتابة [Charts::TrendlineType](../trendlinetype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | يضبط معامل القالب الـ n't كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجعية المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجعية المشتركة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجعية المشتركة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجعية الضعيفة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجعية الضعيفة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يفتن الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* الفئة [DomObject](../../aspose.slides/domobject/)
* الفئة [ITrendline](../itrendline/)
* مساحة الاسم [Aspose::Slides::Charts](../)
* المكتبة [Aspose.Slides](../../)