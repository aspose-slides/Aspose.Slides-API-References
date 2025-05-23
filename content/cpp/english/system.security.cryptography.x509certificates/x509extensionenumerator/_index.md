---
title: X509ExtensionEnumerator
second_title: Aspose.Slides for C++ API Reference
description: "Enumerator to iterate through extension collection. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 183
url: /system.security.cryptography.x509certificates/x509extensionenumerator/
---
## X509ExtensionEnumerator class


Enumerator to iterate through extension collection. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class X509ExtensionEnumerator : public System::Collections::Generic::SimpleEnumerator<X509ExtensionCollection::vector_t>
```

## Methods

| Method | Description |
| --- | --- |
|  [ASPOSECPP_SHARED_RTTI_INFO_DECL](./asposecpp_shared_rtti_info_decl/)() | RTTI information. |
| [IEnumerator](../../system.collections.generic/ienumerator/) * [AsVirtualizedIterator](../../system.collections.generic/ienumerator/asvirtualizediterator/)() | Prepares the iterator to be used by the VirtualizedIterator class. |
|  [BaseEnumerator](../../system.collections.generic/baseenumerator/baseenumerator/)(const [Object::ptr](../../system/object/ptr/)\&, Container\&) | Initializes iterator. |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](../../system.collections.generic/simpleenumerator/cloneiterator/)() const override | Clones current iterator. |
| virtual [MakeConstRef_t](../../system/makeconstref_t/)\<T\> [Current](../../system.collections.generic/ienumerator/current/)() const | Gets current element. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | Does nothing. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| [MakeConstRef_t](../../system/makeconstref_t/)\<Element\> [get_Current](../../system.collections.generic/simpleenumerator/get_current/)() const override | Gets 'current' element. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
|  [IEnumerator](../../system.collections.generic/ienumerator/ienumerator/)() |  |
| void [IncrementIterator](../../system.collections.generic/ienumerator/incrementiterator/)() override | Moves the iterator step forward. |
| void [InitializeIterator](../../system.collections.generic/ienumerator/initializeiterator/)() override | Does the first [MoveNext()](../../system.collections.generic/ienumerator/movenext/) call and prepares the enumerator object to be used by VirtualizedIterator. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| **bool** [IsValid](../../system.collections.generic/baseenumerator/isvalid/)() const | Checks whether [MoveNext()](../../system.collections.generic/baseenumerator/movenext/) was called and end was not reached. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| void [MarkOwnedByVirtualizedIterator](../../system.collections.generic/ienumerator/markownedbyvirtualizediterator/)() | Marks the enumerator owned by virtualized iterator. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
| **bool** [MoveNext](../../system.collections.generic/baseenumerator/movenext/)() override | Enumerator-style increment. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [Reset](../../system.collections.generic/baseenumerator/reset/)() override | Resets enumerator to allow re-enumerating elements. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
|  [SimpleEnumerator](../../system.collections.generic/simpleenumerator/simpleenumerator/)([Object::ptr](../../system/object/ptr/), Container\&) | Creates simple iterator. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
|  [X509ExtensionEnumerator](./x509extensionenumerator/)(const [SharedPtr](../../system/sharedptr/)\<[X509ExtensionCollection](../x509extensioncollection/)\>\&) | Creates enumerator. |
| virtual  [~IEnumerator](../../system.collections.generic/ienumerator/~ienumerator/)() |  |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ThisType](./thistype/) | This type. |
| [BaseType](./basetype/) | Parent type. |
## See Also

* Class [SimpleEnumerator](../../system.collections.generic/simpleenumerator/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.Slides](../../)