---
title: Object
second_title: Aspose.Slides for C++ API Reference
description: Base class that enables using methods available for System.Object class in C#. All non-trivial classes used with translated environment should inherit it.
type: docs
weight: 1080
url: /system/object/
---
## Object class


Base class that enables using methods available for [System.Object](./) class in C#. All non-trivial classes used with translated environment should inherit it.

```cpp
class Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](./equals/)([ptr](./ptr/)) | Compares objects using C# [Object.Equals](./equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](./equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](./equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| Detail::SmartPtrCounter * [GetCounter](./getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](./gethashcode/)() const | Analog of C# [Object.GetHashCode()](./gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](./gettype/) call. |
| virtual **bool** [Is](./is/)(const [TypeInfo](../typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Lock](./lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../lockcontext/) sentry object. |
| virtual [ptr](./ptr/) [MemberwiseClone](./memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](./memberwiseclone/) method. Enables cloning custom types. |
|  [Object](./object/)() | Creates object. Initializes all internal data structures. |
|  [Object](./object/)([Object](./) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](./)\& [operator=](./operator_equal/)([Object](./) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](./referenceequals/)([ptr](./ptr/) const\&, [ptr](./ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](./referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialization of [Object::ReferenceEquals](./referenceequals/) for case of strings. |
| int [RemovedSharedRefs](./removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| virtual void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](./sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](./) * [SharedRefAdded](./sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../string/) [ToString](./tostring/)() const | Analog of C# [Object.ToString()](./tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Implements C# typeof([System.Object](./)) construct. |
| void [Unlock](./unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](./weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](./weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](./~object/)() | Destroys object. Frees all internal data structures. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ptr](./ptr/) | Alias for smart pointer type. |
## Remarks


Alongside with methods available in C# [System.Object](./) class, it also enables support for some concepts specific for translated code environment. This includes reference counting used by smart pointer classes ([System::SmartPtr](../smartptr/), [System::WeakPtr](../weakptr/), [System::DynamicWeakPtr](../dynamicweakptr/)) and other services related to memory management, debug, etc.

Each [Object](./) has two reference counters: shared reference counter and weak reference counter. Weak reference counter is always stored in detached data structure rather than in [Object](./) itself which allows weak pointers overlive referenced object. Smart reference counter is stored either in object itself or in same detached structure, depending on ENABLE_EXTERNAL_REFCOUNT macro state. By default, it is enabled in debug builds and disabled in release builds. If smart pointer counter is stored in object itself, detached data structure is created only if weak pointers to object exist. Otherwise, it is created alongside with object itself.

All smart pointers use these two reference counters and contribute to same and only ownership group.

If [Object](./) subclass is created on stack, no smart pointers to it may be created, otherwise there is a stack deletion issue.

This type can be allocated either in stack as value type or in heap using [System::MakeObject()](../makeobject/) function. Once the object is allocated, never mix up these two usecases: having [SmartPtr](../smartptr/) pointers onto stack-allocated objects is strictly prohibited. 
## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)