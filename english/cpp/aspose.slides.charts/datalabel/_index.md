---
title: DataLabel
second_title: Aspose.Slides for C++ API Reference
description: Represents a series labels.
type: docs
weight: 365
url: /cpp/aspose.slides.charts/datalabel/
---
## DataLabel class


Represents a series labels.

```cpp
class DataLabel : public Aspose::Slides::Charts::IDataLabel,
                  public Aspose::Slides::IDOMObject
```

## Methods

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Initialize TextFrameForOverriding with the text in paramener \"text\". If TextFrameForOverriding is already initialized then simply changes its text. |
|  [DataLabel](./datalabel/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) | Creates a new instance of [DataLabel](./) class. |
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
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Returns the parent chart. Read-only [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() override | Returns data label format. Read-only [IDataLabelFormat](../idatalabelformat/). |
| **float** [get_Height](./get_height/)() override | Returns the height of a title as a fraction of the height of the chart. Read **float**. |
| **bool** [get_IsVisible](./get_isvisible/)() override | False means that data label is not visible (and so all Show*-flags (ShowValue, ...) are false). Read-only **bool**. |
| **float** [get_Right](./get_right/)() override | Right. Read-only **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Returns text format. Read-only [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Can contain a rich formatted text. If this property is not null then this formatted text value overrides auto-generated text of data label. Auto-generated text of data label means text that is managed by ShowSeriesName, ShowValue, ... properties and is formatted with the TextFormatManager.TextFormat property. Read-only [ITextFrame](../../aspose.slides/itextframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() override | Gets workbook data cell. Applied if IDataLabelFormat::get(set)_ShowLabelValueFromCell property equals true. |
| **float** [get_Width](./get_width/)() override | Returns the width of a title as a fraction of the width of the chart. Read **float**. |
| **float** [get_X](./get_x/)() override | Returns the x coordinate of a title as a fraction of the width of the chart. Read **float**. |
| **float** [get_Y](./get_y/)() override | Returns the y coordinate of a title as a fraction of the height of the chart. Read **float**. |
| [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() override | Returns actual label text based on [DataLabelFormat](../datalabelformat/) settings or [get_TextFrameForOverriding()](./get_textframeforoverriding/)->get(set)_Text() value. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| void [Hide](./hide/)() override | Make data label hidden by setting all Show*-flags (ShowValue, ...) to false state. IsVisible will be false after this. |
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
| void [set_Height](./set_height/)(**float**) override | Sets the height of a title as a fraction of the height of the chart. Write **float**. |
| void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) override | Sets workbook data cell. Applied if IDataLabelFormat::get(set)_ShowLabelValueFromCell property equals true. |
| void [set_Width](./set_width/)(**float**) override | Sets the width of a title as a fraction of the width of the chart. Write **float**. |
| void [set_X](./set_x/)(**float**) override | Sets the x coordinate of a title as a fraction of the width of the chart. Write **float**. |
| void [set_Y](./set_y/)(**float**) override | Sets the y coordinate of a title as a fraction of the height of the chart. Write **float**. |
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

* Class [IDataLabel](../idatalabel/)
* Class [IDOMObject](../../aspose.slides/idomobject/)
* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)