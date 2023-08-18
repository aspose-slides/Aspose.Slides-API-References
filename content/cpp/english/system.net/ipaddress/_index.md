---
title: IPAddress
second_title: Aspose.Slides for C++ API Reference
description: "Represents the IP address. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 326
url: /system.net/ipaddress/
---
## IPAddress class


Represents the IP address. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class IPAddress : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| [System::Net::Sockets::AddressFamily](../../system.net.sockets/addressfamily/) [get_AddressFamily](./get_addressfamily/)() | Returns the address family. |
| **bool** [get_IsIPv4MappedToIPv6](./get_isipv4mappedtoipv6/)() | Returns a value that indicates if the address is an IPv4 address and is mapped to an IPv6 address. |
| **bool** [get_IsIPv6LinkLocal](./get_isipv6linklocal/)() | Returns a value that indicates if the address is an IPv6 link-local address. |
| **bool** [get_IsIPv6Multicast](./get_isipv6multicast/)() | Returns a value that indicates if the address is an global IPv6 multicast address. |
| **bool** [get_IsIPv6SiteLocal](./get_isipv6sitelocal/)() | Returns a value that indicates if the address is an IPv6 site-local address. |
| **bool** [get_IsIPv6Teredo](./get_isipv6teredo/)() | Returns a value that indicates if the address is an IPv6 Teredo address. |
| **int64_t** [get_ScopeId](./get_scopeid/)() | Gets the scope identifier of the IPv6 address. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetAddressBytes](./getaddressbytes/)() | Returns a byte array of the IP address. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | Returns a pointer to implementation. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| static **int64_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int64_t**) | Converts the specified host byte order to the corresponding network byte order. |
| static **int32_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int32_t**) | Converts the specified host byte order to the corresponding network byte order. |
| static **int16_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int16_t**) | Converts the specified host byte order to the corresponding network byte order. |
|  [IPAddress](./ipaddress/)(**int64_t**) | Constructs a new instance. |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int64_t**) | Constructs a new instance. |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Constructs a new instance. |
|  [IPAddress](./ipaddress/)() | Constructs a new instance. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| static **bool** [IsLoopback](./isloopback/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>) | Returns a value that indicates if the specified address is a loopback address. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv4](./maptoipv4/)() | Maps the address to the IPv4 address. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv6](./maptoipv6/)() | Maps the address to the IPv6 address. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
| static **int64_t** [NetworkToHostOrder](./networktohostorder/)(**int64_t**) | Converts the specified network byte order to the corresponding host byte order. |
| static **int32_t** [NetworkToHostOrder](./networktohostorder/)(**int32_t**) | Converts the specified network byte order to the corresponding host byte order. |
| static **int16_t** [NetworkToHostOrder](./networktohostorder/)(**int16_t**) | Converts the specified network byte order to the corresponding host byte order. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [Parse](./parse/)([String](../../system/string/)) | Converts a passed string to an instance of the [IPAddress](./) class. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [set_ScopeId](./set_scopeid/)(**int64_t**) | Sets the scope identifier of the IPv6 address. |
| void [SetImpl](./setimpl/)([ImplPtr](./implptr/)) | Sets a pointer to implementation. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>\&) | Tries to convert a passed string to an instance of the [IPAddress](./) class. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## Fields

| Field | Description |
| --- | --- |
| static [Any](./any/) | The IPv4 address that indicates if the server must listen all network interfaces. |
| static [Broadcast](./broadcast/) | The IPv4 broadcast address. |
| static [IPv6Any](./ipv6any/) | The IPv6 address that indicates if the server must listen all network interfaces. |
| static [IPv6Loopback](./ipv6loopback/) | The IPv6 loopback address. |
| static [IPv6None](./ipv6none/) | The IPv6 address that indicates if the server mustn't listen any network interface. |
| static [Loopback](./loopback/) | The IPv4 loopback address. |
| static [None](./none/) | The IPv4 address that indicates if the server mustn't listen any network interface. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ImplPtr](./implptr/) | A pointer to the implementation type. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.Slides](../../)