---
title: IChartPlotArea
second_title: Aspose.Slides for C++ API Reference
description: Represents chart title properties.
type: docs
weight: 794
url: /cpp/aspose.slides.charts/ichartplotarea/
---
## IChartPlotArea class


Represents chart title properties.

```cpp
class IChartPlotArea : public Aspose::Slides::Charts::ILayoutable,
                       public Aspose::Slides::Charts::IActualLayout
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
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Gets the top of the chart element as a fraction of the height of the chart. Read-only **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Returns the chart. Read-only [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Returns the format of a plot area. Read-only [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Specifies the height of the chart element as a fraction of the height of the chart. Read **float**. |
| virtual [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() | If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside (not including axis and axis labels) or outside (including axis and axis labels). Read [LayoutTargetType](../layouttargettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Returns the presentation. Read-only [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Gets the right of the chart element as a fraction of the width of the chart. Read-only **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Returns the base slide. Read-only [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Specifies the width of the chart element as a fraction of the width of the chart. Read **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Specifies the x location (left) of the chart element as a fraction of the width of the chart. Read **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Specifies the top of the chart element as a fraction of the height of the chart. Read **float**. |
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
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Specifies the height of the chart element as a fraction of the height of the chart. Write **float**. |
| virtual void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) | If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside (not including axis and axis labels) or outside (including axis and axis labels). Write [LayoutTargetType](../layouttargettype/). |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Specifies the width of the chart element as a fraction of the width of the chart. Write **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Specifies the x location (left) of the chart element as a fraction of the width of the chart. Write **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Specifies the top of the chart element as a fraction of the height of the chart. Write **float**. |
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

* Class [ILayoutable](../ilayoutable/)
* Class [IActualLayout](../iactuallayout/)
* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)