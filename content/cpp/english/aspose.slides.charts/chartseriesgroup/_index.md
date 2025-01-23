---
title: ChartSeriesGroup
second_title: Aspose.Slides for C++ API Reference
description: Represents group of series.
type: docs
weight: 300
url: /aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup class


Represents group of series.

```cpp
class ChartSeriesGroup : public Aspose::Slides::Charts::IChartSeriesGroup,
                         public Aspose::Slides::IDOMObject
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
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | Specifies how the bubble size values are represented on the bubble chart. Read [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). Read **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Returns the parent chart. Read-only [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | Returns the chart series in the group at the specified index. |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | Specifies the size of the hole in a doughnut chart (can be between 0 and 90 percents of the size of the plot area.). Read **uint8_t**. |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | Gets the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). Read **uint16_t**. |
| **uint16_t** [get_GapDepth](./get_gapdepth/)() override | Returns the distance, as a percentage of the marker width, between the data series in a 3D chart. Read **uint16_t**. |
| **uint16_t** [get_GapWidth](./get_gapwidth/)() override | Specifies the space between bar or column clusters, as a percentage of the bar or column width. Read **uint16_t**. |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | True if chart has series lines. Applied to stacked bar and OfPie charts. Read **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() override | Specifies HiLowLines format. HiLowLines applied with HiLowClose, OpenHiLowClose, VolumeHiLowClose and VolumeOpenHiLowClose chart types. |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | Specifies that each data marker in the series has a different color. Read **bool**. |
| **int8_t** [get_Overlap](./get_overlap/)() override | Specifies how much bars and columns shall overlap on 2-D charts, as a percentage (from -100% to 100%). |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Read [PieSplitType](../piesplittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. Returns data point that shall be drawn in the second pie or bar in a pie-of-pie or bar-of-pie chart by index. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or bar-of-pie chart. Read-only [PieSplitCustomPointCollection](../piesplitcustompointcollection/). |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. Read **double**. |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | Indicates if series of this group is plotted on secondary axis. Read-only **bool**. |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). Read **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() override | Returns a collection of series. Read-only [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() override | Returns a type of this series group. Read-only [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() override | Provede access to up/down bars of Line- or Stock-chart. Read-only [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) override | Gets the element at the specified index. |
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
| void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) override | Specifies how the bubble size values are represented on the bubble chart. Write [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) override | Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). Write **int32_t**. |
| void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) override | Specifies the size of the hole in a doughnut chart (can be between 0 and 90 percents of the size of the plot area.). Write **uint8_t**. |
| void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) override | Sets the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). Write **uint16_t**. |
| void [set_GapDepth](./set_gapdepth/)(**uint16_t**) override | Sets the distance, as a percentage of the marker width, between the data series in a 3D chart. Write **uint16_t**. |
| void [set_GapWidth](./set_gapwidth/)(**uint16_t**) override | Specifies the space between bar or column clusters, as a percentage of the bar or column width. Write **uint16_t**. |
| void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) override | True if chart has series lines. Applied to stacked bar and OfPie charts. Write **bool**. |
| void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) override | Specifies that each data marker in the series has a different color. Write **bool**. |
| void [set_Overlap](./set_overlap/)(**int8_t**) override | Specifies how much bars and columns shall overlap on 2-D charts, as a percentage (from -100% to 100%). |
| void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) override | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Write [PieSplitType](../piesplittype/). |
| void [set_PieSplitPosition](./set_piesplitposition/)(**double**) override | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. Write **double**. |
| void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) override | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). Write **uint16_t**. |
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
## Remarks


1) See summary and remarks for ChartSeriesGroupCollection class and CombinableSeriesTypesGroup enum. 2) Group of series contains some series properies whitch is common for each series in group (\"series group properties\"). \"Series group properties\" in [ChartSeriesGroup](./) class is read/write. Each of \"series group properties\" can have a read-only projection in [ChartSeries](../chartseries/) class. 
## See Also

* Class [IChartSeriesGroup](../ichartseriesgroup/)
* Class [IDOMObject](../../aspose.slides/idomobject/)
* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)