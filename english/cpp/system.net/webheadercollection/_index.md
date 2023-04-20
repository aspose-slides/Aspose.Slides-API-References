---
title: WebHeaderCollection
second_title: Aspose.Slides for C++ API Reference
description: "Represents the collection of the protocol headers. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 482
url: /cpp/system.net/webheadercollection/
---
## WebHeaderCollection class


Represents the collection of the protocol headers. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class WebHeaderCollection : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| void [Add](./add/)([String](../../system/string/), [String](../../system/string/)) | Adds the specified pair of the header name and the header value to the collection. |
| void [Add](./add/)([HttpResponseHeader](../httpresponseheader/), [String](../../system/string/)) | Adds the specified pair of the header and the header value to the collection. |
| void [Add](./add/)([HttpRequestHeader](../httprequestheader/), [String](../../system/string/)) | Adds the specified pair of the header and the header value to the collection. |
| [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [AllKeys](./allkeys/)() | Returns a collection of header names that are stored in the collection. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| **int32_t** [get_Count](./get_count/)() const | Returns a number of elements in the collection. |
| [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_Keys](./get_keys/)() | Returns a collection of header names that are stored in the collection. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| [String](../../system/string/) [GetKey](./getkey/)(int) | Returns a key at the specified index. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [GetValues](./getvalues/)([String](../../system/string/)) | Returns the collection of the header values. |
| [String](../../system/string/) [idx_get](./idx_get/)([HttpRequestHeader](../httprequestheader/)) | Gets the header value using the specified request's header. |
| [String](../../system/string/) [idx_get](./idx_get/)([HttpResponseHeader](../httpresponseheader/)) | Gets the header value using the specified response's header. |
| [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/)) | Gets the header value using the specified header name. |
| void [idx_set](./idx_set/)([HttpRequestHeader](../httprequestheader/), [String](../../system/string/)) | Sets the header value of the specified header. |
| void [idx_set](./idx_set/)([HttpResponseHeader](../httpresponseheader/), [String](../../system/string/)) | Sets the header value using the specified response's header. |
| void [idx_set](./idx_set/)([String](../../system/string/), [String](../../system/string/)) | Sets the header value using the specified header name. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| static **bool** [IsRestricted](./isrestricted/)(const [String](../../system/string/)\&) | Not implemented. |
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
| void [Remove](./remove/)([String](../../system/string/)) | Removes the header by the specified header name. |
| void [Remove](./remove/)([HttpResponseHeader](../httpresponseheader/)) | Removes the specified response's header. |
| void [Remove](./remove/)([HttpRequestHeader](../httprequestheader/)) | Removes the specified request's header. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [Set](./set/)([String](../../system/string/), [String](../../system/string/)) | Sets the value of the specified header. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
|  [WebHeaderCollection](./webheadercollection/)() | Constructs a new instance. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.Slides](../../)