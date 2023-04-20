---
title: ITrendline
second_title: Aspose.Slides for C++ API Reference
description: Class represents trend line of chart series
type: docs
weight: 1223
url: /cpp/aspose.slides.charts/itrendline/
---
## ITrendline class


Class represents trend line of chart series

```cpp
class ITrendline : public Aspose::Slides::Charts::IOverridableText
```

## Methods

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Initialize TextFrameForOverriding with the text in paramener \"text\". If TextFrameForOverriding is already initialized then simply changes its text. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| virtual **double** [get_Backward](./get_backward/)() | Specifies the number of categories (or units on a scatter chart) that the trend line extends before the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any nonnegative value. Read **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Returns the chart. Read-only [IChart](../ichart/). |
| virtual **bool** [get_DisplayEquation](./get_displayequation/)() | Specifies that the equation for the trendline is displayed on the chart (in the same label as the Rsquaredvalue). Read **bool**. |
| virtual **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() | Specifies that the R-squared value of the trendline is displayed on the chart (in the same label as the equation). Read **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Represents the format of the trend line. Read [IFormat](../iformat/). |
| virtual **double** [get_Forward](./get_forward/)() | Specifies the number of categories (or units on a scatter chart) that the trendline extends after the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any non-negative value. Read **double**. |
| virtual **double** [get_Intercept](./get_intercept/)() | Specifies the value where the trendline shall cross the y axis. This property shall be supported only when the trendline type is exp, linear, or poly. Read **double**. |
| virtual **uint8_t** [get_Order](./get_order/)() | Specifies the order of the polynomial trend line. It is ignored for other trend line types. Value must be between 2 and 6. Read **uint8_t**. |
| virtual **uint8_t** [get_Period](./get_period/)() | Specifies the period of the trend line for a moving average trend line. It is ignored for other trend line variants. Value must be between 2 and 255. Read **uint8_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Returns the presentation. Read-only [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | Represents legend entry related with this trendline Read-only [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Returns the base slide. Read-only [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Returns chart text format. Read-only [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Can contain a rich formatted text. If this property is not null then this formatted text value overrides auto-generated text. Auto-generated text is an implicit property of the data label, the display unit label of the value axis, the axis title, the chart title, the label of the trendline. Auto-generated text is formatted with the [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) property. Read-only [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() | Gets name of the trendline. Read [System::String](../../system/string/). |
| virtual [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() | Gets type of trend line. Read [TrendlineType](../trendlinetype/). |
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
| virtual void [set_Backward](./set_backward/)(**double**) | Specifies the number of categories (or units on a scatter chart) that the trend line extends before the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any nonnegative value. Write **double**. |
| virtual void [set_DisplayEquation](./set_displayequation/)(**bool**) | Specifies that the equation for the trendline is displayed on the chart (in the same label as the Rsquaredvalue). Write **bool**. |
| virtual void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) | Specifies that the R-squared value of the trendline is displayed on the chart (in the same label as the equation). Write **bool**. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | Represents the format of the trend line. Write [IFormat](../iformat/). |
| virtual void [set_Forward](./set_forward/)(**double**) | Specifies the number of categories (or units on a scatter chart) that the trendline extends after the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any non-negative value. Write **double**. |
| virtual void [set_Intercept](./set_intercept/)(**double**) | Specifies the value where the trendline shall cross the y axis. This property shall be supported only when the trendline type is exp, linear, or poly. Write **double**. |
| virtual void [set_Order](./set_order/)(**uint8_t**) | Specifies the order of the polynomial trend line. It is ignored for other trend line types. Value must be between 2 and 6. Write **uint8_t**. |
| virtual void [set_Period](./set_period/)(**uint8_t**) | Specifies the period of the trend line for a moving average trend line. It is ignored for other trend line variants. Value must be between 2 and 255. Write **uint8_t**. |
| virtual void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) | Sets name of the trendline. Write [System::String](../../system/string/). |
| virtual void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) | Sets type of trend line. Write [TrendlineType](../trendlinetype/). |
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

* Class [IOverridableText](../ioverridabletext/)
* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)