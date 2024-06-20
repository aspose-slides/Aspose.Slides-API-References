---
title: TextFrameFormat
second_title: Aspose.Slides for C++ API Reference
description: Contains the TextFrame's formatTextFrameFormatting properties.
type: docs
weight: 5253
url: /aspose.slides/textframeformat/
---
## TextFrameFormat class


Contains the [TextFrame](../textframe/)'s formatTextFrameFormatting properties.

```cpp
class TextFrameFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::ITextFrameFormat,
                        public Aspose::Slides::Charts::IChartTextBlockFormat
```

## Methods

| Method | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Compares with specified object. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() override | Returns vertical anchor text in a TextFrameEx. Read [TextAnchorType](../textanchortype/). |
| [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() override | Returns text's autofit mode. Read [TextAutofitType](../textautofittype/). |
| [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() override | If [NullableBool::True](../nullablebool/) then text should be centered in box horizontally. Read [NullableBool](../nullablebool/). |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | Returns number of columns in the text area. This value must be a positive number. Otherwise, the value will be set to zero. Value 0 means undefined value. Read **int32_t**. |
| **double** [get_ColumnSpacing](./get_columnspacing/)() override | Returns the space between text columns in the text area (in points). This should only apply when there is more than 1 column present. This value must be a positive number. Otherwise, the value will be set to zero. Read **double**. |
| **bool** [get_KeepTextFlat](./get_keeptextflat/)() override | Gets keeping text flat even if a 3-D Rotation effect was applied. Read **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | Returns the bottom margin (points) in a [TextFrame](../textframe/). Read **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | Returns the left margin (points) in a [TextFrame](../textframe/). Read **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | Returns the right margin (points) in a [TextFrame](../textframe/). Read **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | Returns the top margin (points) in a [TextFrame](../textframe/). Read **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Returns Parent_Immediate object. Read-only [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Returns parent [IPresentationComponent](../ipresentationcomponent/). Read-only [IPresentationComponent](../ipresentationcomponent/). |
| **float** [get_RotationAngle](./get_rotationangle/)() override | Specifies custom the rotation that is being applied to the text within the bounding box. If it not specified, the rotation of the accompanying shape is used. If it is specified, then this is applied independently from the shape. That is the shape can have a rotation applied in addition to the text itself having a rotation applied to it. The resulted value of visual text rotation summarized from this property and predefined vertical type in property TextVerticalType. Read **float**. |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Determines text orientation. The resulted value of visual text rotation summarized from this property and custom angle in property RotationAngle. Read [Slides::TextVerticalType](../textverticaltype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | Returns the [ThreeDFormat](../threedformat/) object that represents 3d effect properties for a text. Read-only [IThreeDFormat](../ithreedformat/). |
| [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() override | Gets text wrapping shape. Read [TextShapeType](../textshapetype/). |
| [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() override | **True** if text is wrapped at [TextFrame](../textframe/)'s margins. Read [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() override | Gets effective text frame formatting data with the inheritance applied. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Returns hash code. |
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
| void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) override | Sets vertical anchor text in a TextFrameEx. Write [TextAnchorType](../textanchortype/). |
| void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) override | Sets text's autofit mode. Write [TextAutofitType](../textautofittype/). |
| void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) override | If [NullableBool::True](../nullablebool/) then text should be centered in box horizontally. Write [NullableBool](../nullablebool/). |
| void [set_ColumnCount](./set_columncount/)(**int32_t**) override | Sets number of columns in the text area. This value must be a positive number. Otherwise, the value will be set to zero. Value 0 means undefined value. Write **int32_t**. |
| void [set_ColumnSpacing](./set_columnspacing/)(**double**) override | Sets the space between text columns in the text area (in points). This should only apply when there is more than 1 column present. This value must be a positive number. Otherwise, the value will be set to zero. Write **double**. |
| void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) override | Sets keeping text flat even if a 3-D Rotation effect was applied. Write **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | Sets the bottom margin (points) in a [TextFrame](../textframe/). Write **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | Sets the left margin (points) in a [TextFrame](../textframe/). Write **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | Sets the right margin (points) in a [TextFrame](../textframe/). Write **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | Sets the top margin (points) in a [TextFrame](../textframe/). Write **double**. |
| void [set_RotationAngle](./set_rotationangle/)(**float**) override | Specifies custom the rotation that is being applied to the text within the bounding box. If it not specified, the rotation of the accompanying shape is used. If it is specified, then this is applied independently from the shape. That is the shape can have a rotation applied in addition to the text itself having a rotation applied to it. The resulted value of visual text rotation summarized from this property and predefined vertical type in property TextVerticalType. Write **float**. |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Determines text orientation. The resulted value of visual text rotation summarized from this property and custom angle in property RotationAngle. Write [Slides::TextVerticalType](../textverticaltype/). |
| void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) override | Sets text wrapping shape. Write [TextShapeType](../textshapetype/). |
| void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) override | **True** if text is wrapped at [TextFrame](../textframe/)'s margins. Write [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
|  [TextFrameFormat](./textframeformat/)() | Initializes a new instance of [TextFrameFormat](./) class. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [PVIObject](../pviobject/)
* Class [ITextFrameFormat](../itextframeformat/)
* Class [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)