---
title: ChartSeriesGroup
second_title: Aspose.Slides لـ C++ مرجع API
description: يمثل مجموعة من السلاسل.
type: docs
weight: 300
url: /ar/aspose.slides.charts/chartseriesgroup/
---
## فئة ChartSeriesGroup


Represents group of series.

```cpp
class ChartSeriesGroup : public Aspose::Slides::Charts::IChartSeriesGroup,
                         public Aspose::Slides::IDOMObject
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaN الاثنان متساويتين على الرغم من أنه وفقًا للمعيار IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaN الاثنان متساويتين على الرغم من أنه وفقًا للمعيار IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. اقرأ [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | يحدد معامل التحجيم لمخطط الفقاعات (يمكن أن يكون بين 0 و 300 ٪ من الحجم الافتراضي). اقرأ **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | يعيد المخطط الأصل. [IChart](../ichart/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | يعيد سلسلة المخطط في المجموعة عند الفهرس المحدد. |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | يحدد حجم الثقب في مخطط القالب (يمكن أن يكون بين 0 و 90 ٪ من حجم مساحة الرسم). اقرأ **uint8_t**. |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | يحصل على زاوية الشريحة الأولى من مخطط الفطيرة أو القالب، بالدرجات (مع اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). اقرأ **uint16_t**. |
| **uint16_t** [get_GapDepth](./get_gapdepth/)() override | يعيد المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. اقرأ **uint16_t**. |
| **uint16_t** [get_GapWidth](./get_gapwidth/)() override | يحدد المسافة بين مجموعات الأعمدة أو الشرائط، كنسبة مئوية من عرض العمود أو الشريط. اقرأ **uint16_t**. |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | صحيح إذا كان المخطط يحتوي على خطوط السلاسل. يُطبق على مخططات الأعمدة المتكدسة ومخططات OfPie. اقرأ **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() override | يحدد تنسيق HiLowLines. تُطبق HiLowLines مع أنواع المخططات HiLowClose و OpenHiLowClose و VolumeHiLowClose و VolumeOpenHiLowClose. |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. اقرأ **bool**. |
| **int8_t** [get_Overlap](./get_overlap/)() override | يحدد مقدار تداخل الأعمدة والشرائط في المخططات ثنائية الأبعاد، كنسبة مئوية (من -100٪ إلى 100٪). |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | يحدد كيفية تحديد أي نقاط البيانات توجد في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. اقرأ [PieSplitType](../piesplittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | معلومات التقسيم المخصَّص لمخطط pie-of-pie أو bar-of-pie مع تقسيم مخصَّص. يعيد نقطة البيانات التي يجب رسمها في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie حسب الفهرس. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | معلومات التقسيم المخصَّص لمخطط pie-of-pie أو bar-of-pie مع تقسيم مخصَّص. يحتوي على نقاط البيانات التي يجب رسمها في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. [PieSplitCustomPointCollection](../piesplitcustompointcollection/) للقراءة فقط. |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | يحدد قيمة تُستخدم لتحديد أي نقاط البيانات توجد في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. تُستخدم مع خاصية PieSplitBy. اقرأ **double**. |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | يشير إلى ما إذا كانت سلاسل هذه المجموعة مُرسَّمة على محور ثانوي. **bool** للقراءة فقط. |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | يحدد حجم الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200 ٪). اقرأ **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() override | يعيد مجموعة من السلاسل. [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/) للقراءة فقط. |
| [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() override | يعيد نوع مجموعة السلاسل هذه. [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() override | يوفر الوصول إلى أشرطة الصعود/الهبوط في مخطط الخط أو المخطط السهمي. [IUpDownBarsManager](../iupdownbarsmanager/) للقراءة فقط. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نسخة مشابهة لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). تمكِّن من تجزئة الكائنات المخصَّصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نسخة مشابهة لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) override | يحصل على العنصر عند الفهرس المحدد. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نسخة مشابهة لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نسخة مشابهة لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). تمكِّن من استنساخ الأنواع المخصَّصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | بناء نسخة. لا ينسخ أي شيء حقًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء حقًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يُقلل عداد المرجع المُشترك بالقيمة المحددة. |
| void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) override | يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. اكتب [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) override | يحدد معامل التحجيم لمخطط الفقاعات (يمكن أن يكون بين 0 و 300 ٪ من الحجم الافتراضي). اكتب **int32_t**. |
| void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) override | يحدد حجم الثقب في مخطط القالب (يمكن أن يكون بين 0 و 90 ٪ من حجم مساحة الرسم). اكتب **uint8_t**. |
| void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) override | يضبط زاوية الشريحة الأولى من مخطط الفطيرة أو القالب، بالدرجات (مع اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). اكتب **uint16_t**. |
| void [set_GapDepth](./set_gapdepth/)(**uint16_t**) override | يضبط المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. اكتب **uint16_t**. |
| void [set_GapWidth](./set_gapwidth/)(**uint16_t**) override | يحدد المسافة بين مجموعات الأعمدة أو الشرائط، كنسبة مئوية من عرض العمود أو الشريط. اكتب **uint16_t**. |
| void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) override | صحيح إذا كان المخطط يحتوي على خطوط السلاسل. يُطبق على مخططات الأعمدة المتكدسة و OfPie. اكتب **bool**. |
| void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) override | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. اكتب **bool**. |
| void [set_Overlap](./set_overlap/)(**int8_t**) override | يحدد مقدار تداخل الأعمدة والشرائط في المخططات ثنائية الأبعاد، كنسبة مئوية (من -100٪ إلى 100٪). |
| void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) override | يحدد كيفية تحديد أي نقاط البيانات توجد في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. اكتب [PieSplitType](../piesplittype/). |
| void [set_PieSplitPosition](./set_piesplitposition/)(**double**) override | يحدد قيمة تُستخدم لتحديد أي نقاط البيانات توجد في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. تُستخدم مع خاصية PieSplitBy. اكتب **double**. |
| void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) override | يحدد حجم الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200 ٪). اكتب **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n كإشارة ضعيفة (بدلاً من مشاركة). يسمح بتحويل الإشارات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المُشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المُشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يُقلل ويعيد عداد المرجع المُشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نسخة مشابهة لطريقة C# [Object.ToString()](../../system/object/tostring/). تمكِّن من تحويل الكائنات المخصَّصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يُقلل عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |
## ملاحظات

1) راجع الملخص والملاحظات لفئة ChartSeriesGroupCollection والعدد enum CombinableSeriesTypesGroup. 2) مجموعة السلاسل تحتوي على بعض خصائص السلسلة التي تكون مشتركة لكل سلسلة في المجموعة ("خصائص مجموعة السلسلة"). "خصائص مجموعة السلسلة" في فئة [ChartSeriesGroup](./) هي قراءة/كتابة. يمكن لكل من "خصائص مجموعة السلسلة" أن يكون لها إسقاط للقراءة فقط في فئة [ChartSeries](../chartseries/). 
## انظر أيضًا

* فئة [IChartSeriesGroup](../ichartseriesgroup/)
* فئة [IDOMObject](../../aspose.slides/idomobject/)
* نطاق الاسم [Aspose::Slides::Charts](../)
* مكتبة [Aspose.Slides](../../)