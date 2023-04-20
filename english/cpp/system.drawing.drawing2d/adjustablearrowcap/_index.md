---
title: AdjustableArrowCap
second_title: Aspose.Slides for C++ API Reference
description: "Represents an adjustable arrow-shaped line cap. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 1
url: /cpp/system.drawing.drawing2d/adjustablearrowcap/
---
## AdjustableArrowCap class


Represents an adjustable arrow-shaped line cap. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class AdjustableArrowCap : public System::Drawing::Drawing2D::CustomLineCap
```

## Methods

| Method | Description |
| --- | --- |
|  [AdjustableArrowCap](./adjustablearrowcap/)(**float**, **float**, **bool**) | Constructs a new instance of [AdjustableArrowCap](./) with the specified width and height. |
| virtual [SharedPtr](../../system/sharedptr/)\<[CustomLineCap](../customlinecap/)\> [Clone](../customlinecap/clone/)() | Returns a copy of the current object. |
|  [CustomLineCap](../customlinecap/customlinecap/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](../graphicspath/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](../graphicspath/)\>\&, [LineCap](../linecap/), **float**) | Constructs a new instance of [CustomLineCap](../customlinecap/) class that represents a user-defined line cap with the specified properties. |
| void [Dispose](../customlinecap/dispose/)() | Releases all operating system resources acquired by the current object. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| [LineCap](../linecap/) [get_BaseCap](../customlinecap/get_basecap/)() const | Returns the base line cap from which this custom cap is created. |
| **float** [get_BaseInset](../customlinecap/get_baseinset/)() const | Returns the distance between the line and the cap. |
| **bool** [get_Filled](./get_filled/)() const | Returns a value that indicates if the arrow represented by the current object is filled. |
| **float** [get_Height](./get_height/)() const | Returns the height of the arrow represented by the current object. |
| **float** [get_MiddleInset](./get_middleinset/)() const | Sets the distance between the line and the cap represented by the current object. |
| [LineJoin](../linejoin/) [get_StrokeJoin](../customlinecap/get_strokejoin/)() const | Returns the LineJoin value which determines how lines of this custom cap are joined. |
| **float** [get_Width](./get_width/)() const | Returns the width of the arrow represented by the current object. |
| **float** [get_WidthScale](../customlinecap/get_widthscale/)() const | Returns the scale of this custom cap. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| void [GetStrokeCaps](../customlinecap/getstrokecaps/)([LineCap](../linecap/)\&, [LineCap](../linecap/)\&) | Gets the start and end line caps of the custom cap represented by the current object. |
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
| void [set_BaseCap](../customlinecap/set_basecap/)([LineCap](../linecap/)) | Sets the base line cap value for this custom cap. |
| void [set_BaseInset](../customlinecap/set_baseinset/)(**float**) | Sets the distance between the line and the cap. |
| void [set_Filled](./set_filled/)(**bool**) | Sets a value that specifies if the arrow represented by the current object is filled. |
| void [set_Height](./set_height/)(**float**) | Sets the height of the arrow represented by the current object. |
| void [set_MiddleInset](./set_middleinset/)(**float**) | Sets the distance between the line and the cap represented by the current object. |
| void [set_StrokeJoin](../customlinecap/set_strokejoin/)([LineJoin](../linejoin/)) | Sets the LineJoin value which determines how lines of this custom cap are joined. |
| void [set_Width](./set_width/)(**float**) | Sets the width of the arrow represented by the current object. |
| void [set_WidthScale](../customlinecap/set_widthscale/)(**float**) | Sets the scale value of this custom cap. |
| void [SetStrokeCaps](../customlinecap/setstrokecaps/)([LineCap](../linecap/), [LineCap](../linecap/)) | Sets the start and end line caps of the custom cap represented by the current object. |
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

* Class [CustomLineCap](../customlinecap/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.Slides](../../)