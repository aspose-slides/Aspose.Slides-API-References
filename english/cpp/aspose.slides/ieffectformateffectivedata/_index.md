---
title: IEffectFormatEffectiveData
second_title: Aspose.Slides for C++ API Reference
description: Imutable object which contains effective effect formatting properties.
type: docs
weight: 1925
url: /cpp/aspose.slides/ieffectformateffectivedata/
---
## IEffectFormatEffectiveData class


Imutable object which contains effective effect formatting properties.

```cpp
class IEffectFormatEffectiveData : public Aspose::Slides::IEffectParamSource
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
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlurEffectiveData](../../aspose.slides.effects/iblureffectivedata/)\> [get_BlurEffect](./get_blureffect/)() | Blur effect. Read-only [Effects::IBlurEffectiveData](../../aspose.slides.effects/iblureffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlayEffectiveData](../../aspose.slides.effects/ifilloverlayeffectivedata/)\> [get_FillOverlayEffect](./get_filloverlayeffect/)() | Fill overlay effect. Read-only [Effects::IFillOverlayEffectiveData](../../aspose.slides.effects/ifilloverlayeffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlowEffectiveData](../../aspose.slides.effects/igloweffectivedata/)\> [get_GlowEffect](./get_gloweffect/)() | Glow effect. Read-only [Effects::IGlowEffectiveData](../../aspose.slides.effects/igloweffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadowEffectiveData](../../aspose.slides.effects/iinnershadoweffectivedata/)\> [get_InnerShadowEffect](./get_innershadoweffect/)() | Inner shadow. Read-only [Effects::IInnerShadowEffectiveData](../../aspose.slides.effects/iinnershadoweffectivedata/). |
| virtual **bool** [get_IsNoEffects](./get_isnoeffects/)() | Returns true if all effects are disabled (as just created, default [EffectFormat](../effectformat/) object). Read-only **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadowEffectiveData](../../aspose.slides.effects/ioutershadoweffectivedata/)\> [get_OuterShadowEffect](./get_outershadoweffect/)() | Outer shadow. Read-only [Effects::IOuterShadowEffectiveData](../../aspose.slides.effects/ioutershadoweffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadowEffectiveData](../../aspose.slides.effects/ipresetshadoweffectivedata/)\> [get_PresetShadowEffect](./get_presetshadoweffect/)() | Preset shadow. Read-only [Effects::IPresetShadowEffectiveData](../../aspose.slides.effects/ipresetshadoweffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflectionEffectiveData](../../aspose.slides.effects/ireflectioneffectivedata/)\> [get_ReflectionEffect](./get_reflectioneffect/)() | Reflection. Read-only [Effects::IReflectionEffectiveData](../../aspose.slides.effects/ireflectioneffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdgeEffectiveData](../../aspose.slides.effects/isoftedgeeffectivedata/)\> [get_SoftEdgeEffect](./get_softedgeeffect/)() | Soft edge. Read-only [Effects::ISoftEdgeEffectiveData](../../aspose.slides.effects/isoftedgeeffectivedata/). |
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
## Remarks


This interface is used together with the [IEffectFormat](../ieffectformat/) interface to return effective formatting values with inheritance applied. 
## See Also

* Class [IEffectParamSource](../ieffectparamsource/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)
