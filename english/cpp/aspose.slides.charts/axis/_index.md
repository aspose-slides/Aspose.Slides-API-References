---
title: Axis
second_title: Aspose.Slides for C++ API Reference
description: Encapsulates the object that represents a chart's axis.
type: docs
weight: 14
url: /cpp/aspose.slides.charts/axis/
---
## Axis class


Encapsulates the object that represents a chart's axis.

```cpp
class Axis : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::AxesManager>>,
             public Aspose::Slides::Charts::IAxis
```

## Methods

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| **double** [get_ActualMajorUnit](./get_actualmajorunit/)() override | Specifies actual major unit of the axis. Call method [IChart::ValidateChartLayout](../ichart/validatechartlayout/) previously to get actual value. |
| [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() override | Specifies actual major unit scale of the axis. Call method [IChart::ValidateChartLayout](../ichart/validatechartlayout/) previously to get actual value. |
| **double** [get_ActualMaxValue](./get_actualmaxvalue/)() override | Specifies actual maximum value on the axis. Call method [IChart::ValidateChartLayout](../ichart/validatechartlayout/) previously to get actual value. |
| **double** [get_ActualMinorUnit](./get_actualminorunit/)() override | Specifies actual minor unit of the axis. Call method [IChart::ValidateChartLayout](../ichart/validatechartlayout/) previously to get actual value. |
| [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() override | Specifies actual minor unit scale of the axis. Call method [IChart::ValidateChartLayout](../ichart/validatechartlayout/) previously to get actual value. |
| **double** [get_ActualMinValue](./get_actualminvalue/)() override | Specifies actual minimum value on the axis. Call method [IChart::ValidateChartLayout](../ichart/validatechartlayout/) previously to get actual value. |
| [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() override | Represents aggregation type of category axis (binning). Applied to category. Used with Histogram or HistogramPareto series only. |
| **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() override | Represents if the value axis crosses the category axis between categories. This property applies only to category axes, and it doesn't apply to 3-D charts. Read **bool**. |
| [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() override | Specifies the smallest time unit that is represented on the date axis. Read [TimeUnitType](../timeunittype/). |
| **double** [get_BinWidth](./get_binwidth/)() override | Specifies bin width when AggregationType property value setted to [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Applied to category axes. Used with Histogram or HistogramPareto series only. |
| [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() override | Specifies the type of the category axis. Read [Charts::CategoryAxisType](../categoryaxistype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Returns the parent chart. Read-only [IChart](../ichart/). |
| **float** [get_CrossAt](./get_crossat/)() override | Represents the point on the axis where the perpendicular axis crosses it. Read **float**. |
| [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() override | Represents the CrossType on the specified axis where the other axis crosses. Read [CrossesType](../crossestype/). |
| [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() override | Specifies the scaling value of the display units for the value axis. Read [DisplayUnitType](../displayunittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() override | Represents format of axis. Read-only [IAxisFormat](../iaxisformat/). |
| **bool** [get_HasTitle](./get_hastitle/)() override | Determines whether a axis has a visible title. Read **bool**. |
| **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() override | Indicates whether the major unit of the axis is automatically assigned. Read **bool**. |
| **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() override | Indicates whether the max value is automatically assigned. Read **bool**. |
| **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() override | Indicates whether the minor unit of the axis is automatically assigned. Read **bool**. |
| **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() override | Indicates whether the min value is automatically assigned. Read **bool**. |
| **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() override | Specifies automatic overflow bin value. If false: use OverflowBin property. |
| **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() override | Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. Read **bool**. |
| **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() override | Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. Read **bool**. |
| **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() override | Specifies automatic underflow bin value. If false: use UnderflowBin property. |
| **bool** [get_IsLogarithmic](./get_islogarithmic/)() override | Represents if the value axis scale type is logarithmic or not. Read **bool**. |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Indicates whether the format is linked source data. Read **bool**. |
| **bool** [get_IsOverflowBin](./get_isoverflowbin/)() override | Specifies if overflow bin applied. Use IsAutomaticOverflowBin and OverflowBin to adjust overflow bin value. |
| **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() override | Represents if MS PowerPoint plots data points from last to first. Read **bool**. |
| **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() override | Specifies if underflow bin applied. Use IsAutomaticUnderflowBin and UnderflowBin to adjust underflow bin value. |
| **bool** [get_IsVisible](./get_isvisible/)() override | Represents if the axis is visible. Read **bool**. |
| **uint16_t** [get_LabelOffset](./get_labeloffset/)() override | Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. Read **uint16_t**. |
| **double** [get_LogBase](./get_logbase/)() override | Represents the logarithmic base. Default value is 10. Read **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() override | Represents major gridlines format on a chart axis. Read-only [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() override | Represents the type of major tick mark for the specified axis. Read [TickMarkType](../tickmarktype/). |
| **double** [get_MajorUnit](./get_majorunit/)() override | Represents the major units for the date or value axis. Read **double**. |
| [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() override | Represents the major unit scale for the date axis. Read [TimeUnitType](../timeunittype/). |
| **double** [get_MaxValue](./get_maxvalue/)() override | Represents the maximum value on the value axis. Read **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() override | Represents minor gridlines format on a chart axis. Read-only [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() override | Represents the type of minor tick mark for the specified axis. Read [TickMarkType](../tickmarktype/). |
| **double** [get_MinorUnit](./get_minorunit/)() override | Represents the minor units for the date or value axis. Read **double**. |
| [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() override | Represents the major unit scale for the date axis. Read [TimeUnitType](../timeunittype/). |
| **double** [get_MinValue](./get_minvalue/)() override | Represents the minimum value on the value axis. Read **double**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | Represents the format string for the [Axis](./) Labels. Read [System::String](../../system/string/). |
| **uint32_t** [get_NumberOfBins](./get_numberofbins/)() override | Specifies number of bins when AggregationType property value setted to [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Applied to category axes. Used with Histogram or HistogramPareto series only. |
| **double** [get_OverflowBin](./get_overflowbin/)() override | Specifies overflow bin custom value. Applied when IsAutomaticOverflowBin property setted to false and IsOverflowBin property equals true. |
| [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() override | Represents position of axis. Read [AxisPositionType](../axispositiontype/). |
| **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() override | To hide major gridline set [get_MajorGridLinesFormat()](./get_majorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() to [FillType::NoFill](../../aspose.slides/filltype/). Read-only **bool**. |
| **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() override | To hide minor gridline set [get_MinorGridLinesFormat()](./get_minorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() to [FillType::NoFill](../../aspose.slides/filltype/). Read-only **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Represents format of text. Read-only [IChartTextFormat](../icharttextformat/). |
| [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() override | Represents the position of tick-mark labels on the specified axis. Read [TickLabelPositionType](../ticklabelpositiontype/). |
| **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() override | Represents the rotation angle of tick labels. Read **float**. |
| **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() override | Specifies how many tick labels to skip between label that is drawn. Applied to category or series axis. Read **uint32_t**. |
| **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() override | Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. Read **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() override | Gets the axis' title. Read-only [IChartTitle](../icharttitle/). |
| **double** [get_UnderflowBin](./get_underflowbin/)() override | Specifies underflow bin custom value. Applied when IsAutomaticUnderflowBin property setted to false and IsUnderflowBin property equals true. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) override | Represents aggregation type of category axis (binning). Applied to category. Used with Histogram or HistogramPareto series only. |
| void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) override | Represents if the value axis crosses the category axis between categories. This property applies only to category axes, and it doesn't apply to 3-D charts. Write **bool**. |
| void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) override | Specifies the smallest time unit that is represented on the date axis. Write [TimeUnitType](../timeunittype/). |
| void [set_BinWidth](./set_binwidth/)(**double**) override | Specifies bin width when AggregationType property value setted to [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Applied to category axes. Used with Histogram or HistogramPareto series only. |
| void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) override | Specifies the type of the category axis. Write [Charts::CategoryAxisType](../categoryaxistype/). |
| void [set_CrossAt](./set_crossat/)(**float**) override | Represents the point on the axis where the perpendicular axis crosses it. Write **float**. |
| void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) override | Represents the CrossType on the specified axis where the other axis crosses. Write [CrossesType](../crossestype/). |
| void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) override | Specifies the scaling value of the display units for the value axis. Write [DisplayUnitType](../displayunittype/). |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | Determines whether a axis has a visible title. Write **bool**. |
| void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) override | Indicates whether the major unit of the axis is automatically assigned. Write **bool**. |
| void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) override | Indicates whether the max value is automatically assigned. Write **bool**. |
| void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) override | Indicates whether the minor unit of the axis is automatically assigned. Write **bool**. |
| void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) override | Indicates whether the min value is automatically assigned. Write **bool**. |
| void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) override | Specifies automatic overflow bin value. If false: use OverflowBin property. |
| void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) override | Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. Write **bool**. |
| void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) override | Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. Write **bool**. |
| void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) override | Specifies automatic underflow bin value. If false: use UnderflowBin property. |
| void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) override | Represents if the value axis scale type is logarithmic or not. Write **bool**. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Indicates whether the format is linked source data. Write **bool**. |
| void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) override | Specifies if overflow bin applied. Use IsAutomaticOverflowBin and OverflowBin to adjust overflow bin value. |
| void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) override | Represents if MS PowerPoint plots data points from last to first. Write **bool**. |
| void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) override | Specifies if underflow bin applied. Use IsAutomaticUnderflowBin and UnderflowBin to adjust underflow bin value. |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | Represents if the axis is visible. Write **bool**. |
| void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) override | Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. Write **uint16_t**. |
| void [set_LogBase](./set_logbase/)(**double**) override | Represents the logarithmic base. Default value is 10. Write **double**. |
| void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) override | Represents the type of major tick mark for the specified axis. Write [TickMarkType](../tickmarktype/). |
| void [set_MajorUnit](./set_majorunit/)(**double**) override | Represents the major units for the date or value axis. Write **double**. |
| void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) override | Represents the major unit scale for the date axis. Write [TimeUnitType](../timeunittype/). |
| void [set_MaxValue](./set_maxvalue/)(**double**) override | Represents the maximum value on the value axis. Write **double**. |
| void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) override | Represents the type of minor tick mark for the specified axis. Write [TickMarkType](../tickmarktype/). |
| void [set_MinorUnit](./set_minorunit/)(**double**) override | Represents the minor units for the date or value axis. Write **double**. |
| void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) override | Represents the major unit scale for the date axis. Write [TimeUnitType](../timeunittype/). |
| void [set_MinValue](./set_minvalue/)(**double**) override | Represents the minimum value on the value axis. Write **double**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | Represents the format string for the [Axis](./) Labels. Write [System::String](../../system/string/). |
| void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) override | Specifies number of bins when AggregationType property value setted to [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Applied to category axes. Used with Histogram or HistogramPareto series only. |
| void [set_OverflowBin](./set_overflowbin/)(**double**) override | Specifies overflow bin custom value. Applied when IsAutomaticOverflowBin property setted to false and IsOverflowBin property equals true. |
| void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) override | Represents position of axis. Write [AxisPositionType](../axispositiontype/). |
| void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) override | Represents the position of tick-mark labels on the specified axis. Write [TickLabelPositionType](../ticklabelpositiontype/). |
| void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) override | Represents the rotation angle of tick labels. Write **float**. |
| void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) override | Specifies how many tick labels to skip between label that is drawn. Applied to category or series axis. Write **uint32_t**. |
| void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) override | Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. Write **uint16_t**. |
| void [set_UnderflowBin](./set_underflowbin/)(**double**) override | Specifies underflow bin custom value. Applied when IsAutomaticUnderflowBin property setted to false and IsUnderflowBin property equals true. |
| void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() override | Sets IAxis::get(set)_CategoryAxisType property with a value that is automatically determined based on axis data. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [DomObject](../../aspose.slides/domobject/)
* Class [IAxis](../iaxis/)
* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)
