---
title: DefaultBoxedValue
second_title: Aspose.Slides for C++ API Reference
description: "BoxedValue class implementation. Allows it BoxingValue specializations to be declared without duplicating common code. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 248
url: /system/defaultboxedvalue/
---
## DefaultBoxedValue class


[BoxedValue](../boxedvalue/) class implementation. Allows it BoxingValue specializations to be declared without duplicating common code. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<class T>class DefaultBoxedValue : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
|  [DefaultBoxedValue](./defaultboxedvalue/)(const T\&) | Constructs a new instance of [DefaultBoxedValue](./) class that represents the specified value. |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | Determines the equality of the boxed values represented by the current and specified objects. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Gets reference counter data structure associated with the object. |
| int [GetHashCode](./gethashcode/)() const override | Returns a hash code for the current object. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Gets actual type of object. |
| **bool** [is](./is/)() const | Determines if the type of the boxed value represented by the current object is **V**. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Lock](../object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../lockcontext/) sentry object. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../object/object/)([Object](../object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialization of [Object::ReferenceEquals](../object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Returns the string representation of the boxed value. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implements C# typeof([System.Object](../object/)) construct. |
| const T\& [unbox](./unbox/)() const | Unboxes the boxed value. |
| void [Unlock](../object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)