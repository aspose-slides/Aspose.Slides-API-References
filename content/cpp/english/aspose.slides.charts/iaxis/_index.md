---
title: IAxis
second_title: Aspose.Slides for C++ API Reference
description: Encapsulates the object that represents a chart's axis.
type: docs
weight: 534
url: /aspose.slides.charts/iaxis/
---
## IAxis class


Encapsulates the object that represents a chart's axis.

```cpp
class IAxis : public Aspose::Slides::Charts::IFormattedTextContainer
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
| virtual **double** [get_ActualMajorUnit](./get_actualmajorunit/)() | Specifies actual major unit of the axis. Call method [IChart::ValidateChartLayout](../ichart/validatechartlayout/) previously to get actual value. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() | Specifies actual major unit scale of the axis. Call method [IChart::ValidateChartLayout](../ichart/validatechartlayout/) previously to get actual value. |
| virtual **double** [get_ActualMaxValue](./get_actualmaxvalue/)() | Specifies actual maximum value on the axis. Call method [IChart::ValidateChartLayout](../ichart/validatechartlayout/) previously to get actual value. |
| virtual **double** [get_ActualMinorUnit](./get_actualminorunit/)() | Specifies actual minor unit of the axis. Call method [IChart::ValidateChartLayout](../ichart/validatechartlayout/) previously to get actual value. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() | Specifies actual minor unit scale of the axis. Call method [IChart::ValidateChartLayout](../ichart/validatechartlayout/) previously to get actual value. |
| virtual **double** [get_ActualMinValue](./get_actualminvalue/)() | Specifies actual minimum value on the axis. Call method [IChart::ValidateChartLayout](../ichart/validatechartlayout/) previously to get actual value. |
| virtual [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() | Represents aggregation type of category axis (binning). Applied to category. Used with Histogram or HistogramPareto series only. |
| virtual **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() | Represents if the value axis crosses the category axis between categories. This property applies only to category axes, and it doesn't apply to 3-D charts. Read **bool**. |
| virtual [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() | Specifies the smallest time unit that is represented on the date axis. Read [TimeUnitType](../timeunittype/). |
| virtual **double** [get_BinWidth](./get_binwidth/)() | Specifies bin width when AggregationType property value setted to [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Applied to category axes. Used with Histogram or HistogramPareto series only. |
| virtual [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() | Specifies the type of the category axis. Read [CategoryAxisType](../categoryaxistype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Returns the chart. Read-only [IChart](../ichart/). |
| virtual **float** [get_CrossAt](./get_crossat/)() | Represents the point on the axis where the perpendicular axis crosses it. Read **float**. |
| virtual [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() | Represents the CrossType on the specified axis where the other axis crosses. Read [CrossesType](../crossestype/). |
| virtual [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() | Specifies the scaling value of the display units for the value axis. Read [DisplayUnitType](../displayunittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() | Represents format of axis. Read-only [IAxisFormat](../iaxisformat/). |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | Determines whether a axis has a visible title. Read **bool**. |
| virtual **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() | Indicates whether the major unit of the axis is automatically assigned. Read **bool**. |
| virtual **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() | Indicates whether the max value is automatically assigned. Read **bool**. |
| virtual **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() | Indicates whether the minor unit of the axis is automatically assigned. Read **bool**. |
| virtual **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() | Indicates whether the min value is automatically assigned. Read **bool**. |
| virtual **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() | Specifies automatic overflow bin value. If false: use OverflowBin property. |
| virtual **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() | Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. Read **bool**. |
| virtual **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() | Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. Read **bool**. |
| virtual **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() | Specifies automatic underflow bin value. If false: use UnderflowBin property. |
| virtual **bool** [get_IsLogarithmic](./get_islogarithmic/)() | Represents if the value axis scale type is logarithmic or not. Read **bool**. |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Indicates whether the format is linked source data. Read **bool**. |
| virtual **bool** [get_IsOverflowBin](./get_isoverflowbin/)() | Specifies if overflow bin applied. Use IsAutomaticOverflowBin and OverflowBin to adjust overflow bin value. |
| virtual **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() | Represents if MS PowerPoint plots data points from last to first. Read **bool**. |
| virtual **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() | Specifies if underflow bin applied. Use IsAutomaticUnderflowBin and UnderflowBin to adjust underflow bin value. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | Represents if the axis is visible. Read **bool**. |
| virtual **uint16_t** [get_LabelOffset](./get_labeloffset/)() | Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. Read **uint16_t**. |
| virtual **double** [get_LogBase](./get_logbase/)() | Represents the logarithmic base. Default value is 10. Read **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() | Represents major gridlines format on a chart axis. Read-only [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() | Represents the type of major tick mark for the specified axis. Read [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MajorUnit](./get_majorunit/)() | Represents the major units for the date or value axis. Read **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() | Represents the major unit scale for the date axis. Read [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MaxValue](./get_maxvalue/)() | Represents the maximum value on the value axis. Read **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() | Represents minor gridlines format on a chart axis. Read-only [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() | Represents the type of minor tick mark for the specified axis. Read [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MinorUnit](./get_minorunit/)() | Represents the minor units for the date or value axis. Read **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() | Represents the major unit scale for the date axis. Read [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MinValue](./get_minvalue/)() | Represents the minimum value on the value axis. Read **double**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | Represents the format string for the [Axis](../axis/) Labels. Read [System::String](../../system/string/). |
| virtual **uint32_t** [get_NumberOfBins](./get_numberofbins/)() | Specifies number of bins when AggregationType property value setted to [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Applied to category axes. Used with Histogram or HistogramPareto series only. |
| virtual **double** [get_OverflowBin](./get_overflowbin/)() | Specifies overflow bin custom value. Applied when IsAutomaticOverflowBin property setted to false and IsOverflowBin property equals true. |
| virtual [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() | Represents position of axis. Read [AxisPositionType](../axispositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Returns the presentation. Read-only [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() | Represents if the major gridlines showed. Read-only **bool**. |
| virtual **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() | Represents if the minor gridlines showed. Read-only **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Returns the base slide. Read-only [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Returns chart text format. Read-only [IChartTextFormat](../icharttextformat/). |
| virtual [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() | Represents the position of tick-mark labels on the specified axis. Read [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() | Represents the rotation angle of tick labels Read **float**. |
| virtual **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() | Specifies how many tick labels to skip between label that is drawn. Read **uint32_t**. |
| virtual **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() | Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. Read **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() | Gets the axis' title. Read-only [IChartTitle](../icharttitle/). |
| virtual **double** [get_UnderflowBin](./get_underflowbin/)() | Specifies underflow bin custom value. Applied when IsAutomaticUnderflowBin property setted to false and IsUnderflowBin property equals true. |
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
| virtual void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) | Represents aggregation type of category axis (binning). Applied to category. Used with Histogram or HistogramPareto series only. |
| virtual void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) | Represents if the value axis crosses the category axis between categories. This property applies only to category axes, and it doesn't apply to 3-D charts. Write **bool**. |
| virtual void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) | Specifies the smallest time unit that is represented on the date axis. Write [TimeUnitType](../timeunittype/). |
| virtual void [set_BinWidth](./set_binwidth/)(**double**) | Specifies bin width when AggregationType property value setted to [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Applied to category axes. Used with Histogram or HistogramPareto series only. |
| virtual void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) | Specifies the type of the category axis. Write [CategoryAxisType](../categoryaxistype/). |
| virtual void [set_CrossAt](./set_crossat/)(**float**) | Represents the point on the axis where the perpendicular axis crosses it. Write **float**. |
| virtual void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) | Represents the CrossType on the specified axis where the other axis crosses. Write [CrossesType](../crossestype/). |
| virtual void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) | Specifies the scaling value of the display units for the value axis. Write [DisplayUnitType](../displayunittype/). |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | Determines whether a axis has a visible title. Write **bool**. |
| virtual void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) | Indicates whether the major unit of the axis is automatically assigned. Write **bool**. |
| virtual void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) | Indicates whether the max value is automatically assigned. Write **bool**. |
| virtual void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) | Indicates whether the minor unit of the axis is automatically assigned. Write **bool**. |
| virtual void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) | Indicates whether the min value is automatically assigned. Write **bool**. |
| virtual void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) | Specifies automatic overflow bin value. If false: use OverflowBin property. |
| virtual void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) | Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. Write **bool**. |
| virtual void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) | Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. Write **bool**. |
| virtual void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) | Specifies automatic underflow bin value. If false: use UnderflowBin property. |
| virtual void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) | Represents if the value axis scale type is logarithmic or not. Write **bool**. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Indicates whether the format is linked source data. Write **bool**. |
| virtual void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) | Specifies if overflow bin applied. Use IsAutomaticOverflowBin and OverflowBin to adjust overflow bin value. |
| virtual void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) | Represents if MS PowerPoint plots data points from last to first. Write **bool**. |
| virtual void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) | Specifies if underflow bin applied. Use IsAutomaticUnderflowBin and UnderflowBin to adjust underflow bin value. |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | Represents if the axis is visible. Write **bool**. |
| virtual void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) | Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. Write **uint16_t**. |
| virtual void [set_LogBase](./set_logbase/)(**double**) | Represents the logarithmic base. Default value is 10. Write **double**. |
| virtual void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) | Represents the type of major tick mark for the specified axis. Write [TickMarkType](../tickmarktype/). |
| virtual void [set_MajorUnit](./set_majorunit/)(**double**) | Represents the major units for the date or value axis. Write **double**. |
| virtual void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) | Represents the major unit scale for the date axis. Write [TimeUnitType](../timeunittype/). |
| virtual void [set_MaxValue](./set_maxvalue/)(**double**) | Represents the maximum value on the value axis. Write **double**. |
| virtual void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) | Represents the type of minor tick mark for the specified axis. Write [TickMarkType](../tickmarktype/). |
| virtual void [set_MinorUnit](./set_minorunit/)(**double**) | Represents the minor units for the date or value axis. Write **double**. |
| virtual void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) | Represents the major unit scale for the date axis. Write [TimeUnitType](../timeunittype/). |
| virtual void [set_MinValue](./set_minvalue/)(**double**) | Represents the minimum value on the value axis. Write **double**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | Represents the format string for the [Axis](../axis/) Labels. Write [System::String](../../system/string/). |
| virtual void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) | Specifies number of bins when AggregationType property value setted to [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Applied to category axes. Used with Histogram or HistogramPareto series only. |
| virtual void [set_OverflowBin](./set_overflowbin/)(**double**) | Specifies overflow bin custom value. Applied when IsAutomaticOverflowBin property setted to false and IsOverflowBin property equals true. |
| virtual void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) | Represents position of axis. Write [AxisPositionType](../axispositiontype/). |
| virtual void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) | Represents the position of tick-mark labels on the specified axis. Write [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) | Represents the rotation angle of tick labels Write **float**. |
| virtual void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) | Specifies how many tick labels to skip between label that is drawn. Write **uint32_t**. |
| virtual void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) | Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. Write **uint16_t**. |
| virtual void [set_UnderflowBin](./set_underflowbin/)(**double**) | Specifies underflow bin custom value. Applied when IsAutomaticUnderflowBin property setted to false and IsUnderflowBin property equals true. |
| virtual void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() | Sets IAxis::get(set)_CategoryAxisType property with a value that is automatically determined based on axis data. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
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

* Class [IFormattedTextContainer](../iformattedtextcontainer/)
* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)