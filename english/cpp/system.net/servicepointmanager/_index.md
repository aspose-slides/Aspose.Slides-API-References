---
title: ServicePointManager
second_title: Aspose.Slides for C++ API Reference
description: "Manages the lifecycle stages (creating, maintaining, and deleting) of the ServicePoint class instances. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 430
url: /cpp/system.net/servicepointmanager/
---
## ServicePointManager class


Manages the lifecycle stages (creating, maintaining, and deleting) of the [ServicePoint](../servicepoint/) class instances. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ServicePointManager : public System::Object
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
| static [System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\> [get_CertificatePolicy](./get_certificatepolicy/)() | Gets a certificate policy. |
| static **bool** [get_CheckCertificateRevocationList](./get_checkcertificaterevocationlist/)() | Gets a value that indicates if the certificate must be checked against the certificate authority revocation list. |
| static **int32_t** [get_DefaultConnectionLimit](./get_defaultconnectionlimit/)() | Gets the maximum number of concurrent connections that are allowed by the ServicePoint-class instances. |
| static **int32_t** [get_DnsRefreshTimeout](./get_dnsrefreshtimeout/)() | Gets a timeout in milliseconds during which a DNS resolution is considered valid. |
| static **bool** [get_EnableDnsRoundRobin](./get_enablednsroundrobin/)() | Gets a value that indicates if a DNS resolution rotates among the applicable IP addresses. |
| static [System::Net::Security::EncryptionPolicy](../../system.net.security/encryptionpolicy/) [get_EncryptionPolicy](./get_encryptionpolicy/)() | Returns the encryption policy that is used by the current instance. |
| static **bool** [get_Expect100Continue](./get_expect100continue/)() | Gets a value that indicates if the ServicePoint-class instances use the 100-Continue behavior. |
| static **int32_t** [get_MaxServicePointIdleTime](./get_maxservicepointidletime/)() | Gets the maximum idle time of the ServicePoint-class instances. |
| static **int32_t** [get_MaxServicePoints](./get_maxservicepoints/)() | Gets the maximum number of the ServicePoint-class instances that can be managed by the current instance. |
| static **bool** [get_ReusePort](./get_reuseport/)() | Gets a value that indicates if the output connections sockets use the 'SO_REUSE_UNICASTPORT' option. |
| static [SecurityProtocolType](../securityprotocoltype/) [get_SecurityProtocol](./get_securityprotocol/)() | Gets the security protocol type used by the ServicePoint-class instances that are managed by the current instance. |
| static [Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/) [get_ServerCertificateValidationCallback](./get_servercertificatevalidationcallback/)() | Gets the callback that is used to validate a server certificate. |
| static **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | Gets a value that indicates if the ServicePoint-class instances use the Nagle algorithm. |
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
| static void [set_CertificatePolicy](./set_certificatepolicy/)([System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\>) | Sets a certificate policy. |
| static void [set_CheckCertificateRevocationList](./set_checkcertificaterevocationlist/)(**bool**) | Sets a value that indicates if the certificate must be checked against the certificate authority revocation list. |
| static void [set_DefaultConnectionLimit](./set_defaultconnectionlimit/)(**int32_t**) | Sets the maximum number of concurrent connections that are allowed by the ServicePoint-class instances. |
| static void [set_DnsRefreshTimeout](./set_dnsrefreshtimeout/)(**int32_t**) | Sets a timeout in milliseconds during which a DNS resolution is considered valid. |
| static void [set_EnableDnsRoundRobin](./set_enablednsroundrobin/)(**bool**) | Sets a value that indicates if a DNS resolution rotates among the applicable IP addresses. |
| static void [set_Expect100Continue](./set_expect100continue/)(**bool**) | Sets a value that indicates if the ServicePoint-class instances use the 100-Continue behavior. |
| static void [set_MaxServicePointIdleTime](./set_maxservicepointidletime/)(**int32_t**) | Sets the maximum idle time of the ServicePoint-class instances. |
| static void [set_MaxServicePoints](./set_maxservicepoints/)(**int32_t**) | Sets the maximum number of the ServicePoint-class instances that can be managed by the current instance. |
| static void [set_ReusePort](./set_reuseport/)(**bool**) | Sets a value that indicates if the output connections sockets use the 'SO_REUSE_UNICASTPORT' option. |
| static void [set_SecurityProtocol](./set_securityprotocol/)([SecurityProtocolType](../securityprotocoltype/)) | Sets the security protocol type used by the ServicePoint-class instances that are managed by the current instance. |
| static void [set_ServerCertificateValidationCallback](./set_servercertificatevalidationcallback/)([Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/)) | Sets the callback that is used to validate a server certificate. |
| static void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | Sets a value that indicates if the ServicePoint-class instances use the Nagle algorithm. |
| static void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | Sets the value that indicates if the 'Keep-Alive' option is enabled. |
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
## Fields

| Field | Description |
| --- | --- |
| static [DefaultNonPersistentConnectionLimit](./defaultnonpersistentconnectionlimit/) | The default number of non-persistent connections. |
| static [DefaultPersistentConnectionLimit](./defaultpersistentconnectionlimit/) | The default number of persistent connections. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.Slides](../../)