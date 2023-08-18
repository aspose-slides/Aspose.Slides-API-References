---
title: IChartDataPoint
second_title: Aspose.Slides for C++ API Reference
description: Represents series data point.
type: docs
weight: 677
url: /aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint class


Represents series data point.

```cpp
class IChartDataPoint : public Aspose::Slides::Charts::IActualLayout
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
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Specifies actual height of the chart element. Call method [IChart::ValidateChartLayout](../ichart/validatechartlayout/) before to get actual values. Read **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Specifies actual width of the chart element. Call method [IChart::ValidateChartLayout](../ichart/validatechartlayout/) before to get actual values. Read **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Specifies actual x location (left) of the chart element relative to the left top corner of the chart. Call method [IChart::ValidateChartLayout](../ichart/validatechartlayout/) before to get actual values. Read **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Specifies actual top of the chart element relative to the left top corner of the chart. Call method [IChart::ValidateChartLayout](../ichart/validatechartlayout/) before to get actual values. Read **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_BubbleSize](./get_bubblesize/)() | Returns the bubble size of chart data point. Read-only [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_ColorValue](./get_colorvalue/)() | Returns the color value of chart data point. Used with Map charts. Read-only [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevel](../ichartdatapointlevel/)\> [get_DataPointLevel](./get_datapointlevel/)(**int32_t**) | Returns a data point level at the specified index. Applied for Treeamp and Sunburst series. Data point levels indexing is zero-based. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevelsManager](../ichartdatapointlevelsmanager/)\> [get_DataPointLevels](./get_datapointlevels/)() | Returns container of data point levels. Applied for Treeamp and Sunburst series. Data point levels indexing is zero-based. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsCustomValues](../ierrorbarscustomvalues/)\> [get_ErrorBarsCustomValues](./get_errorbarscustomvalues/)() | Represents series error bars values in case of Custom value type. Read-only [IErrorBarsCustomValues](../ierrorbarscustomvalues/). |
| virtual **int32_t** [get_Explosion](./get_explosion/)() | Specifies the amount the data point shall be moved from the center of the pie. Read **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Represents the formatting properties. Read [IFormat](../iformat/). |
| virtual **uint32_t** [get_Index](./get_index/)() | Determines which of the parent's children collection this data point applies to. Read **uint32_t**. |
| virtual **bool** [get_InvertIfNegative](./get_invertifnegative/)() | Specifies the data point shall invert its colors if the value is negative. Read **bool**. |
| virtual **bool** [get_IsBubble3D](./get_isbubble3d/)() | Specifies that the bubbles have a 3-D effect applied to them. Read **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)() | Represents the lable of chart data point. Read-only [IDataLabel](../idatalabel/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() | Specifies a data marker. Read-only [IMarker](../imarker/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | Properties of corresponding legend entry in case of chart type from this list: [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/). Read-only [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual **bool** [get_SetAsTotal](./get_setastotal/)() | Sets data point as total. Applied for Waterfall series type only. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_SizeValue](./get_sizevalue/)() | Returns the size value of chart data point. Used with Treemap and Sunburst charts. Read-only [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_Value](./get_value/)() | Returns the value of chart data point. Read-only [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IStringOrDoubleChartValue](../istringordoublechartvalue/)\> [get_XValue](./get_xvalue/)() | Returns the x value of chart data point. Read-only [IStringOrDoubleChartValue](../istringordoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_YValue](./get_yvalue/)() | Returns the y value of chart data point. Read-only [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticDataPointColor](./getautomaticdatapointcolor/)() | Returns an automatic color of data point based on series index, data point index, ParentSeriesGroup.IsColorVaried propery and chart style. This color is used by default if FillType equals NotDefined. |
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
| virtual void [Remove](./remove/)() | Removes DataPoint from chart series. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| virtual void [set_Explosion](./set_explosion/)(**int32_t**) | Specifies the amount the data point shall be moved from the center of the pie. Write **int32_t**. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | Represents the formatting properties. Write [IFormat](../iformat/). |
| virtual void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) | Specifies the data point shall invert its colors if the value is negative. Write **bool**. |
| virtual void [set_IsBubble3D](./set_isbubble3d/)(**bool**) | Specifies that the bubbles have a 3-D effect applied to them. Write **bool**. |
| virtual void [set_SetAsTotal](./set_setastotal/)(**bool**) | Sets data point as total. Applied for Waterfall series type only. |
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

* Class [IActualLayout](../iactuallayout/)
* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)