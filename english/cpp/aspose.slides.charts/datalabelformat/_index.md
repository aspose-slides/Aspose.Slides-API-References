---
title: DataLabelFormat
second_title: Aspose.Slides for C++ API Reference
description: Represents formatting options for DataLabel.
type: docs
weight: 391
url: /cpp/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat class


Represents formatting options for [DataLabel](../datalabel/).

```cpp
class DataLabelFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::Charts::IDataLabelFormat
```

## Methods

| Method | Description |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Compares with specified object. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Returns the chart. Read-only [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Represents the format of the data label. Read-only [IFormat](../iformat/). |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Read **bool**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | Represents the format string for the DataLabels object. Read [System::String](../../system/string/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | Returns Parent_Immediate object. Read-only [IDOMObject](../../aspose.slides/idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Returns parent [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). Read-only [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() override | Represents the position of the data label. Read [LegendDataLabelPosition](../legenddatalabelposition/). |
| [System::String](../../system/string/) [get_Separator](./get_separator/)() override | Sets or returns a Variant representing the separator used for the data labels on a chart. Read [System::String](../../system/string/). |
| **bool** [get_ShowBubbleSize](./get_showbubblesize/)() override | Represents a specified chart's data label bubble size value display behavior. True displays the bubble size value. False to hide. Read **bool**. |
| **bool** [get_ShowCategoryName](./get_showcategoryname/)() override | Represents a specified chart's data label category name display behavior. True to display the category name for the data labels on a chart. False to hide. Read **bool**. |
| **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() override | Determines either specified chart's data label will be displayed as data callout or as data label. |
| **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() override | Represents a specified chart's data label cell value display behavior. True displays cell value. False to hide. Read **bool**. |
| **bool** [get_ShowLeaderLines](./get_showleaderlines/)() override | Represents a specified chart's data label leader lines display behavior. True displays the leader lines. False to hide. Read **bool**. |
| **bool** [get_ShowLegendKey](./get_showlegendkey/)() override | Represents a specified chart's data label legend key display behavior. True if the data label legend key is visible. Read **bool**. |
| **bool** [get_ShowPercentage](./get_showpercentage/)() override | Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Read **bool**. |
| **bool** [get_ShowSeriesName](./get_showseriesname/)() override | Returns a Boolean to indicate the series name display behavior for the data labels on a chart. True to show the series name. False to hide. Read **bool**. |
| **bool** [get_ShowValue](./get_showvalue/)() override | Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Read **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Returns chart text format. Read-only [IChartTextFormat](../icharttextformat/). |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Version. Read-only **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | Returns hash code. |
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
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Write **bool**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | Represents the format string for the DataLabels object. Write [System::String](../../system/string/). |
| void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) override | Represents the position of the data label. Write [LegendDataLabelPosition](../legenddatalabelposition/). |
| void [set_Separator](./set_separator/)([System::String](../../system/string/)) override | Sets or returns a Variant representing the separator used for the data labels on a chart. Write [System::String](../../system/string/). |
| void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) override | Represents a specified chart's data label bubble size value display behavior. True displays the bubble size value. False to hide. Write **bool**. |
| void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) override | Represents a specified chart's data label category name display behavior. True to display the category name for the data labels on a chart. False to hide. Write **bool**. |
| void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) override | Determines either specified chart's data label will be displayed as data callout or as data label. |
| void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) override | Represents a specified chart's data label cell value display behavior. True displays cell value. False to hide. Write **bool**. |
| void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) override | Represents a specified chart's data label leader lines display behavior. True displays the leader lines. False to hide. Write **bool**. |
| void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) override | Represents a specified chart's data label legend key display behavior. True if the data label legend key is visible. Write **bool**. |
| void [set_ShowPercentage](./set_showpercentage/)(**bool**) override | Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Write **bool**. |
| void [set_ShowSeriesName](./set_showseriesname/)(**bool**) override | Sets a Boolean to indicate the series name display behavior for the data labels on a chart. True to show the series name. False to hide. Write **bool**. |
| void [set_ShowValue](./set_showvalue/)(**bool**) override | Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Write **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [PVIObject](../../aspose.slides/pviobject/)
* Class [IDataLabelFormat](../idatalabelformat/)
* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)