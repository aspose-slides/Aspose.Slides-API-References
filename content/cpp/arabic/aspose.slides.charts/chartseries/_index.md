---
title: ChartSeries
second_title: مرجع API Aspose.Slides للغة C++
description: يمثل سلسلة مخطط.
type: docs
weight: 274
url: /ar/aspose.slides.charts/chartseries/
---
## ChartSeries فئة

يمثل سلسلة مخطط.

```cpp
class ChartSeries : public Aspose::Slides::Charts::IChartSeries,
                    public Aspose::Slides::IDOMObject
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي على نمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي على نمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُ considered NaN مزدوجة متساوية بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُ considered NaN مزدوجة متساوية بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [ChartShapeType](../chartshapetype/) [get_Bar3DShape](./get_bar3dshape/)() override | يحدد شكل سلسلة في مخطط شريطي ثلاثي الأبعاد. تغيير قيمة هذه الخاصية يمكن أن يسبب تغيير نوع السلسلة تلقائيًا. اقرأ [ChartShapeType](../chartshapetype/). |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إسقاط للخاصية المناسبة للمجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_BubbleSizeRepresentation() خاصية قراءة/كتابة لتغيير القيمة. |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | يحدد معامل القياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300 بالمئة من الحجم الافتراضي). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إسقاط للخاصية المناسبة للمجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_BubbleSizeScale() خاصية قراءة/كتابة لتغيير القيمة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | يعيد المخطط الأصل. للقراءة فقط [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_DataPoint](./get_datapoint/)(**int32_t**) override | يعيد نقطة البيانات لهذه السلسلة عند الفهرس المحدد. |
| **int32_t** [get_DataPoint](./get_datapoint/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointCollection](../ichartdatapointcollection/)\> [get_DataPoints](./get_datapoints/)() override | يعيد مجموعة نقاط البيانات لهذه السلسلة. للقراءة فقط [IChartDataPointCollection](../ichartdatapointcollection/). |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | يحدد حجم الثقب في مخطط الدونات (يمكن أن يكون بين 10 و 90 بالمئة من حجم منطقة الرسم). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إسقاط للخاصية المناسبة للمجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_DoughnutHoleSize() خاصية قراءة/كتابة لتغيير القيمة. للقراءة فقط **uint8_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsFormat](../ierrorbarsformat/)\> [get_ErrorBarsXFormat](./get_errorbarsxformat/)() override | يمثل أشرطة الخطأ للسلسلة باتجاه X. |
| [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsFormat](../ierrorbarsformat/)\> [get_ErrorBarsYFormat](./get_errorbarsyformat/)() override | يمثل أشرطة الخطأ للسلسلة باتجاه Y. |
| **int32_t** [get_Explosion](./get_explosion/)() override | المسافة بين شريحة الفطيرة المفتوحة ومركز مخطط الفطيرة تُعبر عنها كنسبة مئوية من قطر الفطيرة. اقرأ **int32_t**. |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | يحدد زاوية أول شريحة في مخطط الفطيرة أو الدونات، بالدرجات (مع اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إسقاط للخاصية المناسبة للمجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_FirstSliceAngle() خاصية قراءة/كتابة لتغيير القيمة. للقراءة فقط **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | يعيد تنسيق السلسلة. للقراءة فقط [IFormat](../iformat/). |
| **int32_t** [get_GapDepth](./get_gapdepth/)() override | يعيد المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إسقاط للخاصية المناسبة للمجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_GapDepth() خاصية قراءة/كتابة لتغيير القيمة. للقراءة فقط **int32_t**. |
| **int32_t** [get_GapWidth](./get_gapwidth/)() override | يحدد المسافة بين مجموعات الأعمدة أو الشريط، كنسبة مئوية من عرض الشريط أو العمود. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إسقاط للخاصية المناسبة للمجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_GapWidth() خاصية قراءة/كتابة لتغيير القيمة. للقراءة فقط **int32_t**. |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | يحدد ما إذا كانت هناك خطوط سلاسل لهذه السلسلة والسلاسل المرتبطة. هذه الخاصية للقراءة فقط. استخدم [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_HasSeriesLines() خاصية قراءة/كتابة لتغيير القيمة. استخدم خاصية ParentSeriesGroup.SeriesLinesFormat لتنسيق خطوط السلسلة. للقراءة فقط **bool**. |
| **bool** [get_HasUpDownBars](./get_hasupdownbars/)() override | يحدد ما إذا كان مخطط الخط أو المخطط السهمي يحتوي على أشرطة صعود/هبوط. هذه الخاصية للقراءة فقط. استخدم [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get_UpDownBars()->get(set)_HasUpDownBars() خاصية قراءة/كتابة لتغيير القيمة. استخدم خاصية [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get_UpDownBars() لتنسيق أشرطة الصعود/الهبوط. للقراءة فقط **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_InvertedSolidFillColor](./get_invertedsolidfillcolor/)() override | يحدد عكس اللون الصلب للسلسلة. لتطبيق إعداد اللون اضبط خاصية FillType في تنسيق السلسلة إلى [FillType::Solid](../../aspose.slides/filltype/). اقرأ [ColorFormat](../../aspose.slides/colorformat/). |
| **bool** [get_InvertIfNegative](./get_invertifnegative/)() override | يحدد أن شريط أو عمود أو سلسلة فقاعات ستعكس ألوانها إذا كانت القيمة سلبية. اقرأ **bool**. |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. هذه الخاصية للقراءة فقط. استخدم [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_IsColorVaried() خاصية قراءة/كتابة لتغيير القيمة. للقراءة فقط **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)(**int32_t**) override | يعيد تسمية البيانات لنقطة البيانات في هذه السلسلة عند الفهرس المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelCollection](../idatalabelcollection/)\> [get_Labels](./get_labels/)() override | يعيد التسميات لسلسلة. للقراءة فقط [IDataLabelCollection](../idatalabelcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() override | [Marker](../marker/). للقراءة فقط [IMarker](../imarker/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IStringChartValue](../istringchartvalue/)\> [get_Name](./get_name/)() override | إرجاع اسم السلسلة. للقراءة فقط [IStringChartValue](../istringchartvalue/). |
| [System::String](../../system/string/) [get_NumberFormatOfBubbleSizes](./get_numberformatofbubblesizes/)() override | NumberFormatOfBubbleSizes. اقرأ [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_NumberFormatOfValues](./get_numberformatofvalues/)() override | NumberFormatOfValues. اقرأ [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_NumberFormatOfXValues](./get_numberformatofxvalues/)() override | NumberFormatOfXValues. اقرأ [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_NumberFormatOfYValues](./get_numberformatofyvalues/)() override | NumberFormatOfYValues. اقرأ [System::String](../../system/string/). |
| **int32_t** [get_Order](./get_order/)() override | يعيد ترتيب السلسلة. اقرأ **int32_t**. |
| **int8_t** [get_Overlap](./get_overlap/)() override | يحدد مقدار تداخل الأشرطة والأعمدة في المخططات الثنائية الأبعاد، كنسبة مئوية (من -100% إلى 100%). هذه الخاصية للقراءة فقط. لتغيير القيمة، استخدم خاصية [get_ParentSeriesGroup()->Overlap()](./get_parentseriesgroup/) قراءة/كتابة. للقراءة فقط **int8_t**. |
| [ParentLabelLayoutType](../parentlabellayouttype/) [get_ParentLabelLayout](./get_parentlabellayout/)() override | يمثل تخطيط تسميات الفئات الأصلية. يُطبق فقط على مخططات شجرة الخريطة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ParentSeries](./get_parentseries/)(**int32_t**) override | يعيد سلاسل المخطط في مجموعة السلسلة الأصلية عند الفهرس المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_ParentSeriesGroup](./get_parentseriesgroup/)() override | ParentSeriesGroup. للقراءة فقط [IChartSeriesGroup](../ichartseriesgroup/). |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | يحدد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة. هذه الخاصية للقراءة فقط. استخدم [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_PieSplitBy() خاصية قراءة/كتابة لتغيير القيمة. للقراءة فقط [PieSplitType](../piesplittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | معلومات الانقسام المخصصة ... يعيد نقطة البيانات التي يجب رسمها في الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة عند الفهرس المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | معلومات الانقسام المخصصة ... يحتوي على نقاط البيانات ... هذه الخاصية للقراءة فقط [PieSplitCustomPointCollection](../piesplitcustompointcollection/). |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | يحدد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة. تُستخدم مع خاصية PieSplitBy. هذه الخاصية للقراءة فقط. استخدم [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_PieSplitPosition() خاصية قراءة/كتابة لتغيير القيمة. للقراءة فقط **double**. |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | يشير إذا ما تم رسم هذه السلسلة على محور ثانوي. اقرأ **bool**. |
| [QuartileMethodType](../quartilemethodtype/) [get_QuartileMethod](./get_quartilemethod/)() override | يمثل طريقة الأرباع. يُطبق فقط على مخططات BoxAndWhisker. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | يمثل مدخل الأسطورة المتعلق بهذه السلسلة. للقراءة فقط [ILegendEntryProperties](../ilegendentryproperties/). |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | يحدد حجم الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200 بالمئة). هذه الخاصية للقراءة فقط. استخدم [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_SecondPieSize() خاصية قراءة/كتابة لتغيير القيمة. للقراءة فقط **uint16_t**. |
| **bool** [get_ShowConnectorLines](./get_showconnectorlines/)() override | يمثل خطوط الموصل. ينطبق فقط على مخططات Waterfall. |
| **bool** [get_ShowInnerPoints](./get_showinnerpoints/)() override | يمثل النقاط الداخلية. صحيح إذا تم إظهار النقاط الداخلية على مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قراءة **bool**. |
| **bool** [get_ShowMeanLine](./get_showmeanline/)() override | يمثل خط المتوسط. صحيح إذا تم إظهار خط المتوسط على مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قراءة **bool**. |
| **bool** [get_ShowMeanMarkers](./get_showmeanmarkers/)() override | يمثل علامات المتوسط. صحيح إذا تم إظهار علامات المتوسط على مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قراءة **bool**. |
| **bool** [get_ShowOutlierPoints](./get_showoutlierpoints/)() override | يمثل نقاط القيم المتطرفة. صحيح إذا تم إظهار نقاط القيم المتطرفة على مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قراءة **bool**. |
| **bool** [get_Smooth](./get_smooth/)() override | يمثل تنعيم المنحنى. صحيح إذا تم تشغيل تنعيم المنحنى لمخطط الخط أو مخطط التشتت. ينطبق فقط على مخططات الخط ومخططات التشتت المتصلة بخطوط. قراءة **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITrendline](../itrendline/)\> [get_TrendLine](./get_trendline/)(**int32_t**) override | يرجع خط الاتجاه عند الفهرس المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITrendlineCollection](../itrendlinecollection/)\> [get_TrendLines](./get_trendlines/)() override | مجموعة خطوط الاتجاه للسلسلة. للقراءة فقط [ITrendlineCollection](../itrendlinecollection/). |
| [ChartType](../charttype/) [get_Type](./get_type/)() override | يرجع نوع هذه السلسلة. قراءة [ChartType](../charttype/). |
| [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticSeriesColor](./getautomaticseriescolor/)() override | يرجع لونًا تلقائيًا للسلسلة بناءً على فهرس السلسلة ونمط المخطط. يُستخدم هذا اللون افتراضيًا إذا كان FillType يساوي NotDefined. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. تماثل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ تأمين عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يتهيئ جميع هياكل البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، بل يتهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يتهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائنًا من نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_Bar3DShape](./set_bar3dshape/)([ChartShapeType](../chartshapetype/)) override | يحدد شكل سلسلة من مخطط شريطي ثلاثي الأبعاد. يمكن لتغيير قيمة هذه الخاصية أن يسبب تغييرًا تلقائيًا لنوع السلسلة. كتابة [ChartShapeType](../chartshapetype/). |
| void [set_Explosion](./set_explosion/)(**int32_t**) override | المسافة بين شريحة فطيرة مفتوحة ومركز مخطط الفطيرة معبر عنها كنسبة مئوية من قطر الفطيرة. كتابة **int32_t**. |
| void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) override | يحدد أن السلسلة الشريطية أو العمودية أو الفقاعية تقلب ألوانها إذا كانت القيمة سالبة. كتابة **bool**. |
| void [set_NumberFormatOfBubbleSizes](./set_numberformatofbubblesizes/)([System::String](../../system/string/)) override | NumberFormatOfBubbleSizes. كتابة [System::String](../../system/string/). |
| void [set_NumberFormatOfValues](./set_numberformatofvalues/)([System::String](../../system/string/)) override | NumberFormatOfValues. كتابة [System::String](../../system/string/). |
| void [set_NumberFormatOfXValues](./set_numberformatofxvalues/)([System::String](../../system/string/)) override | NumberFormatOfXValues. كتابة [System::String](../../system/string/). |
| void [set_NumberFormatOfYValues](./set_numberformatofyvalues/)([System::String](../../system/string/)) override | NumberFormatOfYValues. كتابة [System::String](../../system/string/). |
| void [set_Order](./set_order/)(**int32_t**) override | يرجع ترتيب سلسلة. كتابة **int32_t**. |
| void [set_ParentLabelLayout](./set_parentlabellayout/)([ParentLabelLayoutType](../parentlabellayouttype/)) override | يمثل تخطيط تسميات الفئات الأم. ينطبق فقط على مخططات Treemap. |
| void [set_PlotOnSecondAxis](./set_plotonsecondaxis/)(**bool**) override | يشير إلى ما إذا كانت هذه السلسلة مرسومة على المحور الثانوي. كتابة **bool**. |
| void [set_QuartileMethod](./set_quartilemethod/)([QuartileMethodType](../quartilemethodtype/)) override | يمثل طريقة الربع. ينطبق فقط على مخططات BoxAndWhisker. |
| void [set_ShowConnectorLines](./set_showconnectorlines/)(**bool**) override | يمثل خطوط الموصل. ينطبق فقط على مخططات Waterfall. |
| void [set_ShowInnerPoints](./set_showinnerpoints/)(**bool**) override | يمثل النقاط الداخلية. صحيح إذا تم إظهار النقاط الداخلية على مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. كتابة **bool**. |
| void [set_ShowMeanLine](./set_showmeanline/)(**bool**) override | يمثل خط المتوسط. صحيح إذا تم إظهار خط المتوسط على مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. كتابة **bool**. |
| void [set_ShowMeanMarkers](./set_showmeanmarkers/)(**bool**) override | يمثل علامات المتوسط. صحيح إذا تم إظهار علامات المتوسط على مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. كتابة **bool**. |
| void [set_ShowOutlierPoints](./set_showoutlierpoints/)(**bool**) override | يمثل نقاط القيم المتطرفة. صحيح إذا تم إظهار نقاط القيم المتطرفة على مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. كتابة **bool**. |
| void [set_Smooth](./set_smooth/)(**bool**) override | يمثل تنعيم المنحنى. صحيح إذا تم تشغيل تنعيم المنحنى لمخطط الخط أو مخطط التشتت. ينطبق فقط على مخططات الخط ومخططات التشتت المتصلة بخطوط. كتابة **bool**. |
| void [set_Type](./set_type/)([ChartType](../charttype/)) override | يرجع نوع هذه السلسلة. كتابة [ChartType](../charttype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n كمرجع ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ بل użyالمؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك تأمين عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |
## انظر أيضًا

* فئة [IChartSeries](../ichartseries/)
* فئة [IDOMObject](../../aspose.slides/idomobject/)
* نطاق [Aspose::Slides::Charts](../)
* مكتبة [Aspose.Slides](../../)