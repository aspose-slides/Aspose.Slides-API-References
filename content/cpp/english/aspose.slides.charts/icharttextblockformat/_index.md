---
title: IChartTextBlockFormat
second_title: Aspose.Slides for C++ API Reference
description: Represents formatting properties for chart text elements.
type: docs
weight: 885
url: /aspose.slides.charts/icharttextblockformat/
---
## IChartTextBlockFormat class


Represents formatting properties for chart text elements.

```cpp
class IChartTextBlockFormat : public virtual System::Object
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
| virtual [TextAnchorType](../../aspose.slides/textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | Returns vertical anchor text in a [TextFrame](../../aspose.slides/textframe/). Read [TextAnchorType](../../aspose.slides/textanchortype/). |
| virtual [TextAutofitType](../../aspose.slides/textautofittype/) [get_AutofitType](./get_autofittype/)() | Returns text's autofit mode. Changing of this property can produce a certain influence only for these chart parts: [DataLabel](../datalabel/) and [DataLabelFormat](../datalabelformat/) (full suport in PowerPoint 2013; in PowerPoint 2007 there is no effect for rendering). Read [TextAutofitType](../../aspose.slides/textautofittype/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_CenterText](./get_centertext/)() | If [NullableBool::True](../../aspose.slides/nullablebool/) then text should be centered in box horizontally. Read [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Returns the bottom margin (points) in a [TextFrame](../../aspose.slides/textframe/). Changing of this property can produce a certain influence only for these chart parts: [DataLabel](../datalabel/) and [DataLabelFormat](../datalabelformat/) (full suport in PowerPoint 2013; in PowerPoint 2007 there is no effect for rendering). Read **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Returns the left margin (points) in a [TextFrame](../../aspose.slides/textframe/). Changing of this property can produce a certain influence only for these chart parts: [DataLabel](../datalabel/) and [DataLabelFormat](../datalabelformat/) (full suport in PowerPoint 2013; in PowerPoint 2007 there is no effect for rendering). Read **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Returns the right margin (points) in a [TextFrame](../../aspose.slides/textframe/). Changing of this property can produce a certain influence only for these chart parts: [DataLabel](../datalabel/) and [DataLabelFormat](../datalabelformat/) (full suport in PowerPoint 2013; in PowerPoint 2007 there is no effect for rendering). Read **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Returns the top margin (points) in a [TextFrame](../../aspose.slides/textframe/). Changing of this property can produce a certain influence only for these chart parts: [DataLabel](../datalabel/) and [DataLabelFormat](../datalabelformat/) (full suport in PowerPoint 2013; in PowerPoint 2007 there is no effect for rendering). Read **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | Specifies the custom rotation that is being applied to the text within the bounding box. If it not specified, the rotation of the accompanying shape is used. If it is specified, then this is applied independently from the shape. That is the shape can have a rotation applied in addition to the text itself having a rotation applied to it. The resulted value of visual text rotation summarized from this property and predefined vertical type in property TextVerticalType. Read **float**. |
| virtual [Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Determines text orientation. The resulted value of visual text rotation summarized from this property and custom angle in property RotationAngle. Read [Slides::TextVerticalType](../../aspose.slides/textverticaltype/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_WrapText](./get_wraptext/)() | **True** if text is wrapped at [TextFrame](../../aspose.slides/textframe/)'s margins. Changing of this property can produce a certain influence only for these chart parts: [DataLabel](../datalabel/) and [DataLabelFormat](../datalabelformat/) (full suport in PowerPoint 2007/2013). Read [NullableBool](../../aspose.slides/nullablebool/). |
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
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../../aspose.slides/textanchortype/)) | Sets vertical anchor text in a [TextFrame](../../aspose.slides/textframe/). Write [TextAnchorType](../../aspose.slides/textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../../aspose.slides/textautofittype/)) | Sets text's autofit mode. Changing of this property can produce a certain influence only for these chart parts: [DataLabel](../datalabel/) and [DataLabelFormat](../datalabelformat/) (full suport in PowerPoint 2013; in PowerPoint 2007 there is no effect for rendering). Write [TextAutofitType](../../aspose.slides/textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../../aspose.slides/nullablebool/)) | If [NullableBool::True](../../aspose.slides/nullablebool/) then text should be centered in box horizontally. Write [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Sets the bottom margin (points) in a [TextFrame](../../aspose.slides/textframe/). Changing of this property can produce a certain influence only for these chart parts: [DataLabel](../datalabel/) and [DataLabelFormat](../datalabelformat/) (full suport in PowerPoint 2013; in PowerPoint 2007 there is no effect for rendering). Write **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Sets the left margin (points) in a [TextFrame](../../aspose.slides/textframe/). Changing of this property can produce a certain influence only for these chart parts: [DataLabel](../datalabel/) and [DataLabelFormat](../datalabelformat/) (full suport in PowerPoint 2013; in PowerPoint 2007 there is no effect for rendering). Write **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Sets the right margin (points) in a [TextFrame](../../aspose.slides/textframe/). Changing of this property can produce a certain influence only for these chart parts: [DataLabel](../datalabel/) and [DataLabelFormat](../datalabelformat/) (full suport in PowerPoint 2013; in PowerPoint 2007 there is no effect for rendering). Write **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Sets the top margin (points) in a [TextFrame](../../aspose.slides/textframe/). Changing of this property can produce a certain influence only for these chart parts: [DataLabel](../datalabel/) and [DataLabelFormat](../datalabelformat/) (full suport in PowerPoint 2013; in PowerPoint 2007 there is no effect for rendering). Write **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | Specifies the custom rotation that is being applied to the text within the bounding box. If it not specified, the rotation of the accompanying shape is used. If it is specified, then this is applied independently from the shape. That is the shape can have a rotation applied in addition to the text itself having a rotation applied to it. The resulted value of visual text rotation summarized from this property and predefined vertical type in property TextVerticalType. Write **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/)) | Determines text orientation. The resulted value of visual text rotation summarized from this property and custom angle in property RotationAngle. Write [Slides::TextVerticalType](../../aspose.slides/textverticaltype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../../aspose.slides/nullablebool/)) | **True** if text is wrapped at [TextFrame](../../aspose.slides/textframe/)'s margins. Changing of this property can produce a certain influence only for these chart parts: [DataLabel](../datalabel/) and [DataLabelFormat](../datalabelformat/) (full suport in PowerPoint 2007/2013). Write [NullableBool](../../aspose.slides/nullablebool/). |
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

* Class [Object](../../system/object/)
* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)