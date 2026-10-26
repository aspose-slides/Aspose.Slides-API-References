---
title: IChartSeries
second_title: Aspose.Slides for C++ API 参考
description: 表示一个图表系列。
type: docs
weight: 820
url: /zh/aspose.slides.charts/ichartseries/
---
## IChartSeries 类

表示一个图表系列。

```cpp
class IChartSeries : public Aspose::Slides::Charts::IChartComponent
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [ChartShapeType](../chartshapetype/) [get_Bar3DShape](./get_bar3dshape/)() | 指定 3-D 条形图系列的形状。更改此属性的值可能会自动更改系列的类型。阅读 [ChartShapeType](../chartshapetype/)。 |
| virtual [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() | 指定气泡图中气泡大小值的表示方式。此属性不仅适用于此系列，还适用于父系列组的所有系列——这是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_BubbleSizeRepresentation() 读/写属性来更改值。 |
| virtual **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() | 指定气泡图的比例因子（可以在默认大小的 0% 到 300% 之间）。此属性不仅适用于此系列，还适用于父系列组的所有系列——这是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_BubbleSizeScale() 读/写属性来更改值。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | 返回图表。只读 [IChart](../ichart/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_DataPoint](./get_datapoint/)(**int32_t**) | 返回此系列在指定索引处的数据点。 |
| virtual **int32_t** [get_DataPoint](./get_datapoint/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointCollection](../ichartdatapointcollection/)\> [get_DataPoints](./get_datapoints/)() | 返回此系列的数据点集合。只读 [IChartDataPointCollection](../ichartdatapointcollection/)。 |
| virtual **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() | 指定环形图中孔的大小（可以在绘图区大小的 10% 到 90% 之间）。此属性不仅适用于此系列，还适用于父系列组的所有系列——这是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_DoughnutHoleSize() 读/写属性来更改值。只读 **uint8_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsFormat](../ierrorbarsformat/)\> [get_ErrorBarsXFormat](./get_errorbarsxformat/)() | 表示 X 方向的系列 ErrorBars。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsFormat](../ierrorbarsformat/)\> [get_ErrorBarsYFormat](./get_errorbarsyformat/)() | 表示 Y 方向的系列 ErrorBars。 |
| virtual **int32_t** [get_Explosion](./get_explosion/)() | 环形图中打开的饼块到中心的距离以饼直径的百分比表示。读取 **int32_t**。 |
| virtual **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() | 指定首个饼或环形图切片的角度，单位为度（顺时针，从上方 0 到 360 度）。此属性不仅适用于此系列，还适用于父系列组的所有系列——这是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_FirstSliceAngle() 读/写属性来更改值。只读 **uint16_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | 返回系列的格式。只读 [IFormat](../iformat/)。 |
| virtual **int32_t** [get_GapDepth](./get_gapdepth/)() | 返回 3D 图表中数据系列之间的距离，以标记宽度的百分比表示。此属性不仅适用于此系列，还适用于父系列组的所有系列——这是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_GapDepth() 读/写属性来更改值。只读 **int32_t**。 |
| virtual **int32_t** [get_GapWidth](./get_gapwidth/)() | 指定条形或列簇之间的间距，以条形或列宽的百分比表示。此属性不仅适用于此系列，还适用于父系列组的所有系列——这是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_GapWidth() 读/写属性来更改值。只读 **int32_t**。 |
| virtual **bool** [get_HasSeriesLines](./get_hasserieslines/)() | 确定此系列及其关联系列是否具有系列线。此属性不仅适用于此系列，还适用于父系列组的所有系列——这是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_HasSeriesLines() 读/写属性来更改值。使用 ParentSeriesGroup.SeriesLinesFormat 属性设置系列线的格式。只读 **bool**。 |
| virtual **bool** [get_HasUpDownBars](./get_hasupdownbars/)() | 确定折线图或股票图是否具有上下条。此属性不仅适用于此系列，还适用于父系列组的所有系列——这是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get_UpDownBars()->get(set)_HasUpDownBars() 读/写属性来更改值。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get_UpDownBars() 属性设置上下条的格式。只读 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_InvertedSolidFillColor](./get_invertedsolidfillcolor/)() | 指定系列的反转实心颜色。要应用颜色设置，请将系列格式 FillType 设置为 [FillType::Solid](../../aspose.slides/filltype/)。阅读 [IColorFormat](../../aspose.slides/icolorformat/)。 |
| virtual **bool** [get_InvertIfNegative](./get_invertifnegative/)() | 指定当值为负数时，条形、列或气泡系列应反转其颜色。读取 **bool**。 |
| virtual **bool** [get_IsColorVaried](./get_iscolorvaried/)() | 指定系列中的每个数据标记使用不同的颜色。此属性不仅适用于此系列，还适用于父系列组的所有系列——这是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_IsColorVaried() 读/写属性来更改值。只读 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)(**int32_t**) | 返回此系列在指定索引处的数据标签。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelCollection](../idatalabelcollection/)\> [get_Labels](./get_labels/)() | 返回系列的 Labels。只读 [IDataLabelCollection](../idatalabelcollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() | 返回系列标记。只读 [IMarker](../imarker/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IStringChartValue](../istringchartvalue/)\> [get_Name](./get_name/)() | 返回系列名称。只读 [IStringChartValue](../istringchartvalue/)。 |
| virtual [System::String](../../system/string/) [get_NumberFormatOfBubbleSizes](./get_numberformatofbubblesizes/)() | 返回系列气泡大小的数字格式。阅读 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_NumberFormatOfValues](./get_numberformatofvalues/)() | 返回系列值的数字格式。阅读 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_NumberFormatOfXValues](./get_numberformatofxvalues/)() | 返回系列 X 值的数字格式。阅读 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_NumberFormatOfYValues](./get_numberformatofyvalues/)() | 返回系列 Y 值的数字格式。阅读 [System::String](../../system/string/)。 |
| virtual **int32_t** [get_Order](./get_order/)() | 返回系列的顺序。读取 **int32_t**。 |
| virtual **int8_t** [get_Overlap](./get_overlap/)() | 指定在 2-D 图表上条形和列的重叠程度，单位为百分比（-100% 到 100%）。此属性不仅适用于此系列，还适用于父系列组的所有系列——这是相应组属性的投影。因此此属性为只读。要更改值，请使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_Overlap() 读/写属性。只读 **int8_t**。 |
| virtual [ParentLabelLayoutType](../parentlabellayouttype/) [get_ParentLabelLayout](./get_parentlabellayout/)() | 表示父分类标签的布局。仅适用于 Treemap 图表。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](./)\> [get_ParentSeries](./get_parentseries/)(**int32_t**) | 返回父系列组中指定索引处的图表系列。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_ParentSeriesGroup](./get_parentseriesgroup/)() | 返回父系列组。只读 [IChartSeriesGroup](../ichartseriesgroup/)。 |
| virtual [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() | 指定如何确定在 pie-of-pie 或 bar-of-pie 图表中哪些数据点位于第二个饼或条中。此属性不仅适用于此系列，还适用于父系列组的所有系列——这是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_PieSplitBy() 读/写属性来更改值。只读 [PieSplitType](../piesplittype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) | 对于自定义拆分的 pie-of-pie 或 bar-of-pie 图表，返回应在第二个饼或条中绘制的数据点的自定义拆分信息。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() | 对于自定义拆分的 pie-of-pie 或 bar-of-pie 图表，包含应在第二个饼或条中绘制的数据点的自定义拆分信息。此属性不仅适用于此系列，还适用于父系列组的所有系列——这是相应组属性的投影。只读 [IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)。 |
| virtual **double** [get_PieSplitPosition](./get_piesplitposition/)() | 指定用于确定在 pie-of-pie 或 bar-of-pie 图表中哪些数据点位于第二个饼或条的值。与 PieSplitBy 属性一起使用。此属性不仅适用于此系列，还适用于父系列组的所有系列——这是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_PieSplitPosition() 读/写属性来更改值。只读 **double**。 |
| virtual **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() | 指示此系列是否绘制在第二值轴上。读取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 返回演示文稿。只读 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual [QuartileMethodType](../quartilemethodtype/) [get_QuartileMethod](./get_quartilemethod/)() | 表示四分位方法。仅适用于 BoxAndWhisker 图表。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | 表示与此系列相关的图例项。只读 [ILegendEntryProperties](../ilegendentryproperties/)。 |
| virtual **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() | 指定 pie-of-pie 或 bar-of-pie 图表中第二个饼或条的大小，作为第一个饼大小的百分比（可以在 5% 到 200% 之间）。此属性不仅适用于此系列，还适用于父系列组的所有系列——这是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_SecondPieSize() 读/写属性来更改值。只读 **uint16_t**。 |
| virtual **bool** [get_ShowConnectorLines](./get_showconnectorlines/)() | 表示连接线。仅适用于 Waterfall 图表。 |
| virtual **bool** [get_ShowInnerPoints](./get_showinnerpoints/)() | 表示内部点。若在 BoxAndWhisker 图表上显示内部点则为 true。仅适用于 BoxAndWhisker 图表。读取 **bool**。 |
| virtual **bool** [get_ShowMeanLine](./get_showmeanline/)() | 表示均值标记。若在 BoxAndWhisker 图表上显示均值线则为 true。仅适用于 BoxAndWhisker 图表。读取 **bool**。 |
| virtual **bool** [get_ShowMeanMarkers](./get_showmeanmarkers/)() | 表示均值标记。若在 BoxAndWhisker 图表上显示均值标记则为 true。仅适用于 BoxAndWhisker 图表。读取 **bool**。 |
| virtual **bool** [get_ShowOutlierPoints](./get_showoutlierpoints/)() | 表示异常值点。若在 BoxAndWhisker 图表上显示异常值点则为 true。仅适用于 BoxAndWhisker 图表。读取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 返回基础幻灯片。只读 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual **bool** [get_Smooth](./get_smooth/)() | 表示曲线平滑。若对折线图或散点图启用曲线平滑则为 true。仅适用于折线图和带线的散点图。读取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITrendline](../itrendline/)\> [get_TrendLine](./get_trendline/)(**int32_t**) | 返回指定索引处的趋势线。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITrendlineCollection](../itrendlinecollection/)\> [get_TrendLines](./get_trendlines/)() | 系列趋势线集合。只读 [ITrendlineCollection](../itrendlinecollection/)。 |
| virtual [ChartType](../charttype/) [get_Type](./get_type/)() | 返回此系列的类型。阅读 [ChartType](../charttype/)。 |
| virtual [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticSeriesColor](./getautomaticseriescolor/)() | 返回基于系列索引和图表样式的系列自动颜色。如果 FillType 等于 NotDefined，则默认使用此颜色。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的等价实现。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是目标类型的实例。相当于 C# `is` 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的等价实现。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不拷贝任何内容，仅初始化新对象并允许子类拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不拷贝任何内容，仅初始化新对象并允许子类拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_Bar3DShape](./set_bar3dshape/)([ChartShapeType](../chartshapetype/)) | 指定 3-D 条形图系列的形状。更改此属性的值可能会自动更改系列的类型。写入 [ChartShapeType](../chartshapetype/)。 |
| virtual void [set_Explosion](./set_explosion/)(**int32_t**) | 环形图中打开的饼块到中心的距离以饼直径的百分比表示。写入 **int32_t**。 |
| virtual void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) | 指定当值为负数时，条形、列或气泡系列应反转其颜色。写入 **bool**。 |
| virtual void [set_NumberFormatOfBubbleSizes](./set_numberformatofbubblesizes/)([System::String](../../system/string/)) | 设置系列气泡大小的数字格式。写入 [System::String](../../system/string/)。 |
| virtual void [set_NumberFormatOfValues](./set_numberformatofvalues/)([System::String](../../system/string/)) | 设置系列值的数字格式。写入 [System::String](../../system/string/)。 |
| virtual void [set_NumberFormatOfXValues](./set_numberformatofxvalues/)([System::String](../../system/string/)) | 设置系列 X 值的数字格式。写入 [System::String](../../system/string/)。 |
| virtual void [set_NumberFormatOfYValues](./set_numberformatofyvalues/)([System::String](../../system/string/)) | 设置系列 Y 值的数字格式。写入 [System::String](../../system/string/)。 |
| virtual void [set_Order](./set_order/)(**int32_t**) | 返回系列的顺序。写入 **int32_t**。 |
| virtual void [set_ParentLabelLayout](./set_parentlabellayout/)([ParentLabelLayoutType](../parentlabellayouttype/)) | 表示父分类标签的布局。仅适用于 Treemap 图表。 |
| virtual void [set_PlotOnSecondAxis](./set_plotonsecondaxis/)(**bool**) | 指示此系列是否绘制在第二值轴上。写入 **bool**。 |
| virtual void [set_QuartileMethod](./set_quartilemethod/)([QuartileMethodType](../quartilemethodtype/)) | 表示四分位方法。仅适用于 BoxAndWhisker 图表。 |
| virtual void [set_ShowConnectorLines](./set_showconnectorlines/)(**bool**) | 表示连接线。仅适用于 Waterfall 图表。 |
| virtual void [set_ShowInnerPoints](./set_showinnerpoints/)(**bool**) | 表示内部点。若在 BoxAndWhisker 图表上显示内部点则为 true。仅适用于 BoxAndWhisker 图表。写入 **bool**。 |
| virtual void [set_ShowMeanLine](./set_showmeanline/)(**bool**) | 表示均值标记。若在 BoxAndWhisker 图表上显示均值线则为 true。仅适用于 BoxAndWhisker 图表。写入 **bool**。 |
| virtual void [set_ShowMeanMarkers](./set_showmeanmarkers/)(**bool**) | 表示均值标记。若在 BoxAndWhisker 图表上显示均值标记则为 true。仅适用于 BoxAndWhisker 图表。写入 **bool**。 |
| virtual void [set_ShowOutlierPoints](./set_showoutlierpoints/)(**bool**) | 表示异常值点。若在 BoxAndWhisker 图表上显示异常值点则为 true。仅适用于 BoxAndWhisker 图表。写入 **bool**。 |
| virtual void [set_Smooth](./set_smooth/)(**bool**) | 表示曲线平滑。若对折线图或散点图启用曲线平滑则为 true。仅适用于折线图和带线的散点图。写入 **bool**。 |
| virtual void [set_Type](./set_type/)([ChartType](../charttype/)) | 返回此系列的类型。写入 [ChartType](../charttype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取当前的共享引用计数值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 减少并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的等价实现。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 减少弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [IChartComponent](../ichartcomponent/)
* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)