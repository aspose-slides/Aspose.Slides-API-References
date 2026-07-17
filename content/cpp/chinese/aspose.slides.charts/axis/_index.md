---
title: Axis
second_title: Aspose.Slides for C++ API 参考
description: 封装表示图表坐标轴的对象。
type: docs
weight: 14
url: /zh/aspose.slides.charts/axis/
---
## Axis 类

Encapsulates the object that represents a chart's axis.

```cpp
class Axis : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::AxesManager>>,
             public Aspose::Slides::Charts::IAxis
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 在 C# 风格中比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 在 C# 风格中比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 与任何值都不相等，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 与任何值都不相等，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| **double** [get_ActualMajorUnit](./get_actualmajorunit/)() override | 指定轴的实际主单位。请先调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以获取实际值。 |
| [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() override | 指定轴的实际主单位比例。请先调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以获取实际值。 |
| **double** [get_ActualMaxValue](./get_actualmaxvalue/)() override | 指定轴上的实际最大值。请先调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以获取实际值。 |
| **double** [get_ActualMinorUnit](./get_actualminorunit/)() override | 指定轴的实际次单位。请先调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以获取实际值。 |
| [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() override | 指定轴的实际次单位比例。请先调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以获取实际值。 |
| **double** [get_ActualMinValue](./get_actualminvalue/)() override | 指定轴上的实际最小值。请先调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以获取实际值。 |
| [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() override | 表示分类轴的聚合类型（分箱）。适用于分类轴，仅在直方图或 HistogramPareto 系列中使用。 |
| **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() override | 表示值轴是否在分类之间跨越分类轴。此属性仅适用于分类轴，不适用于 3D 图表。读取 **bool**。 |
| [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() override | 指定日期轴上表示的最小时间单位。读取 [TimeUnitType](../timeunittype/)。 |
| **double** [get_BinWidth](./get_binwidth/)() override | 当 AggregationType 属性值设为 [AxisAggregationType::ByBinWidth](../axisaggregationtype/) 时指定分箱宽度。适用于分类轴，仅在直方图或 HistogramPareto 系列中使用。 |
| [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() override | 指定分类轴的类型。读取 [Charts::CategoryAxisType](../categoryaxistype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 返回父图表。只读 [IChart](../ichart/)。 |
| **float** [get_CrossAt](./get_crossat/)() override | 表示轴上垂直轴相交的点。读取 **float**。 |
| [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() override | 表示指定轴上另一轴相交的 CrossType。读取 [CrossesType](../crossestype/)。 |
| [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() override | 指定值轴显示单位的缩放值。读取 [DisplayUnitType](../displayunittype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() override | 表示轴的格式。只读 [IAxisFormat](../iaxisformat/)。 |
| **bool** [get_HasTitle](./get_hastitle/)() override | 确定轴是否具有可见标题。读取 **bool**。 |
| **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() override | 指示轴的主单位是否自动分配。读取 **bool**。 |
| **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() override | 指示最大值是否自动分配。读取 **bool**。 |
| **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() override | 指示轴的次单位是否自动分配。读取 **bool**。 |
| **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() override | 指示最小值是否自动分配。读取 **bool**。 |
| **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() override | 指定自动溢出分箱值。如果为 false：使用 OverflowBin 属性。 |
| **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() override | 指定自动刻度标签间距值。如果为 false：使用 TickLabelSpacing 属性。读取 **bool**。 |
| **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() override | 指定自动刻度标记间距值。如果为 false：使用 TickMarksSpacing 属性。读取 **bool**。 |
| **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() override | 指定自动下溢分箱值。如果为 false：使用 UnderflowBin 属性。 |
| **bool** [get_IsLogarithmic](./get_islogarithmic/)() override | 表示值轴的刻度类型是否为对数。读取 **bool**。 |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | 指示格式是否为链接的源数据。读取 **bool**。 |
| **bool** [get_IsOverflowBin](./get_isoverflowbin/)() override | 指定是否应用溢出分箱。使用 IsAutomaticOverflowBin 和 OverflowBin 调整溢出分箱值。 |
| **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() override | 表示 MS PowerPoint 是否从最后到第一个绘制数据点。读取 **bool**。 |
| **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() override | 指定是否应用下溢分箱。使用 IsAutomaticUnderflowBin 和 UnderflowBin 调整下溢分箱值。 |
| **bool** [get_IsVisible](./get_isvisible/)() override | 表示轴是否可见。读取 **bool**。 |
| **uint16_t** [get_LabelOffset](./get_labeloffset/)() override | 指定标签距轴的距离。适用于分类或日期轴。值必须介于 0% 到 1000% 之间。读取 **uint16_t**。 |
| **double** [get_LogBase](./get_logbase/)() override | 表示对数基数。默认值为 10。读取 **double**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() override | 表示图表轴上主要网格线的格式。只读 [IChartLinesFormat](../ichartlinesformat/)。 |
| [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() override | 表示指定轴的主要刻度标记类型。读取 [TickMarkType](../tickmarktype/)。 |
| **double** [get_MajorUnit](./get_majorunit/)() override | 表示日期或数值轴的主要单位。读取 **double**。 |
| [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() override | 表示日期轴的主要单位比例。读取 [TimeUnitType](../timeunittype/)。 |
| **double** [get_MaxValue](./get_maxvalue/)() override | 表示值轴的最大值。读取 **double**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() override | 表示图表轴上次要网格线的格式。只读 [IChartLinesFormat](../ichartlinesformat/)。 |
| [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() override | 表示指定轴的次要刻度标记类型。读取 [TickMarkType](../tickmarktype/)。 |
| **double** [get_MinorUnit](./get_minorunit/)() override | 表示日期或数值轴的次要单位。读取 **double**。 |
| [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() override | 表示日期轴的主要单位比例。读取 [TimeUnitType](../timeunittype/)。 |
| **double** [get_MinValue](./get_minvalue/)() override | 表示值轴的最小值。读取 **double**。 |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | 表示 [Axis](./) 标签的格式字符串。读取 [System::String](../../system/string/)。 |
| **uint32_t** [get_NumberOfBins](./get_numberofbins/)() override | 当 AggregationType 属性值设为 [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) 时指定分箱数量。适用于分类轴，仅在直方图或 HistogramPareto 系列中使用。 |
| **double** [get_OverflowBin](./get_overflowbin/)() override | 指定溢出分箱的自定义值。当 IsAutomaticOverflowBin 属性设为 false 且 IsOverflowBin 属性为 true 时适用。 |
| [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() override | 表示轴的位置。读取 [AxisPositionType](../axispositiontype/)。 |
| **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() override | 要隐藏主要网格线，将 [get_MajorGridLinesFormat()](./get_majorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() 设置为 [FillType::NoFill](../../aspose.slides/filltype/)。只读 **bool**。 |
| **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() override | 要隐藏次要网格线，将 [get_MinorGridLinesFormat()](./get_minorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() 设置为 [FillType::NoFill](../../aspose.slides/filltype/)。只读 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | 表示文本的格式。只读 [IChartTextFormat](../icharttextformat/)。 |
| [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() override | 表示指定轴上刻度标签的位置。读取 [TickLabelPositionType](../ticklabelpositiontype/)。 |
| **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() override | 表示刻度标签的旋转角度。读取 **float**。 |
| **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() override | 指定在已绘制标签之间跳过的刻度标签数量。适用于分类或系列轴。读取 **uint32_t**。 |
| **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() override | 指定在绘制下一个刻度标记之前应跳过的刻度标记数量。适用于分类或系列轴。读取 **uint16_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() override | 获取轴的标题。只读 [IChartTitle](../icharttitle/)。 |
| **double** [get_UnderflowBin](./get_underflowbin/)() override | 指定下溢分箱的自定义值。当 IsAutomaticUnderflowBin 属性设为 false 且 IsUnderflowBin 属性为 true 时适用。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 所描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，只是初始化新对象并允许复制构造子类。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许复制构造子类。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串和 nullptr 情形下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串情形下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) override | 表示分类轴的聚合类型（分箱）。适用于分类轴，仅在直方图或 HistogramPareto 系列中使用。 |
| void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) override | 表示值轴是否在分类之间跨越分类轴。此属性仅适用于分类轴，不适用于 3D 图表。写入 **bool**。 |
| void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) override | 指定日期轴上表示的最小时间单位。写入 [TimeUnitType](../timeunittype/)。 |
| void [set_BinWidth](./set_binwidth/)(**double**) override | 当 AggregationType 属性值设为 [AxisAggregationType::ByBinWidth](../axisaggregationtype/) 时指定分箱宽度。适用于分类轴，仅在直方图或 HistogramPareto 系列中使用。 |
| void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) override | 指定分类轴的类型。写入 [Charts::CategoryAxisType](../categoryaxistype/)。 |
| void [set_CrossAt](./set_crossat/)(**float**) override | 表示轴上垂直轴相交的点。写入 **float**。 |
| void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) override | 表示指定轴上另一轴相交的 CrossType。写入 [CrossesType](../crossestype/)。 |
| void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) override | 指定值轴显示单位的缩放值。写入 [DisplayUnitType](../displayunittype/)。 |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | 确定轴是否具有可见标题。写入 **bool**。 |
| void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) override | 指示轴的主单位是否自动分配。写入 **bool**。 |
| void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) override | 指示最大值是否自动分配。写入 **bool**。 |
| void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) override | 指示轴的次单位是否自动分配。写入 **bool**。 |
| void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) override | 指示最小值是否自动分配。写入 **bool**。 |
| void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) override | 指定自动溢出分箱值。如果为 false：使用 OverflowBin 属性。 |
| void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) override | 指定自动刻度标签间距值。如果为 false：使用 TickLabelSpacing 属性。写入 **bool**。 |
| void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) override | 指定自动刻度标记间距值。如果为 false：使用 TickMarksSpacing 属性。写入 **bool**。 |
| void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) override | 指定自动下溢分箱值。如果为 false：使用 UnderflowBin 属性。 |
| void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) override | 表示值轴的刻度类型是否为对数。写入 **bool**。 |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | 指示格式是否为链接的源数据。写入 **bool**。 |
| void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) override | 指定是否应用溢出分箱。使用 IsAutomaticOverflowBin 和 OverflowBin 调整溢出分箱值。 |
| void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) override | 表示 MS PowerPoint 是否从最后到第一个绘制数据点。写入 **bool**。 |
| void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) override | 指定是否应用下溢分箱。使用 IsAutomaticUnderflowBin 和 UnderflowBin 调整下溢分箱值。 |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | 表示轴是否可见。写入 **bool**。 |
| void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) override | 指定标签距轴的距离。适用于分类或日期轴。值必须介于 0% 到 1000% 之间。写入 **uint16_t**。 |
| void [set_LogBase](./set_logbase/)(**double**) override | 表示对数基数。默认值为 10。写入 **double**。 |
| void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) override | 表示指定轴的主要刻度标记类型。写入 [TickMarkType](../tickmarktype/)。 |
| void [set_MajorUnit](./set_majorunit/)(**double**) override | 表示日期或数值轴的主要单位。写入 **double**。 |
| void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) override | 表示日期轴的主要单位比例。写入 [TimeUnitType](../timeunittype/)。 |
| void [set_MaxValue](./set_maxvalue/)(**double**) override | 表示值轴的最大值。写入 **double**。 |
| void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) override | 表示指定轴的次要刻度标记类型。写入 [TickMarkType](../tickmarktype/)。 |
| void [set_MinorUnit](./set_minorunit/)(**double**) override | 表示日期或数值轴的次要单位。写入 **double**。 |
| void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) override | 表示日期轴的主要单位比例。写入 [TimeUnitType](../timeunittype/)。 |
| void [set_MinValue](./set_minvalue/)(**double**) override | 表示值轴的最小值。写入 **double**。 |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | 表示 [Axis](./) 标签的格式字符串。写入 [System::String](../../system/string/)。 |
| void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) override | 当 AggregationType 属性值设为 [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) 时指定分箱数量。适用于分类轴，仅在直方图或 HistogramPareto 系列中使用。 |
| void [set_OverflowBin](./set_overflowbin/)(**double**) override | 指定溢出分箱的自定义值。当 IsAutomaticOverflowBin 属性设为 false 且 IsOverflowBin 属性为 true 时适用。 |
| void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) override | 表示轴的位置。写入 [AxisPositionType](../axispositiontype/)。 |
| void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) override | 表示指定轴上刻度标签的位置。写入 [TickLabelPositionType](../ticklabelpositiontype/)。 |
| void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) override | 表示刻度标签的旋转角度。写入 **float**。 |
| void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) override | 指定在已绘制标签之间跳过的刻度标签数量。适用于分类或系列轴。写入 **uint32_t**。 |
| void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) override | 指定在绘制下一个刻度标记之前应跳过的刻度标记数量。适用于分类或系列轴。写入 **uint16_t**。 |
| void [set_UnderflowBin](./set_underflowbin/)(**double**) override | 指定下溢分箱的自定义值。当 IsAutomaticUnderflowBin 属性设为 false 且 IsUnderflowBin 属性为 true 时适用。 |
| void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() override | 设置 IAxis::get(set)_CategoryAxisType 属性，使其值根据轴数据自动确定。 |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取当前共享引用计数的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 减少并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 结构。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 减少弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参见

* 类 [DomObject](../../aspose.slides/domobject/)
* 类 [IAxis](../iaxis/)
* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)