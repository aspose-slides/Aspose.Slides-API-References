---
title: StringComparer
second_title: Aspose.Slides for C++ API Reference
description: "Compares strings using different comparison modes. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 1223
url: /system/stringcomparer/
---
## StringComparer class


Compares strings using different comparison modes. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StringComparer : public virtual System::Object,
                       public System::Collections::Generic::IComparer<String>,
                       public System::Collections::Generic::IEqualityComparer<String>
```

## Methods

| Method | Description |
| --- | --- |
| int [Compare](./compare/)([args_type](./args_type/), [args_type](./args_type/)) const override | Compares two strings using current settings. |
| static [StringComparerPtr](../stringcomparerptr/) [Create](./create/)(const [System::SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **bool**) | Creates culture-specific comparer. |
| **bool** [Equals](./equals/)([String](../string/), [String](../string/)) const override | Checks if two strings are equal using current settings. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Compares objects using C# [Object.Equals](../object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| static [StringComparerPtr](../stringcomparerptr/) [get_CurrentCulture](./get_currentculture/)() | Current culture comparer singleton. |
| static [StringComparerPtr](../stringcomparerptr/) [get_CurrentCultureIgnoreCase](./get_currentcultureignorecase/)() | Current culture case-ignoring comparer singleton. |
| static [StringComparerPtr](../stringcomparerptr/) [get_InvariantCulture](./get_invariantculture/)() | Invariant culture comparer singleton. |
| static [StringComparerPtr](../stringcomparerptr/) [get_InvariantCultureIgnoreCase](./get_invariantcultureignorecase/)() | Invariant culture case-ignoring comparer singleton. |
| static [StringComparerPtr](../stringcomparerptr/) [get_Ordinal](./get_ordinal/)() | Ordinal comparer singleton. |
| static [StringComparerPtr](../stringcomparerptr/) [get_OrdinalIgnoreCase](./get_ordinalignorecase/)() | Ordinal case-ignoring comparer singleton. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Gets reference counter data structure associated with the object. |
| int [GetHashCode](./gethashcode/)([String](../string/)) const override | Gets string's hash code. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../object/gettype/) call. |
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
|  [RTTI_INFO_TEMPLATE_CLASS](../../system.collections.generic/iequalitycomparer/rtti_info_template_class/)([System::Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<T\>, System::BaseTypesInfo\<[System::Object](../object/)\>) | RTTI information. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analog of C# [Object.ToString()](../object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implements C# typeof([System.Object](../object/)) construct. |
| void [Unlock](../object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../object/~object/)() | Destroys object. Frees all internal data structures. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [args_type](./args_type/) | Argument type. |
## See Also

* Class [Object](../object/)
* Class [IComparer](../../system.collections.generic/icomparer/)
* Class [IEqualityComparer](../../system.collections.generic/iequalitycomparer/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)