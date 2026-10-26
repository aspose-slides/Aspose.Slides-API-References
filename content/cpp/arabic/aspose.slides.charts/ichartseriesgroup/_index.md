---
title: IChartSeriesGroup
second_title: Aspose.Slides لمرجع API C++
description: يمثل مجموعة من السلاسل.
type: docs
weight: 846
url: /ar/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup فئة

يمثل مجموعة من السلاسل.

```cpp
class IChartSeriesGroup : public Aspose::Slides::Charts::IChartComponent
```

## طرق

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يعتبر NaNانان متساويين على الرغم من أن وفقًا لـ IEC 60559:1989 فإن NaN لا يساوي أي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يعتبر NaNانان متساويين على الرغم من أن وفقًا لـ IEC 60559:1989 فإن NaN لا يساوي أي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() | يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. قراءة [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() | يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300٪ من الحجم الافتراضي). قراءة **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | يعيد المخطط. للقراءة فقط [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | يعيد سلسلة المخطط في المجموعة عند الفهرس المحدد. |
| virtual **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() | يحدد حجم الفتحة في مخطط الدونت (يمكن أن يكون بين 10 و 90٪ من حجم منطقة الرسم). قراءة **uint8_t**. |
| virtual **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() | يحصل على زاوية أول شريحة من مخطط الفطيرة أو الدونت، بالدرجات (مع عقارب الساعة من الأعلى، من 0 إلى 360 درجة). قراءة **uint16_t**. |
| virtual **uint16_t** [get_GapDepth](./get_gapdepth/)() | يعيد المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. قراءة **uint16_t**. |
| virtual **uint16_t** [get_GapWidth](./get_gapwidth/)() | يحدد المسافة بين مجموعات الأشرطة أو الأعمدة، كنسبة مئوية من عرض العمود أو الشريط. قراءة **uint16_t**. |
| virtual **bool** [get_HasSeriesLines](./get_hasserieslines/)() | صحيح إذا كان المخطط يحتوي على خطوط السلسلة. يُطبق على مخططات الأشرطة المكدسة و OfPie. قراءة **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() | يحدد تنسيق HiLowLines. يتم تطبيق HiLowLines مع أنواع المخططات HiLowClose, OpenHiLowClose, VolumeHiLowClose و VolumeOpenHiLowClose. |
| virtual **bool** [get_IsColorVaried](./get_iscolorvaried/)() | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. قراءة **bool**. |
| virtual **int8_t** [get_Overlap](./get_overlap/)() | يحدد مقدار تداخل الأشرطة والأعمدة في المخططات ثنائية الأبعاد، كنسبة مئوية (من -100٪ إلى 100٪). |
| virtual [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() | يحدد كيفية تحديد أي نقاط البيانات توجد في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. قراءة [PieSplitType](../piesplittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) | معلومات الانقسام المخصص لمخطط pie-of-pie أو bar-of-pie مع انقسام مخصص. يعيد نقطة البيانات التي يجب رسمها في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie حسب الفهرس. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() | معلومات الانقسام المخصص لمخطط pie-of-pie أو bar-of-pie مع انقسام مخصص. يحتوي على نقاط البيانات التي يجب رسمها في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. للقراءة فقط [IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/). |
| virtual **double** [get_PieSplitPosition](./get_piesplitposition/)() | يحدد قيمة تُستخدم لتحديد أي نقاط البيانات توجد في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. يُستخدم مع خاصية PieSplitBy. قراءة **double**. |
| virtual **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() | يشير إذا كانت سلاسل هذه المجموعة مرسومة على المحور الثانوي. للقراءة فقط **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | يعيد العرض التقديمي. للقراءة فقط [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() | يحدد حجم الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن تكون بين 5 و 200٪). قراءة **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() | يعيد مجموعة قراءة فقط لسلاسل المخطط. للقراءة فقط [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | يعيد الشريحة الأساسية. للقراءة فقط [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() | يعيد نوع مجموعة السلاسل هذه. للقراءة فقط [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() | يوفر وصولًا إلى أشرطة الصعود/الهبوط في مخطط الخط أو المخطط السهمي. للقراءة فقط [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) | يحصل على العنصر عند الفهرس المحدد. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل مثيلاً للنوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدد الإشارات المشتركة بالقيمة المحددة. |
| virtual void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) | يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. كتابة [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) | يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300٪ من الحجم الافتراضي). كتابة **int32_t**. |
| virtual void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) | يحدد حجم الفتحة في مخطط الدونت (يمكن أن يكون بين 10 و 90٪ من حجم منطقة الرسم). كتابة **uint8_t**. |
| virtual void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) | يضبط زاوية أول شريحة من مخطط الفطيرة أو الدونت، بالدرجات (مع عقارب الساعة من الأعلى، من 0 إلى 360 درجة). كتابة **uint16_t**. |
| virtual void [set_GapDepth](./set_gapdepth/)(**uint16_t**) | يضبط المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. كتابة **uint16_t**. |
| virtual void [set_GapWidth](./set_gapwidth/)(**uint16_t**) | يحدد المسافة بين مجموعات الأشرطة أو الأعمدة، كنسبة مئوية من عرض العمود أو الشريط. كتابة **uint16_t**. |
| virtual void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) | صحيح إذا كان المخطط يحتوي على خطوط السلسلة. يُطبق على مخططات الأشرطة المكدسة و OfPie. كتابة **bool**. |
| virtual void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. كتابة **bool**. |
| virtual void [set_Overlap](./set_overlap/)(**int8_t**) | يحدد مقدار تداخل الأشرطة والأعمدة في المخططات ثنائية الأبعاد، كنسبة مئوية (من -100٪ إلى 100٪). |
| virtual void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) | يحدد كيفية تحديد أي نقاط البيانات توجد في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. كتابة [PieSplitType](../piesplittype/). |
| virtual void [set_PieSplitPosition](./set_piesplitposition/)(**double**) | يحدد قيمة تُستخدم لتحديد أي نقاط البيانات توجد في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. يُستخدم مع خاصية PieSplitBy. كتابة **double**. |
| virtual void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) | يحدد حجم الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن تكون بين 5 و 200٪). كتابة **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط المُعامل النوني في القالب إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشترك. لا ينبغي استدعاؤه مباشرةً؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد الإشارة المشترك. لا ينبغي استدعاؤه مباشرةً؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرةً؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرةً؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## ملاحظات

1) راجع الملخص والملاحظات الخاصة بفئة ChartSeriesGroupCollection و enum CombinableSeriesTypesGroup. 2) تحتوي مجموعة السلاسل على بعض خصائص السلاسل التي تكون مشتركة لكل سلسلة في المجموعة ("خصائص مجموعة السلاسل"). "خصائص مجموعة السلاسل" في الفئة [ChartSeriesGroup](../chartseriesgroup/) قابلة للقراءة والكتابة. كل من "خصائص مجموعة السلاسل" يمكن أن يكون لها تمثيل للقراءة فقط في الفئة [ChartSeries](../chartseries/).

## انظر أيضا

* الفئة [IChartComponent](../ichartcomponent/)
* النطاق [Aspose::Slides::Charts](../)
* المكتبة [Aspose.Slides](../../)