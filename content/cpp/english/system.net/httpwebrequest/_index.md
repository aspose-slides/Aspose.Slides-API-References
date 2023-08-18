---
title: HttpWebRequest
second_title: Aspose.Slides for C++ API Reference
description: "Represents the HTTP web request. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 274
url: /system.net/httpwebrequest/
---
## HttpWebRequest class


Represents the HTTP web request. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpWebRequest : public System::Net::WebRequest
```

## Methods

| Method | Description |
| --- | --- |
| void [Abort](./abort/)() override | Aborts the current request. |
| virtual void [AddRange](./addrange/)(**int32_t**) | Adds the 'Range' header to the current request. |
| virtual void [AddRange](./addrange/)([System::String](../../system/string/), **int32_t**, **int32_t**) | Adds the 'Range' header to the current request. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](./begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Initiates an asynchronous operation to get a stream for writing data to the resource. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](./begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Initiates an asynchronous request for the resource. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([String](../../system/string/)) | Creates a new instance of the [WebRequest](../webrequest/) class using the specified URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Creates a new instance of the [WebRequest](../webrequest/) class using the specified URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [CreateDefault](../webrequest/createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Creates a [WebRequest](../webrequest/) descendant for the specified URI scheme. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([String](../../system/string/)) | Creates a new instance of the [WebRequest](../webrequest/) class using the specified URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Creates a new instance of the [WebRequest](../webrequest/) class using the specified URI. |
| [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](./endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Waits until the specified asynchronous operation to get a stream completes. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](./endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Waits until the specified asynchronous request for the resource completes. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| [String](../../system/string/) [get_Accept](./get_accept/)() | Gets the 'Accept' HTTP header value. |
| virtual **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | Gets a value that indicates if the request should follow redirections. |
| virtual **bool** [get_AllowReadStreamBuffering](./get_allowreadstreambuffering/)() | Gets a value indicates if the data received from the resource must be buffered. |
| virtual **bool** [get_AllowWriteStreamBuffering](./get_allowwritestreambuffering/)() | Gets a value that indicates if buffering is enabled for sending data. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](../webrequest/get_cachepolicy/)() | Gets the cache policy. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | Gets the collection of the certificates that are associated with the current request. |
| [System::String](../../system/string/) [get_ConnectionGroupName](./get_connectiongroupname/)() override | Gets the name of the connection group. |
| **int64_t** [get_ContentLength](./get_contentlength/)() override | Gets the number of bytes of the request data to sent. |
| [String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Gets the MIME type of the request. |
| **int32_t** [get_ContinueTimeout](./get_continuetimeout/)() | Gets a timeout to wait until the 100-Continue status code is received. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | Gets a cookie container associated with the current web request. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() override | Gets authentication information that is associated with the current request. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](../webrequest/get_defaultwebproxy/)() | Gets the global HTTP proxy. |
| virtual **bool** [get_HaveResponse](./get_haveresponse/)() | Returns a value that indicates if a response is received. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](./get_headers/)() override | Gets the collection of the HTTP headers. |
| virtual **bool** [get_KeepAlive](./get_keepalive/)() | Gets a value that indicates if the current request must contain the 'Keep-Alive' header. |
| virtual int [get_MaximumAutomaticRedirections](./get_maximumautomaticredirections/)() | Gets a maximum number of allowed redirections. |
| [String](../../system/string/) [get_Method](./get_method/)() override | Gets the HTTP method. |
| **bool** [get_PreAuthenticate](./get_preauthenticate/)() override | Gets a value that indicates if the request must be pre-authenticated. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](../webrequest/get_prefixlist/)() | Gets the prefix list. |
| [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](./get_proxy/)() override | Gets the HTTP proxy. |
| virtual [System::String](../../system/string/) [get_Referer](./get_referer/)() | Gets a value of the 'Referer' header. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() override | Returns the request URI. |
| virtual **bool** [get_SendChunked](./get_sendchunked/)() | Gets a value that indicates if data must be sent in segments. |
| [System::SharedPtr](../../system/sharedptr/)\<[ServicePoint](../servicepoint/)\> [get_ServicePoint](./get_servicepoint/)() | Returns a service point that represents the network connection to the resource. |
| virtual **bool** [get_SupportsCookieContainer](./get_supportscookiecontainer/)() | Returns a value that indicates if the current request can use a cookie container. |
| **int32_t** [get_Timeout](./get_timeout/)() override | Gets an amount of time in milliseconds after which the request will be timed out. |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() override | Gets a value that indicates if the 'Credential' property is equal to the 'DefaultCredentials' property. |
| virtual [System::String](../../system/string/) [get_UserAgent](./get_useragent/)() | Gets a value of the 'User-Agent' header. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](./getrequeststream/)() override | Returns the stream for writing data to the resource. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](./getresponse/)() override | Returns the web response associated with the current web request. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
|  [HttpWebRequest](./httpwebrequest/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Constructs a new instance. |
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
| static **bool** [RegisterPrefix](../webrequest/registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | Registers the [WebRequest](../webrequest/) descendant for the specified URI. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [set_Accept](./set_accept/)([String](../../system/string/)) | Sets the 'Accept' HTTP header value. |
| virtual void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | Sets a value that indicates if the request should follow redirections. |
| virtual void [set_AllowReadStreamBuffering](./set_allowreadstreambuffering/)(**bool**) | Sets a value indicates if the data received from the resource must be buffered. |
| virtual void [set_AllowWriteStreamBuffering](./set_allowwritestreambuffering/)(**bool**) | Sets a value that indicates if buffering is enabled for sending data. |
| virtual void [set_CachePolicy](../webrequest/set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | Sets the cache policy. |
| virtual void [set_ClientCertificates](./set_clientcertificates/)([System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>) | Sets the collection of the certificates that are associated with the current request. |
| void [set_ConnectionGroupName](./set_connectiongroupname/)([System::String](../../system/string/)) override | Sets the name of the connection group. |
| void [set_ContentLength](./set_contentlength/)(**int64_t**) override | Sets the number of bytes of the request data to sent. |
| void [set_ContentType](./set_contenttype/)([String](../../system/string/)) override | Sets the MIME type of the request. |
| void [set_ContinueTimeout](./set_continuetimeout/)(**int32_t**) | Sets a timeout to wait until the 100-Continue status code is received. |
| virtual void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\>) | Sets a cookie container associated with the current web request. |
| void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) override | Sets authentication information that is associated with the current request. |
| static void [set_DefaultWebProxy](../webrequest/set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | Sets the global HTTP proxy. |
| void [set_Headers](./set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) override | Sets the collection of the HTTP headers. |
| virtual void [set_KeepAlive](./set_keepalive/)(**bool**) | Sets a value that indicates if the current request must contain the 'Keep-Alive' header. |
| virtual void [set_MaximumAutomaticRedirections](./set_maximumautomaticredirections/)(int) | Sets a maximum number of allowed redirections. |
| void [set_Method](./set_method/)([String](../../system/string/)) override | Sets the HTTP method. |
| void [set_PreAuthenticate](./set_preauthenticate/)(**bool**) override | Sets a value that indicates if the request must be pre-authenticated. |
| static void [set_PrefixList](../webrequest/set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | Sets the prefix list. |
| void [set_ProtocolVersion](./set_protocolversion/)([System::Version](../../system/version/)) | Sets the version of the HTTP. |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) override | Sets the HTTP proxy. |
| virtual void [set_Referer](./set_referer/)([System::String](../../system/string/)) | Sets a value of the 'Referer' header. |
| virtual void [set_SendChunked](./set_sendchunked/)(**bool**) | Sets a value that indicates if data must be sent in segments. |
| void [set_Timeout](./set_timeout/)(int) override | Sets an amount of time in milliseconds after which the request will be timed out. |
| virtual void [set_Timeout](../webrequest/set_timeout/)(**int32_t**) | Sets an amount of time in milliseconds after which the request will be timed out. |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) override | Sets a value that indicates if the 'Credential' property is equal to the 'DefaultCredentials' property. |
| virtual void [set_UserAgent](./set_useragent/)([System::String](../../system/string/)) | Sets a value of the 'User-Agent' header. |
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

* Class [WebRequest](../webrequest/)
* Namespace [System::Net](../)
* Library [Aspose.Slides](../../)