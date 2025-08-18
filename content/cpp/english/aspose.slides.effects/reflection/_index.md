---
title: Reflection
second_title: Aspose.Slides for C++ API Reference
description: Represents a Reflection effect.
type: docs
weight: 1067
url: /aspose.slides.effects/reflection/
---
## Reflection class


Represents a [Reflection](./) effect.

```cpp
class Reflection : public Aspose::Slides::Effects::IReflection,
                   public Aspose::Slides::Effects::IVisualEffect,
                   public Aspose::Slides::IPVIObject
```

## Methods

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Determines whether the specified [Reflection](./) is equal to the current [Reflection](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) radius. Read **double**. |
| **float** [get_Direction](./get_direction/)() override | Direction of reflection. Read **float**. |
| **double** [get_Distance](./get_distance/)() override | Distance of reflection. Read **double**. |
| **float** [get_EndPosAlpha](./get_endposalpha/)() override | Specifies the end position (along the alpha gradient ramp) of the end alpha value (percents). Read **float**. |
| **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() override | End reflection opacity. (percents). Read **float**. |
| **float** [get_FadeDirection](./get_fadedirection/)() override | Specifies the direction to offset the reflection. (angle). Read **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Returns parent [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). Read-only [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Rectangle alignment. Read [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Specifies whether the reflection should rotate with the shape if the shape is rotated. Read **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Specifies the horizontal scaling factor, negative scaling causes a flip. (percents) Read **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Specifies the vertical scaling factor, negative scaling causes a flip. (percents) Read **double**. |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Specifies the horizontal skew angle. Read **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Specifies the vertical skew angle. Read **double**. |
| **float** [get_StartPosAlpha](./get_startposalpha/)() override | Specifies the start position (along the alpha gradient ramp) of the start alpha value (percents). Read **float**. |
| **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() override | Starting reflection opacity. (percents). Read **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Version. Read-only **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| [System::SharedPtr](../../system/sharedptr/)\<[IReflectionEffectiveData](../ireflectioneffectivedata/)\> [GetEffective](./geteffective/)() override | Gets effective [Reflection](./) effect data with the inheritance applied. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Serves as a hash function for a particular type. |
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
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) radius. Write **double**. |
| void [set_Direction](./set_direction/)(**float**) override | Direction of reflection. Write **float**. |
| void [set_Distance](./set_distance/)(**double**) override | Distance of reflection. Write **double**. |
| void [set_EndPosAlpha](./set_endposalpha/)(**float**) override | Specifies the end position (along the alpha gradient ramp) of the end alpha value (percents). Write **float**. |
| void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) override | End reflection opacity. (percents). Write **float**. |
| void [set_FadeDirection](./set_fadedirection/)(**float**) override | Specifies the direction to offset the reflection. (angle). Write **float**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Rectangle alignment. Write [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Specifies whether the reflection should rotate with the shape if the shape is rotated. Write **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Specifies the horizontal scaling factor, negative scaling causes a flip. (percents) Write **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Specifies the vertical scaling factor, negative scaling causes a flip. (percents) Write **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Specifies the horizontal skew angle. Write **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Specifies the vertical skew angle. Write **double**. |
| void [set_StartPosAlpha](./set_startposalpha/)(**float**) override | Specifies the start position (along the alpha gradient ramp) of the start alpha value (percents). Write **float**. |
| void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) override | Starting reflection opacity. (percents). Write **float**. |
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

* Class [IReflection](../ireflection/)
* Class [IVisualEffect](../ivisualeffect/)
* Class [IPVIObject](../../aspose.slides/ipviobject/)
* Namespace [Aspose::Slides::Effects](../)
* Library [Aspose.Slides](../../)