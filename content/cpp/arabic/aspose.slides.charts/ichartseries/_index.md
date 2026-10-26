---
title: IChartSeries
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل سلسلة مخطط.
type: docs
weight: 820
url: /ar/aspose.slides.charts/ichartseries/
---
## IChartSeries فئة


يمثل سلسلة مخطط.

```cpp
class IChartSeries : public Aspose::Slides::Charts::IChartComponent
```

## الطرق

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام C# [Object.Equals](../../system/object/equals/) الدلالات. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNانين متساويين بالرغم من أنه وفقًا لـ IEC 60559:1989 NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNانين متساويين بالرغم من أنه وفقًا لـ IEC 60559:1989 NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [ChartShapeType](../chartshapetype/) [get_Bar3DShape](./get_bar3dshape/)() | يحدد شكل مجموعة من مخطط شريطي ثلاثي الأبعاد. قد يتسبب تغيير قيمة هذه الخاصية في تغيير نوع السلسلة تلقائيًا. اقرأ [ChartShapeType](../chartshapetype/). |
| virtual [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() | يحدد كيف يتم تمثيل قيم حجم الفقاعات في مخطط الفقاعات. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - وهي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_BubbleSizeRepresentation() خاصية قراءة/كتابة لتغيير القيمة. |
| virtual **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() | يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300 بالمائة من الحجم الافتراضي). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - وهي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_BubbleSizeScale() خاصية قراءة/كتابة لتغيير القيمة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | يُعيد المخطط. قراءة فقط [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_DataPoint](./get_datapoint/)(**int32_t**) | يُعيد نقطة البيانات لهذه السلسلة عند الفهرس المحدد. |
| virtual **int32_t** [get_DataPoint](./get_datapoint/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointCollection](../ichartdatapointcollection/)\> [get_DataPoints](./get_datapoints/)() | يُعيد مجموعة نقاط البيانات لهذه السلسلة. قراءة فقط [IChartDataPointCollection](../ichartdatapointcollection/). |
| virtual **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() | يحدد حجم الفتحة في مخطط الدونات (يمكن أن يكون بين 10 و 90 بالمائة من حجم مساحة الرسم). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - وهي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_DoughnutHoleSize() خاصية قراءة/كتابة لتغيير القيمة. قراءة فقط **uint8_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsFormat](../ierrorbarsformat/)\> [get_ErrorBarsXFormat](./get_errorbarsxformat/)() | يمثل أشرطة الخطأ للسلسلة باتجاه X. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsFormat](../ierrorbarsformat/)\> [get_ErrorBarsYFormat](./get_errorbarsyformat/)() | يمثل أشرطة الخطأ للسلسلة باتجاه Y. |
| virtual **int32_t** [get_Explosion](./get_explosion/)() | تُعبّر مسافة شريحة الفطيرة المفتوحة من مركز مخطط الفطيرة كنسبة مئوية من قطر الفطيرة. قراءة **int32_t**. |
| virtual **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() | يحدد زاوية أول شريحة فطيرة أو دونات، بالدرجات (مع عقرب الساعة من الأعلى، من 0 إلى 360 درجة). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - وهي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_FirstSliceAngle() خاصية قراءة/كتابة لتغيير القيمة. قراءة فقط **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | يُعيد تنسيق السلسلة. قراءة فقط [IFormat](../iformat/). |
| virtual **int32_t** [get_GapDepth](./get_gapdepth/)() | يُعيد المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - وهي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_GapDepth() خاصية قراءة/كتابة لتغيير القيمة. قراءة فقط **int32_t**. |
| virtual **int32_t** [get_GapWidth](./get_gapwidth/)() | يحدد المسافة بين مجموعات الأعمدة أو الأشرطة، كنسبة مئوية من عرض العمود أو الشريط. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - وهي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_GapWidth() خاصية قراءة/كتابة لتغيير القيمة. قراءة فقط **int32_t**. |
| virtual **bool** [get_HasSeriesLines](./get_hasserieslines/)() | يحدد ما إذا كانت هناك خطوط سلاسل لهذه السلسلة والسلاسل ذات الصلة. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - وهي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_HasSeriesLines() خاصية قراءة/كتابة لتغيير القيمة. استخدم خاصية ParentSeriesGroup.SeriesLinesFormat لتنسيق خطوط السلاسل. قراءة فقط **bool**. |
| virtual **bool** [get_HasUpDownBars](./get_hasupdownbars/)() | يحدد ما إذا كان مخطط الخط أو المخطط الشريطي يحتوي على أشرطة صعود/هبوط. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - وهي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get_UpDownBars()->get(set)_HasUpDownBars() خاصية قراءة/كتابة لتغيير القيمة. استخدم خاصية [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get_UpDownBars() لتنسيق أشرطة الصعود/الهبوط. قراءة فقط **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_InvertedSolidFillColor](./get_invertedsolidfillcolor/)() | يحدد اللون الصلب المعكوس للسلسلة. لتطبيق إعداد اللون اضبط FillType للسلسلة إلى [FillType::Solid](../../aspose.slides/filltype/). قراءة [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual **bool** [get_InvertIfNegative](./get_invertifnegative/)() | يحدد ما إذا كانت السلسلة الشريطية أو العمودية أو الفقاعية تعكس ألوانها إذا كانت القيمة سالبة. قراءة **bool**. |
| virtual **bool** [get_IsColorVaried](./get_iscolorvaried/)() | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - وهي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_IsColorVaried() خاصية قراءة/كتابة لتغيير القيمة. قراءة فقط **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)(**int32_t**) | يُعيد تسمية البيانات لنقطة البيانات لهذه السلسلة عند الفهرس المحدد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelCollection](../idatalabelcollection/)\> [get_Labels](./get_labels/)() | يُعيد تسميات السلسلة. قراءة فقط [IDataLabelCollection](../idatalabelcollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() | يُعيد علامة السلسلة. قراءة فقط [IMarker](../imarker/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IStringChartValue](../istringchartvalue/)\> [get_Name](./get_name/)() | يُعيد اسم السلسلة. قراءة فقط [IStringChartValue](../istringchartvalue/). |
| virtual [System::String](../../system/string/) [get_NumberFormatOfBubbleSizes](./get_numberformatofbubblesizes/)() | يُعيد تنسيق الرقم لأحجام فقاعات السلسلة. قراءة [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_NumberFormatOfValues](./get_numberformatofvalues/)() | يُعيد تنسيق الرقم لقيم السلسلة. قراءة [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_NumberFormatOfXValues](./get_numberformatofxvalues/)() | يُعيد تنسيق الرقم لقيم السلسلة السينية. قراءة [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_NumberFormatOfYValues](./get_numberformatofyvalues/)() | يُعيد تنسيق الرقم لقيم السلسلة الصادية. قراءة [System::String](../../system/string/). |
| virtual **int32_t** [get_Order](./get_order/)() | يُعيد ترتيب السلسلة. قراءة **int32_t**. |
| virtual **int8_t** [get_Overlap](./get_overlap/)() | يحدد مقدار تداخل الأشرطة والأعمدة في المخططات ذات البعدين، كنسبة مئوية (من -100% إلى 100%). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية. إنها إسقاط للخاصية المناسبة في مجموعة السلسلة الأصلية، وبالتالي هذه الخاصية للقراءة فقط. لتغيير القيمة، استخدم خاصية [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_Overlap() قراءة/كتابة. قراءة فقط **int8_t**. |
| virtual [ParentLabelLayoutType](../parentlabellayouttype/) [get_ParentLabelLayout](./get_parentlabellayout/)() | يمثل تخطيط تسميات الفئات الأصلية. يُطبق فقط على مخططات الشجرة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](./)\> [get_ParentSeries](./get_parentseries/)(**int32_t**) | يُعيد سلسلة المخطط في مجموعة السلاسل الأصلية عند الفهرس المحدد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_ParentSeriesGroup](./get_parentseriesgroup/)() | يُعيد مجموعة السلسلة الأصلية. قراءة فقط [IChartSeriesGroup](../ichartseriesgroup/). |
| virtual [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() | يحدد كيفية تحديد نقاط البيانات التي تكون في الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - وهي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_PieSplitBy() خاصية قراءة/كتابة لتغيير القيمة. قراءة فقط [PieSplitType](../piesplittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) | معلومات الانقسام المخصصة لمخطط فطيرة-من-فطيرة أو شريط-من-شريط مع انقسام مخصص. يُعيد نقطة البيانات التي يجب رسمها في الفطيرة أو الشريط الثاني عند الفهرس المحدد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() | معلومات الانقسام المخصص لمخطط فطيرة-من-فطيرة أو شريط-من-شريط مع انقسام مخصص. تحتوي على نقاط البيانات التي يجب رسمها في الفطيرة أو الشريط الثاني. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - وهي إسقاط للخاصية المناسبة في المجموعة. قراءة فقط [IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/). |
| virtual **double** [get_PieSplitPosition](./get_piesplitposition/)() | يحدد قيمة تُستخدم لتحديد نقاط البيانات التي تكون في الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-شريط. يُستخدم مع خاصية PieSplitBy. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - وهي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_PieSplitPosition() خاصية قراءة/كتابة لتغيير القيمة. قراءة فقط **double**. |
| virtual **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() | يوضح ما إذا كانت هذه السلسلة مرسومة على محور القيم الثاني. قراءة **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | يُعيد العرض التقديمي. قراءة فقط [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [QuartileMethodType](../quartilemethodtype/) [get_QuartileMethod](./get_quartilemethod/)() | يمثل طريقة الربع. يُطبق فقط على مخططات الصندوق والوشاح. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | يمثل مدخل أسطورة مرتبط بهذه السلسلة. قراءة فقط [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() | يحدد حجم الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-شريط كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200 بالمائة). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - وهي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_SecondPieSize() خاصية قراءة/كتابة لتغيير القيمة. قراءة فقط **uint16_t**. |
| virtual **bool** [get_ShowConnectorLines](./get_showconnectorlines/)() | يمثل خطوط الموصل. يُطبق فقط على مخططات الشلال. |
| virtual **bool** [get_ShowInnerPoints](./get_showinnerpoints/)() | يمثل النقاط الداخلية. صحيح إذا كانت النقاط الداخلية معروضة على مخطط الصندوق والوشاح. يُطبق فقط على مخططات الصندوق والوشاح. قراءة **bool**. |
| virtual **bool** [get_ShowMeanLine](./get_showmeanline/)() | يمثل علامات المتوسط. صحيح إذا كانت خط المتوسط معروض على مخطط الصندوق والوشاح. يُطبق فقط على مخططات الصندوق والوشاح. قراءة **bool**. |
| virtual **bool** [get_ShowMeanMarkers](./get_showmeanmarkers/)() | يمثل علامات المتوسط. صحيح إذا كانت علامات المتوسط معروضة على مخطط الصندوق والوشاح. يُطبق فقط على مخططات الصندوق والوشاح. قراءة **bool**. |
| virtual **bool** [get_ShowOutlierPoints](./get_showoutlierpoints/)() | يمثل نقاط الشذوذ. صحيح إذا كانت نقاط الشذوذ معروضة على مخطط الصندوق والوشاح. يُطبق فقط على مخططات الصندوق والوشاح. قراءة **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | يُعيد الشريحة الأساسية. قراءة فقط [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual **bool** [get_Smooth](./get_smooth/)() | يمثل تنعيم المنحنى. صحيح إذا كان تنعيم المنحنى مفعلاً لمخطط الخط أو المخطط المتناثر. يُطبق فقط على مخططات الخط والمتناثر المتصلة بالخطوط. قراءة **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITrendline](../itrendline/)\> [get_TrendLine](./get_trendline/)(**int32_t**) | يُعيد خط الاتجاه عند الفهرس المحدد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITrendlineCollection](../itrendlinecollection/)\> [get_TrendLines](./get_trendlines/)() | مجموعة خطوط اتجاه السلسلة. قراءة فقط [ITrendlineCollection](../itrendlinecollection/). |
| virtual [ChartType](../charttype/) [get_Type](./get_type/)() | يُعيد نوع هذه السلسلة. قراءة [ChartType](../charttype/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticSeriesColor](./getautomaticseriescolor/)() | يُعيد لونًا تلقائيًا للسلسلة بناءً على فهرس السلسلة ونمط المخطط. يُستخدم هذا اللون افتراضيًا إذا كان FillType يساوي NotDefined. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مشابه لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مشابه لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. مشابه لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يطبق بيان القفل C# lock() لتقفل. استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | مُنشئ النسخ. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويمكّن من نسخ الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | مشغل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويمكّن من نسخ الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_Bar3DShape](./set_bar3dshape/)([ChartShapeType](../chartshapetype/)) | يحدد شكل مجموعة من مخطط شريطي ثلاثي الأبعاد. قد يتسبب تغيير قيمة هذه الخاصية في تغيير نوع السلسلة تلقائيًا. اكتب [ChartShapeType](../chartshapetype/). |
| virtual void [set_Explosion](./set_explosion/)(**int32_t**) | تُعبّر مسافة شريحة الفطيرة المفتوحة من مركز مخطط الفطيرة كنسبة مئوية من قطر الفطيرة. اكتب **int32_t**. |
| virtual void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) | يحدد ما إذا كانت السلسلة الشريطية أو العمودية أو الفقاعية تعكس ألوانها إذا كانت القيمة سالبة. اكتب **bool**. |
| virtual void [set_NumberFormatOfBubbleSizes](./set_numberformatofbubblesizes/)([System::String](../../system/string/)) | يحدد تنسيق الرقم لأحجام فقاعات السلسلة. اكتب [System::String](../../system/string/). |
| virtual void [set_NumberFormatOfValues](./set_numberformatofvalues/)([System::String](../../system/string/)) | يحدد تنسيق الرقم لقيم السلسلة. اكتب [System::String](../../system/string/). |
| virtual void [set_NumberFormatOfXValues](./set_numberformatofxvalues/)([System::String](../../system/string/)) | يحدد تنسيق الرقم لقيم السلسلة السينية. اكتب [System::String](../../system/string/). |
| virtual void [set_NumberFormatOfYValues](./set_numberformatofyvalues/)([System::String](../../system/string/)) | يحدد تنسيق الرقم لقيم السلسلة الصادية. اكتب [System::String](../../system/string/). |
| virtual void [set_Order](./set_order/)(**int32_t**) | يُعيد ترتيب السلسلة. اكتب **int32_t**. |
| virtual void [set_ParentLabelLayout](./set_parentlabellayout/)([ParentLabelLayoutType](../parentlabellayouttype/)) | يمثل تخطيط تسميات الفئات الأصلية. يُطبق فقط على مخططات الشجرة. |
| virtual void [set_PlotOnSecondAxis](./set_plotonsecondaxis/)(**bool**) | يوضح ما إذا كانت هذه السلسلة مرسومة على محور القيم الثاني. اكتب **bool**. |
| virtual void [set_QuartileMethod](./set_quartilemethod/)([QuartileMethodType](../quartilemethodtype/)) | يمثل طريقة الربع. يُطبق فقط على مخططات الصندوق والوشاح. |
| virtual void [set_ShowConnectorLines](./set_showconnectorlines/)(**bool**) | يمثل خطوط الموصل. يُطبق فقط على مخططات الشلال. |
| virtual void [set_ShowInnerPoints](./set_showinnerpoints/)(**bool**) | يمثل النقاط الداخلية. صحيح إذا كانت النقاط الداخلية معروضة على مخطط الصندوق والوشاح. يُطبق فقط على مخططات الصندوق والوشاح. اكتب **bool**. |
| virtual void [set_ShowMeanLine](./set_showmeanline/)(**bool**) | يمثل علامات المتوسط. صحيح إذا كانت خط المتوسط معروض على مخطط الصندوق والوشاح. يُطبق فقط على مخططات الصندوق والوشاح. اكتب **bool**. |
| virtual void [set_ShowMeanMarkers](./set_showmeanmarkers/)(**bool**) | يمثل علامات المتوسط. صحيح إذا كانت علامات المتوسط معروضة على مخطط الصندوق والوشاح. يُطبق فقط على مخططات الصندوق والوشاح. اكتب **bool**. |
| virtual void [set_ShowOutlierPoints](./set_showoutlierpoints/)(**bool**) | يمثل نقاط الشذوذ. صحيح إذا كانت نقاط الشذوذ معروضة على مخطط الصندوق والوشاح. يُطبق فقط على مخططات الصندوق والوشاح. اكتب **bool**. |
| virtual void [set_Smooth](./set_smooth/)(**bool**) | يمثل تنعيم المنحنى. صحيح إذا كان تنعيم المنحنى مفعلاً لمخطط الخط أو المخطط المتناثر. يُطبق فقط على مخططات الخط والمتناثر المتصلة بالخطوط. اكتب **bool**. |
| virtual void [set_Type](./set_type/)([ChartType](../charttype/)) | يُعيد نوع هذه السلسلة. اكتب [ChartType](../charttype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | عيّن الوسيطة القالبية الـ n إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويُعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى نص. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ بيان القفل C# lock() لإلغاء القفل. استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |
## انظر أيضًا

* Class [IChartComponent](../ichartcomponent/)
* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)