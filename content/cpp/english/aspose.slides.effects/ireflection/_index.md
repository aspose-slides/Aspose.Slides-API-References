---
title: IReflection
second_title: Aspose.Slides for C++ API Reference
description: Represents a reflection effect.
type: docs
weight: 898
url: /aspose.slides.effects/ireflection/
---
## IReflection class


Represents a reflection effect.

```cpp
class IReflection : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                    public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IReflectionEffectiveData>>
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
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) radius. Read **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Direction of reflection. Read **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Distance of reflection. Read **double**. |
| virtual **float** [get_EndPosAlpha](./get_endposalpha/)() | Specifies the end position (along the alpha gradient ramp) of the end alpha value (percents). Read **float**. |
| virtual **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() | End reflection opacity. (percents). Read **float**. |
| virtual **float** [get_FadeDirection](./get_fadedirection/)() | Specifies the direction to offset the reflection. (angle). Read **float**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Rectangle alignment. Read [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Specifies whether the reflection should rotate with the shape if the shape is rotated. Read **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Specifies the horizontal scaling factor, negative scaling causes a flip. (percents) Read **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Specifies the vertical scaling factor, negative scaling causes a flip. (percents) Read **double**. |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Specifies the horizontal skew angle. Read **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Specifies the vertical skew angle. Read **double**. |
| virtual **float** [get_StartPosAlpha](./get_startposalpha/)() | Specifies the start position (along the alpha gradient ramp) of the start alpha value (percents). Read **float**. |
| virtual **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() | Starting reflection opacity. (percents). Read **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | Gets effective data with the inheritance applied. |
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
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) radius. Write **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | Direction of reflection. Write **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | Distance of reflection. Write **double**. |
| virtual void [set_EndPosAlpha](./set_endposalpha/)(**float**) | Specifies the end position (along the alpha gradient ramp) of the end alpha value (percents). Write **float**. |
| virtual void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) | End reflection opacity. (percents). Write **float**. |
| virtual void [set_FadeDirection](./set_fadedirection/)(**float**) | Specifies the direction to offset the reflection. (angle). Write **float**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | Rectangle alignment. Write [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | Specifies whether the reflection should rotate with the shape if the shape is rotated. Write **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | Specifies the horizontal scaling factor, negative scaling causes a flip. (percents) Write **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | Specifies the vertical scaling factor, negative scaling causes a flip. (percents) Write **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | Specifies the horizontal skew angle. Write **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | Specifies the vertical skew angle. Write **double**. |
| virtual void [set_StartPosAlpha](./set_startposalpha/)(**float**) | Specifies the start position (along the alpha gradient ramp) of the start alpha value (percents). Write **float**. |
| virtual void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) | Starting reflection opacity. (percents). Write **float**. |
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

* Class [IImageTransformOperation](../iimagetransformoperation/)
* Class [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* Namespace [Aspose::Slides::Effects](../)
* Library [Aspose.Slides](../../)