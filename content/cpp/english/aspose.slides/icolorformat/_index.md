---
title: IColorFormat
second_title: Aspose.Slides for C++ API Reference
description: Represents a color used in a presentation.
type: docs
weight: 1600
url: /aspose.slides/icolorformat/
---
## IColorFormat class


Represents a color used in a presentation.

```cpp
class IColorFormat : public Aspose::Slides::IFillParamSource
```

## Methods

| Method | Description |
| --- | --- |
| virtual void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](./)\>) | Copy color format from \"color\". |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| virtual **uint8_t** [get_B](./get_b/)() | Returns the blue component of a color. All color transformations are ignored. Read **uint8_t**. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() | Returns resulting color (with all color transformations applied). Sets RGB colors and clears all color transformations. Read [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) | Returns color transformation operation applied to color at the specified index. Read/write [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() | Returns the collection of color transformations applied to a color. Read-only [IColorOperationCollection](../icoloroperationcollection/). |
| virtual [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() | Returns the color definition method. Read [Slides::ColorType](../colortype/). |
| virtual **float** [get_FloatB](./get_floatb/)() | Returns the blue component of a color. All color transformations are ignored. Read **float**. |
| virtual **float** [get_FloatG](./get_floatg/)() | Returns the green component of a color. All color transformations are ignored. Read **float**. |
| virtual **float** [get_FloatR](./get_floatr/)() | Returns the red component of a color. All color transformations are ignored. Read **float**. |
| virtual **uint8_t** [get_G](./get_g/)() | Returns the green component of a color. All color transformations are ignored. Read **uint8_t**. |
| virtual **float** [get_Hue](./get_hue/)() | Returns the hue component of a color in HSL representation. All color transformations are ignored. Read **float**. |
| virtual **float** [get_Luminance](./get_luminance/)() | Returns the luminance component of a color in HSL representation. All color transformations are ignored. Read **float**. |
| virtual [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() | Returns the color preset. Read [Slides::PresetColor](../presetcolor/). |
| virtual **uint8_t** [get_R](./get_r/)() | Returns the red component of a color. All color transformations are ignored. Read **uint8_t**. |
| virtual **float** [get_Saturation](./get_saturation/)() | Returns the saturation component of a color in HSL representation. All color transformations are ignored. Read **float**. |
| virtual [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() | Returns the color identified by a color scheme. Read [Slides::SchemeColor](../schemecolor/). |
| virtual [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() | Returns the color identified by the system color table. Read [Slides::SystemColor](../systemcolor/). |
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
| virtual void [set_B](./set_b/)(**uint8_t**) | Sets the blue component of a color. All color transformations are ignored. Write **uint8_t**. |
| virtual void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) | Returns resulting color (with all color transformations applied). Sets RGB colors and clears all color transformations. Write [System::Drawing::Color](../../system.drawing/color/). |
| virtual void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) | Set color transformation operation applied to color at the specified index. Read/write [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) | Sets the color definition method. Write [Slides::ColorType](../colortype/). |
| virtual void [set_FloatB](./set_floatb/)(**float**) | Sets the blue component of a color. All color transformations are ignored. Write **float**. |
| virtual void [set_FloatG](./set_floatg/)(**float**) | Sets the green component of a color. All color transformations are ignored. Write **float**. |
| virtual void [set_FloatR](./set_floatr/)(**float**) | Sets the red component of a color. All color transformations are ignored. Write **float**. |
| virtual void [set_G](./set_g/)(**uint8_t**) | Sets the green component of a color. All color transformations are ignored. Write **uint8_t**. |
| virtual void [set_Hue](./set_hue/)(**float**) | Sets the hue component of a color in HSL representation. All color transformations are ignored. Write **float**. |
| virtual void [set_Luminance](./set_luminance/)(**float**) | Sets the luminance component of a color in HSL representation. All color transformations are ignored. Write **float**. |
| virtual void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) | Sets the color preset. Write [Slides::PresetColor](../presetcolor/). |
| virtual void [set_R](./set_r/)(**uint8_t**) | Sets the red component of a color. All color transformations are ignored. Write **uint8_t**. |
| virtual void [set_Saturation](./set_saturation/)(**float**) | Sets the saturation component of a color in HSL representation. All color transformations are ignored. Write **float**. |
| virtual void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) | Sets the color identified by a color scheme. Write [Slides::SchemeColor](../schemecolor/). |
| virtual void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) | Sets the color identified by the system color table. Write [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) | Returns a [System::String](../../system/string/) that represents the current color format. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [IFillParamSource](../ifillparamsource/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)