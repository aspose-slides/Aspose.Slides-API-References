---
title: IAxis
second_title: Aspose.Slides C++ API 参考
description: 封装表示图表轴的对象。
type: docs
weight: 534
url: /zh/aspose.slides.charts/iaxis/
---
## IAxis 类

封装表示图表轴的对象。

```cpp
class IAxis : public Aspose::Slides::Charts::IFormattedTextContainer
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，两个 NaN 被视为相等，即使根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，两个 NaN 被视为相等，即使根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅用于内部目的。 |
| virtual **double** [get_ActualMajorUnit](./get_actualmajorunit/)() | 指定轴的实际主要单位。请先调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 获取实际值。 |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() | 指定轴的实际主要单位比例。请先调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 获取实际值。 |
| virtual **double** [get_ActualMaxValue](./get_actualmaxvalue/)() | 指定轴上的实际最大值。请先调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 获取实际值。 |
| virtual **double** [get_ActualMinorUnit](./get_actualminorunit/)() | 指定轴的实际次要单位。请先调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 获取实际值。 |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() | 指定轴的实际次要单位比例。请先调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 获取实际值。 |
| virtual **double** [get_ActualMinValue](./get_actualminvalue/)() | 指定值轴的实际最小值。请先调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 获取实际值。 |
| virtual [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() | 表示类别轴的聚合类型（分箱）。适用于类别轴。仅在 Histogram 或 HistogramPareto 系列中使用。 |
| virtual **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() | 表示值轴是否在类别之间跨越类别轴。此属性仅适用于类别轴，不适用于 3-D 图表。读取 **bool**。 |
| virtual [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() | 指定日期轴上表示的最小时间单位。读取 [TimeUnitType](../timeunittype/)。 |
| virtual **double** [get_BinWidth](./get_binwidth/)() | 当 AggregationType 属性设置为 [AxisAggregationType::ByBinWidth](../axisaggregationtype/) 时指定分箱宽度。适用于类别轴。仅在 Histogram 或 HistogramPareto 系列中使用。 |
| virtual [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() | 指定类别轴的类型。读取 [CategoryAxisType](../categoryaxistype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | 返回图表。只读 [IChart](../ichart/)。 |
| virtual **float** [get_CrossAt](./get_crossat/)() | 表示轴上垂直轴相交的点。读取 **float**。 |
| virtual [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() | 表示在指定轴上另一轴交叉时的 CrossType。读取 [CrossesType](../crossestype/)。 |
| virtual [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() | 指定值轴显示单位的缩放值。读取 [DisplayUnitType](../displayunittype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() | 表示轴的格式。只读 [IAxisFormat](../iaxisformat/)。 |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | 确定轴是否具有可见标题。读取 **bool**。 |
| virtual **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() | 指示轴的主要单位是否自动分配。读取 **bool**。 |
| virtual **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() | 指示最大值是否自动分配。读取 **bool**。 |
| virtual **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() | 指示轴的次要单位是否自动分配。读取 **bool**。 |
| virtual **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() | 指示最小值是否自动分配。读取 **bool**。 |
| virtual **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() | 指定自动溢出分箱值。如果为 false：使用 OverflowBin 属性。 |
| virtual **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() | 指定自动刻度标签间距值。如果为 false：使用 TickLabelSpacing 属性。读取 **bool**。 |
| virtual **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() | 指定自动刻度标记间距值。如果为 false：使用 TickMarksSpacing 属性。读取 **bool**。 |
| virtual **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() | 指定自动下溢分箱值。如果为 false：使用 UnderflowBin 属性。 |
| virtual **bool** [get_IsLogarithmic](./get_islogarithmic/)() | 表示值轴的比例类型是否为对数。读取 **bool**。 |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | 指示格式是否链接到源数据。读取 **bool**。 |
| virtual **bool** [get_IsOverflowBin](./get_isoverflowbin/)() | 指定是否应用溢出分箱。使用 IsAutomaticOverflowBin 和 OverflowBin 来调整溢出分箱值。 |
| virtual **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() | 表示 MS PowerPoint 是否从最后到第一个绘制数据点。读取 **bool**。 |
| virtual **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() | 指定是否应用下溢分箱。使用 IsAutomaticUnderflowBin 和 UnderflowBin 来调整下溢分箱值。 |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | 表示轴是否可见。读取 **bool**。 |
| virtual **uint16_t** [get_LabelOffset](./get_labeloffset/)() | 指定标签距轴的距离。适用于类别或日期轴。值必须在 0% 到 1000% 之间。读取 **uint16_t**。 |
| virtual **double** [get_LogBase](./get_logbase/)() | 表示对数基数。默认值为 10。读取 **double**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() | 表示图表轴上主要网格线的格式。只读 [IChartLinesFormat](../ichartlinesformat/)。 |
| virtual [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() | 表示指定轴的主要刻度标记类型。读取 [TickMarkType](../tickmarktype/)。 |
| virtual **double** [get_MajorUnit](./get_majorunit/)() | 表示日期或值轴的主要单位。读取 **double**。 |
| virtual [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() | 表示日期轴的主要单位比例。读取 [TimeUnitType](../timeunittype/)。 |
| virtual **double** [get_MaxValue](./get_maxvalue/)() | 表示值轴的最大值。读取 **double**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() | 表示图表轴上次要网格线的格式。只读 [IChartLinesFormat](../ichartlinesformat/)。 |
| virtual [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() | 表示指定轴的次要刻度标记类型。读取 [TickMarkType](../tickmarktype/)。 |
| virtual **double** [get_MinorUnit](./get_minorunit/)() | 表示日期或值轴的次要单位。读取 **double**。 |
| virtual [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() | 表示日期轴的主要单位比例。读取 [TimeUnitType](../timeunittype/)。 |
| virtual **double** [get_MinValue](./get_minvalue/)() | 表示值轴的最小值。读取 **double**。 |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | 表示 [Axis](../axis/) 标签的格式字符串。读取 [System::String](../../system/string/)。 |
| virtual **uint32_t** [get_NumberOfBins](./get_numberofbins/)() | 当 AggregationType 属性设置为 [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) 时指定分箱数量。适用于类别轴。仅在 Histogram 或 HistogramPareto 系列中使用。 |
| virtual **double** [get_OverflowBin](./get_overflowbin/)() | 指定溢出分箱的自定义值。当 IsAutomaticOverflowBin 属性设置为 false 且 IsOverflowBin 属性为 true 时使用。 |
| virtual [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() | 表示轴的位置。读取 [AxisPositionType](../axispositiontype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 返回演示文稿。只读 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() | 表示是否显示主要网格线。只读 **bool**。 |
| virtual **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() | 表示是否显示次要网格线。只读 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 返回基础幻灯片。只读 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | 返回图表文本格式。只读 [IChartTextFormat](../icharttextformat/)。 |
| virtual [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() | 表示在指定轴上刻度标签的位置。读取 [TickLabelPositionType](../ticklabelpositiontype/)。 |
| virtual **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() | 表示刻度标签的旋转角度。读取 **float**。 |
| virtual **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() | 指定在已绘制的标签之间要跳过多少个刻度标签。读取 **uint32_t**。 |
| virtual **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() | 指定在绘制下一个刻度标记前应跳过多少个刻度标记。适用于类别或系列轴。读取 **uint16_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() | 获取轴的标题。只读 [IChartTitle](../icharttitle/)。 |
| virtual **double** [get_UnderflowBin](./get_underflowbin/)() | 指定下溢分箱的自定义值。当 IsAutomaticUnderflowBin 属性设置为 false 且 IsUnderflowBin 属性为 true 时使用。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 守卫对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用克隆自定义类型。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，仅初始化新对象并允许子类的复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类的复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 情形。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串情形。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) | 表示类别轴的聚合类型（分箱）。适用于类别轴。仅在 Histogram 或 HistogramPareto 系列中使用。 |
| virtual void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) | 表示值轴是否在类别之间跨越类别轴。此属性仅适用于类别轴，不适用于 3-D 图表。写入 **bool**。 |
| virtual void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) | 指定日期轴上表示的最小时间单位。写入 [TimeUnitType](../timeunittype/)。 |
| virtual void [set_BinWidth](./set_binwidth/)(**double**) | 当 AggregationType 属性设置为 [AxisAggregationType::ByBinWidth](../axisaggregationtype/) 时指定分箱宽度。适用于类别轴。仅在 Histogram 或 HistogramPareto 系列中使用。 |
| virtual void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) | 指定类别轴的类型。写入 [CategoryAxisType](../categoryaxistype/)。 |
| virtual void [set_CrossAt](./set_crossat/)(**float**) | 表示轴上垂直轴相交的点。写入 **float**。 |
| virtual void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) | 表示在指定轴上另一轴交叉时的 CrossType。写入 [CrossesType](../crossestype/)。 |
| virtual void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) | 指定值轴显示单位的缩放值。写入 [DisplayUnitType](../displayunittype/)。 |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | 确定轴是否具有可见标题。写入 **bool**。 |
| virtual void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) | 指示轴的主要单位是否自动分配。写入 **bool**。 |
| virtual void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) | 指示最大值是否自动分配。写入 **bool**。 |
| virtual void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) | 指示轴的次要单位是否自动分配。写入 **bool**。 |
| virtual void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) | 指示最小值是否自动分配。写入 **bool**。 |
| virtual void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) | 指定自动溢出分箱值。如果为 false：使用 OverflowBin 属性。 |
| virtual void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) | 指定自动刻度标签间距值。如果为 false：使用 TickLabelSpacing 属性。写入 **bool**。 |
| virtual void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) | 指定自动刻度标记间距值。如果为 false：使用 TickMarksSpacing 属性。写入 **bool**。 |
| virtual void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) | 指定自动下溢分箱值。如果为 false：使用 UnderflowBin 属性。 |
| virtual void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) | 表示值轴的比例类型是否为对数。写入 **bool**。 |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | 指示格式是否链接到源数据。写入 **bool**。 |
| virtual void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) | 指定是否应用溢出分箱。使用 IsAutomaticOverflowBin 和 OverflowBin 来调整溢出分箱值。 |
| virtual void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) | 表示 MS PowerPoint 是否从最后到第一个绘制数据点。写入 **bool**。 |
| virtual void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) | 指定是否应用下溢分箱。使用 IsAutomaticUnderflowBin 和 UnderflowBin 来调整下溢分箱值。 |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | 表示轴是否可见。写入 **bool**。 |
| virtual void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) | 指定标签距轴的距离。适用于类别或日期轴。值必须在 0% 到 1000% 之间。写入 **uint16_t**。 |
| virtual void [set_LogBase](./set_logbase/)(**double**) | 表示对数基数。默认值为 10。写入 **double**。 |
| virtual void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) | 表示指定轴的主要刻度标记类型。写入 [TickMarkType](../tickmarktype/)。 |
| virtual void [set_MajorUnit](./set_majorunit/)(**double**) | 表示日期或值轴的主要单位。写入 **double**。 |
| virtual void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) | 表示日期轴的主要单位比例。写入 [TimeUnitType](../timeunittype/)。 |
| virtual void [set_MaxValue](./set_maxvalue/)(**double**) | 表示值轴的最大值。写入 **double**。 |
| virtual void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) | 表示指定轴的次要刻度标记类型。写入 [TickMarkType](../tickmarktype/)。 |
| virtual void [set_MinorUnit](./set_minorunit/)(**double**) | 表示日期或值轴的次要单位。写入 **double**。 |
| virtual void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) | 表示日期轴的主要单位比例。写入 [TimeUnitType](../timeunittype/)。 |
| virtual void [set_MinValue](./set_minvalue/)(**double**) | 表示值轴的最小值。写入 **double**。 |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | 表示 [Axis](../axis/) 标签的格式字符串。写入 [System::String](../../system/string/)。 |
| virtual void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) | 当 AggregationType 属性设置为 [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) 时指定分箱数量。适用于类别轴。仅在 Histogram 或 HistogramPareto 系列中使用。 |
| virtual void [set_OverflowBin](./set_overflowbin/)(**double**) | 指定溢出分箱的自定义值。当 IsAutomaticOverflowBin 属性设置为 false 且 IsOverflowBin 属性为 true 时使用。 |
| virtual void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) | 表示轴的位置。写入 [AxisPositionType](../axispositiontype/)。 |
| virtual void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) | 表示在指定轴上刻度标签的位置。写入 [TickLabelPositionType](../ticklabelpositiontype/)。 |
| virtual void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) | 表示刻度标签的旋转角度。写入 **float**。 |
| virtual void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) | 指定在已绘制的标签之间要跳过多少个刻度标签。写入 **uint32_t**。 |
| virtual void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) | 指定在绘制下一个刻度标记前应跳过多少个刻度标记。适用于类别或系列轴。写入 **uint16_t**。 |
| virtual void [set_UnderflowBin](./set_underflowbin/)(**double**) | 指定下溢分箱的自定义值。当 IsAutomaticUnderflowBin 属性设置为 false 且 IsUnderflowBin 属性为 true 时使用。 |
| virtual void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() | 使用基于轴数据自动确定的值设置 IAxis::get(set)_CategoryAxisType 属性。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 守卫对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参见

* 类 [IFormattedTextContainer](../iformattedtextcontainer/)
* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)