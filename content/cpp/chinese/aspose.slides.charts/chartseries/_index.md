---
title: ChartSeries
second_title: Aspose.Slides C++ API 参考
description: 表示图表系列。
type: docs
weight: 274
url: /zh/aspose.slides.charts/chartseries/
---
## ChartSeries 类

表示图表系列。

```cpp
class ChartSeries : public Aspose::Slides::Charts::IChartSeries,
                    public Aspose::Slides::IDOMObject
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等，也将两个 NaN 视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等，也将两个 NaN 视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅用于内部目的。 |
| [ChartShapeType](../chartshapetype/) [get_Bar3DShape](./get_bar3dshape/)() override | 指定 3-D 条形图系列的形状。更改此属性的值可能导致自动更改系列的 Type。读取 [ChartShapeType](../chartshapetype/)。 |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | 指定在气泡图上气泡尺寸值的表示方式。此属性不仅属于本系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_BubbleSizeRepresentation() 读/写属性来更改值。 |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | 指定气泡图的比例因子（可在默认大小的 0% 到 300% 之间）。此属性不仅属于本系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_BubbleSizeScale() 读/写属性来更改值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 返回父图表。只读 [IChart](../ichart/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_DataPoint](./get_datapoint/)(**int32_t**) override | 返回此系列在指定索引处的数据点。 |
| **int32_t** [get_DataPoint](./get_datapoint/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointCollection](../ichartdatapointcollection/)\> [get_DataPoints](./get_datapoints/)() override | 返回此系列的数据点集合。只读 [IChartDataPointCollection](../ichartdatapointcollection/)。 |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | 指定环形图中孔的大小（可在绘图区域大小的 10% 到 90% 之间）。此属性不仅属于本系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_DoughnutHoleSize() 读/写属性来更改值。只读 **uint8_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsFormat](../ierrorbarsformat/)\> [get_ErrorBarsXFormat](./get_errorbarsxformat/)() override | 表示方向 X 的系列误差线。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsFormat](../ierrorbarsformat/)\> [get_ErrorBarsYFormat](./get_errorbarsyformat/)() override | 表示方向 Y 的系列误差线。 |
| **int32_t** [get_Explosion](./get_explosion/)() override | 打开的饼图切片距离饼图中心的距离以饼直径的百分比表示。读取 **int32_t**。 |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | 指定第一块饼或环形图切片的角度（单位：度，顺时针从上方，0 到 360 度）。此属性不仅属于本系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_FirstSliceAngle() 读/写属性来更改值。只读 **uint16_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | 返回系列的格式。只读 [IFormat](../iformat/)。 |
| **int32_t** [get_GapDepth](./get_gapdepth/)() override | 返回 3D 图表中数据系列之间的距离，以标记宽度的百分比表示。此属性不仅属于本系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_GapDepth() 读/写属性来更改值。只读 **int32_t**。 |
| **int32_t** [get_GapWidth](./get_gapwidth/)() override | 指定条形或柱形簇之间的间距，以条形或柱形宽度的百分比表示。此属性不仅属于本系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_GapWidth() 读/写属性来更改值。只读 **int32_t**。 |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | 确定此系列及相关系列是否有系列线。此属性不仅属于本系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_HasSeriesLines() 读/写属性来更改值。使用 ParentSeriesGroup.SeriesLinesFormat 属性设置系列线的格式。只读 **bool**。 |
| **bool** [get_HasUpDownBars](./get_hasupdownbars/)() override | 确定折线图或股票图是否具有上下柱。此属性不仅属于本系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get_UpDownBars()->get(set)_HasUpDownBars() 读/写属性来更改值。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get_UpDownBars() 属性格式化上下柱。只读 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_InvertedSolidFillColor](./get_invertedsolidfillcolor/)() override | 指定系列的反转实色。要应用颜色设置，请将系列格式 FillType 设置为 [FillType::Solid](../../aspose.slides/filltype/)。读取 [ColorFormat](../../aspose.slides/colorformat/)。 |
| **bool** [get_InvertIfNegative](./get_invertifnegative/)() override | 指定如果值为负，则条形、柱形或气泡系列应反转其颜色。读取 **bool**。 |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | 指定系列中的每个数据标记具有不同的颜色。此属性不仅属于本系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_IsColorVaried() 读/写属性来更改值。只读 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)(**int32_t**) override | 返回此系列在指定索引处的数据点的数据标签。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelCollection](../idatalabelcollection/)\> [get_Labels](./get_labels/)() override | 返回系列的标签。只读 [IDataLabelCollection](../idatalabelcollection/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() override | [Marker](../marker/)。只读 [IMarker](../imarker/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IStringChartValue](../istringchartvalue/)\> [get_Name](./get_name/)() override | 返回系列名称。只读 [IStringChartValue](../istringchartvalue/)。 |
| [System::String](../../system/string/) [get_NumberFormatOfBubbleSizes](./get_numberformatofbubblesizes/)() override | NumberFormatOfBubbleSizes。读取 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_NumberFormatOfValues](./get_numberformatofvalues/)() override | NumberFormatOfValues。读取 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_NumberFormatOfXValues](./get_numberformatofxvalues/)() override | NumberFormatOfXValues。读取 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_NumberFormatOfYValues](./get_numberformatofyvalues/)() override | NumberFormatOfYValues。读取 [System::String](../../system/string/)。 |
| **int32_t** [get_Order](./get_order/)() override | 返回系列的顺序。读取 **int32_t**。 |
| **int8_t** [get_Overlap](./get_overlap/)() override | 指定条形和柱形在二维图表上的重叠程度，以百分比表示（-100% 到 100%）。此属性不仅属于本系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。若要更改值，请使用 [get_ParentSeriesGroup()->Overlap()](./get_parentseriesgroup/) 读/写属性。只读 **int8_t**。 |
| [ParentLabelLayoutType](../parentlabellayouttype/) [get_ParentLabelLayout](./get_parentlabellayout/)() override | 表示父类别标签的布局。仅适用于 Treemap 图表。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ParentSeries](./get_parentseries/)(**int32_t**) override | 返回父系列组中指定索引处的图表系列。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_ParentSeriesGroup](./get_parentseriesgroup/)() override | ParentSeriesGroup。只读 [IChartSeriesGroup](../ichartseriesgroup/)。 |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | 指定如何确定在饼中饼或柱中饼图的第二块饼或柱中包含哪些数据点。此属性不仅属于本系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_PieSplitBy() 读/写属性来更改值。只读 [PieSplitType](../piesplittype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | 对具有自定义拆分的饼中饼或柱中饼图的自定义拆分信息。返回应在第二块饼或柱中绘制的数据点，索引由指定。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | 对具有自定义拆分的饼中饼或柱中饼图的自定义拆分信息。包含应在第二块饼或柱中绘制的数据点。此属性不仅属于本系列，还属于父系列组的所有系列——它是相应组属性的投影。只读 [PieSplitCustomPointCollection](../piesplitcustompointcollection/)。 |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | 指定用于确定饼中饼或柱中饼图第二块饼或柱中包含哪些数据点的值。与 PieSplitBy 属性一起使用。此属性不仅属于本系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_PieSplitPosition() 读/写属性来更改值。只读 **double**。 |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | 指示此系列是否绘制在次坐标轴上。读取 **bool**。 |
| [QuartileMethodType](../quartilemethodtype/) [get_QuartileMethod](./get_quartilemethod/)() override | 表示四分位方法。仅适用于 BoxAndWhisker 图表。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | 表示与此系列相关的图例项。只读 [ILegendEntryProperties](../ilegendentryproperties/)。 |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | 指定饼中饼图或柱中饼图的第二块饼或柱的大小，以第一块饼大小的百分比表示（可在 5% 到 200% 之间）。此属性不仅属于本系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_SecondPieSize() 读/写属性来更改值。只读 **uint16_t**。 |
| **bool** [get_ShowConnectorLines](./get_showconnectorlines/)() override | 表示连接线。仅适用于 Waterfall 图表。 |
| **bool** [get_ShowInnerPoints](./get_showinnerpoints/)() override | 表示内部点。如果在 BoxAndWhisker 图表上显示内部点则为 true。仅适用于 BoxAndWhisker 图表。读取 **bool**。 |
| **bool** [get_ShowMeanLine](./get_showmeanline/)() override | 表示均值线。如果在 BoxAndWhisker 图表上显示均值线则为 true。仅适用于 BoxAndWhisker 图表。读取 **bool**。 |
| **bool** [get_ShowMeanMarkers](./get_showmeanmarkers/)() override | 表示均值标记。如果在 BoxAndWhisker 图表上显示均值标记则为 true。仅适用于 BoxAndWhisker 图表。读取 **bool**。 |
| **bool** [get_ShowOutlierPoints](./get_showoutlierpoints/)() override | 表示异常点。如果在 BoxAndWhisker 图表上显示异常点则为 true。仅适用于 BoxAndWhisker 图表。读取 **bool**。 |
| **bool** [get_Smooth](./get_smooth/)() override | 表示曲线平滑。如果在折线图或散点图（线连接）上开启曲线平滑则为 true。仅适用于折线图和线连接的散点图。读取 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITrendline](../itrendline/)\> [get_TrendLine](./get_trendline/)(**int32_t**) override | 返回指定索引处的趋势线。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITrendlineCollection](../itrendlinecollection/)\> [get_TrendLines](./get_trendlines/)() override | 系列趋势线的集合。只读 [ITrendlineCollection](../itrendlinecollection/)。 |
| [ChartType](../charttype/) [get_Type](./get_type/)() override | 返回此系列的类型。读取 [ChartType](../charttype/)。 |
| [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticSeriesColor](./getautomaticseriescolor/)() override | 根据系列索引和图表样式返回系列的自动颜色。如果 FillType 等于 NotDefined，则默认使用此颜色。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上并不复制任何内容，只是初始化新对象并启用子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上并不复制任何内容，只是初始化新对象并启用子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 按引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| void [set_Bar3DShape](./set_bar3dshape/)([ChartShapeType](../chartshapetype/)) override | 指定 3-D 条形图系列的形状。更改此属性的值可能导致自动更改系列的 Type。写入 [ChartShapeType](../chartshapetype/)。 |
| void [set_Explosion](./set_explosion/)(**int32_t**) override | 打开的饼图切片距离饼图中心的距离以饼直径的百分比表示。写入 **int32_t**。 |
| void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) override | 指定如果值为负，则条形、柱形或气泡系列应反转其颜色。写入 **bool**。 |
| void [set_NumberFormatOfBubbleSizes](./set_numberformatofbubblesizes/)([System::String](../../system/string/)) override | NumberFormatOfBubbleSizes。写入 [System::String](../../system/string/)。 |
| void [set_NumberFormatOfValues](./set_numberformatofvalues/)([System::String](../../system/string/)) override | NumberFormatOfValues。写入 [System::String](../../system/string/)。 |
| void [set_NumberFormatOfXValues](./set_numberformatofxvalues/)([System::String](../../system/string/)) override | NumberFormatOfXValues。写入 [System::String](../../system/string/)。 |
| void [set_NumberFormatOfYValues](./set_numberformatofyvalues/)([System::String](../../system/string/)) override | NumberFormatOfYValues。写入 [System::String](../../system/string/)。 |
| void [set_Order](./set_order/)(**int32_t**) override | 返回系列的顺序。写入 **int32_t**。 |
| void [set_ParentLabelLayout](./set_parentlabellayout/)([ParentLabelLayoutType](../parentlabellayouttype/)) override | 表示父类别标签的布局。仅适用于 Treemap 图表。 |
| void [set_PlotOnSecondAxis](./set_plotonsecondaxis/)(**bool**) override | 指示此系列是否绘制在次坐标轴上。写入 **bool**。 |
| void [set_QuartileMethod](./set_quartilemethod/)([QuartileMethodType](../quartilemethodtype/)) override | 表示四分位方法。仅适用于 BoxAndWhisker 图表。 |
| void [set_ShowConnectorLines](./set_showconnectorlines/)(**bool**) override | 表示连接线。仅适用于 Waterfall 图表。 |
| void [set_ShowInnerPoints](./set_showinnerpoints/)(**bool**) override | 表示内部点。如果在 BoxAndWhisker 图表上显示内部点则为 true。仅适用于 BoxAndWhisker 图表。写入 **bool**。 |
| void [set_ShowMeanLine](./set_showmeanline/)(**bool**) override | 表示均值线。如果在 BoxAndWhisker 图表上显示均值线则为 true。仅适用于 BoxAndWhisker 图表。写入 **bool**。 |
| void [set_ShowMeanMarkers](./set_showmeanmarkers/)(**bool**) override | 表示均值标记。如果在 BoxAndWhisker 图表上显示均值标记则为 true。仅适用于 BoxAndWhisker 图表。写入 **bool**。 |
| void [set_ShowOutlierPoints](./set_showoutlierpoints/)(**bool**) override | 表示异常点。如果在 BoxAndWhisker 图表上显示异常点则为 true。仅适用于 BoxAndWhisker 图表。写入 **bool**。 |
| void [set_Smooth](./set_smooth/)(**bool**) override | 表示曲线平滑。如果在折线图或散点图（线连接）上开启曲线平滑则为 true。仅适用于折线图和线连接的散点图。写入 **bool**。 |
| void [set_Type](./set_type/)([ChartType](../charttype/)) override | 返回此系列的类型。写入 [ChartType](../charttype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [IChartSeries](../ichartseries/)
* 类 [IDOMObject](../../aspose.slides/idomobject/)
* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)