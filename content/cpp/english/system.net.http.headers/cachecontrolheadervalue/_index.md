---
title: CacheControlHeaderValue
second_title: Aspose.Slides for C++ API Reference
description: "Represents a value of the 'Cache-Control' header. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 14
url: /system.net.http.headers/cachecontrolheadervalue/
---
## CacheControlHeaderValue class


Represents a value of the 'Cache-Control' header. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class CacheControlHeaderValue : public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
|  [CacheControlHeaderValue](./cachecontrolheadervalue/)() | Constructs a new instance. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Extensions](./get_extensions/)() | Returns the collection of the cache-extension tokens. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxAge](./get_maxage/)() | Gets the maximum age value in seconds that determines a time during which the client will accept a response. |
| **bool** [get_MaxStale](./get_maxstale/)() | Gets the value that determines if the client will accept the expired responses. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxStaleLimit](./get_maxstalelimit/)() | Gets the value in seconds that determines the time during which the client will accept the expired responses. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MinFresh](./get_minfresh/)() | Gets the value that determines the freshness lifetime. |
| **bool** [get_MustRevalidate](./get_mustrevalidate/)() | Gets the value that determines if the server requires revalidation of a cache entry when the it becomes stale. |
| **bool** [get_NoCache](./get_nocache/)() | Gets the value that determines if the client will accept a cached response. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_NoCacheHeaders](./get_nocacheheaders/)() | Gets the collection of fieldnames in the 'no-cache' directive in the 'Cache-Control' header. |
| **bool** [get_NoStore](./get_nostore/)() | Gets the value that determines if a cache must not store any part of an HTTP request or response. |
| **bool** [get_NoTransform](./get_notransform/)() | Gets the value that determines if a cache or proxy must not change any part of the entity body. |
| **bool** [get_OnlyIfCached](./get_onlyifcached/)() | Gets the value that determines if the client must use only cached entries. |
| **bool** [get_Private](./get_private/)() | Gets the value that determines if the HTTP response message or its part is intended for a single user and must not be cached by a shared cache. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_PrivateHeaders](./get_privateheaders/)() | Gets the collection of fieldnames in the 'private' directive in the 'Cache-Control' header. |
| **bool** [get_ProxyRevalidate](./get_proxyrevalidate/)() | Gets the value that determines if the server requires revalidation of a cache entry when it becomes stale for the shared user agent caches. |
| **bool** [get_Public](./get_public/)() | Gets the value that determines if an HTTP response can be cached by any cache. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_SharedMaxAge](./get_sharedmaxage/)() | Gets the shared maximum age value in seconds that overrides the 'max-age' directive in the 'Cache-Control'. header or the 'Expires' header for a shared cache. |
| static **int32_t** [GetCacheControlLength](./getcachecontrollength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Converts a passed string from the specified index to an instance of the [CacheControlHeaderValue](./) class. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Converts a passed string to an instance of the [CacheControlHeaderValue](./) class. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [set_MaxAge](./set_maxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Sets the maximum age value in seconds that determines a time during which the client will accept a response. |
| void [set_MaxStale](./set_maxstale/)(**bool**) | Sets the value that determines if the client will accept the expired responses. |
| void [set_MaxStaleLimit](./set_maxstalelimit/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Sets the value in seconds that determines the time during which the client will accept the expired responses. |
| void [set_MinFresh](./set_minfresh/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Sets the value that determines the freshness lifetime. |
| void [set_MustRevalidate](./set_mustrevalidate/)(**bool**) | Sets the value that determines if the server requires revalidation of a cache entry when the it becomes stale. |
| void [set_NoCache](./set_nocache/)(**bool**) | Sets the value that determines if the client will accept a cached response. |
| void [set_NoStore](./set_nostore/)(**bool**) | Sets the value that determines if a cache must not store any part of an HTTP request or response. |
| void [set_NoTransform](./set_notransform/)(**bool**) | Sets the value that determines if a cache or proxy must not change any part of the entity body. |
| void [set_OnlyIfCached](./set_onlyifcached/)(**bool**) | Sets the value that determines if the client must use only cached entries. |
| void [set_Private](./set_private/)(**bool**) | Sets the value that determines if the HTTP response message or its part is intended for a single user and must not be cached by a shared cache. |
| void [set_ProxyRevalidate](./set_proxyrevalidate/)(**bool**) | Sets the value that determines if the server requires revalidation of a cache entry when it becomes stale for the shared user agent caches. |
| void [set_Public](./set_public/)(**bool**) | Sets the value that determines if an HTTP response can be cached by any cache. |
| void [set_SharedMaxAge](./set_sharedmaxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Sets the shared maximum age value in seconds that overrides the 'max-age' directive in the 'Cache-Control'. header or the 'Expires' header for a shared cache. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Tries to convert a passed string to an instance of the [CacheControlHeaderValue](./) class. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.Slides](../../)