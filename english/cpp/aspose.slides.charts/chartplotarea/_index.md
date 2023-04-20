---
title: ChartPlotArea
second_title: Aspose.Slides for C++ API Reference
description: Represents rectangle where chart should be plotted.
type: docs
weight: 248
url: /cpp/aspose.slides.charts/chartplotarea/
---
## ChartPlotArea class


Represents rectangle where chart should be plotted.

```cpp
class ChartPlotArea : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                      public Aspose::Slides::Charts::IChartPlotArea
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
| **float** [get_ActualHeight](./get_actualheight/)() override | Specifies actual height of the chart element. Call method [IChart::ValidateChartLayout](../ichart/validatechartlayout/) before to get actual values. Read **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Specifies actual width of the chart element. Call method [IChart::ValidateChartLayout](../ichart/validatechartlayout/) before to get actual values. Read **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Specifies actual x location (left) of the chart element relative to the left top corner of the chart. Call method [IChart::ValidateChartLayout](../ichart/validatechartlayout/) before to get actual values. Read **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Specifies actual top of the chart element relative to the left top corner of the chart. Call method [IChart::ValidateChartLayout](../ichart/validatechartlayout/) before to get actual values. Read **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Bottom. Read-only **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | [Chart](../chart/). Read-only [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Returns the format of a plot area. Read-only [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Returns the height of a plot area bounding box as a fraction of the height of the chart (from 0 to 1). Read **float**. |
| **bool** [get_IsLocationAutocalculated](./get_islocationautocalculated/)() | Defines how location should be calculated: true \\u2013 calculated automatically; defined by the X, Y, Width, Height properties. Read-only **bool**. |
| [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() override | If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside (not including axis and axis labels) or outside (including axis and axis labels). Read [LayoutTargetType](../layouttargettype/). |
| **float** [get_Right](./get_right/)() override | Right. Read-only **float**. |
| **float** [get_Width](./get_width/)() override | Returns the width of a plot area bounding box as a fraction of the width of the chart (from 0 to 1). Read **float**. |
| **float** [get_X](./get_x/)() override | Returns the x coordinate of the upper left corner of plot area bounding box as a fraction of the width of the chart (from 0 to 1). Read **float**. |
| **float** [get_Y](./get_y/)() override | Returns the y coordinate of the upper left corner of plot area bounding box as a fraction of the height of the chart (from 0 to 1). Read **float**. |
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
| void [set_Height](./set_height/)(**float**) override | Sets the height of a plot area bounding box as a fraction of the height of the chart (from 0 to 1). Write **float**. |
| void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) override | If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside (not including axis and axis labels) or outside (including axis and axis labels). Write [LayoutTargetType](../layouttargettype/). |
| void [set_Width](./set_width/)(**float**) override | Sets the width of a plot area bounding box as a fraction of the width of the chart (from 0 to 1). Write **float**. |
| void [set_X](./set_x/)(**float**) override | Sets the x coordinate of the upper left corner of plot area bounding box as a fraction of the width of the chart (from 0 to 1). Write **float**. |
| void [set_Y](./set_y/)(**float**) override | Sets the y coordinate of the upper left corner of plot area bounding box as a fraction of the height of the chart (from 0 to 1). Write **float**. |
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
* Class [IChartPlotArea](../ichartplotarea/)
* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)