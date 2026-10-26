---
title: HttpWebRequest
second_title: Aspose.Slides C++ API 参考
description: "表示 HTTP web 请求。此类的对象应仅使用 System::MakeObject() 函数进行分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言错误。始终将此类包装为 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 274
url: /zh/system.net/httpwebrequest/
---
## HttpWebRequest 类

表示 HTTP web 请求。此类的对象应仅使用 [System::MakeObject()](../../system/makeobject/) 函数进行分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言错误。始终将此类包装为 [System::SmartPtr](../../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
class HttpWebRequest : public System::Net::WebRequest
```

## 方法

| 方法 | 描述 |
| --- | --- |
| void [Abort](./abort/)() override | 中止当前请求。 |
| virtual void [AddRange](./addrange/)(**int32_t**) | 向当前请求添加 'Range' 标头。 |
| virtual void [AddRange](./addrange/)([System::String](../../system/string/), **int32_t**, **int32_t**) | 向当前请求添加 'Range' 标头。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](./begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 启动异步操作以获取用于向资源写入数据的流。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](./begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 启动针对该资源的异步请求。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([String](../../system/string/)) | 使用指定的 URI 创建 [WebRequest](../webrequest/) 类的一个新实例。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 使用指定的 URI 创建 [WebRequest](../webrequest/) 类的一个新实例。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [CreateDefault](../webrequest/createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 为指定的 URI 方案创建 [WebRequest](../webrequest/) 后代。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([String](../../system/string/)) | 使用指定的 URI 创建 [WebRequest](../webrequest/) 类的一个新实例。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 使用指定的 URI 创建 [WebRequest](../webrequest/) 类的一个新实例。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](./endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | 等待指定的获取流的异步操作完成。 |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](./endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | 等待针对该资源的指定异步请求完成。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [String](../../system/string/) [get_Accept](./get_accept/)() | 获取 'Accept' HTTP 标头的值。 |
| virtual **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | 获取指示请求是否应遵循重定向的值。 |
| virtual **bool** [get_AllowReadStreamBuffering](./get_allowreadstreambuffering/)() | 获取指示是否必须对从资源接收的数据进行缓冲的值。 |
| virtual **bool** [get_AllowWriteStreamBuffering](./get_allowwritestreambuffering/)() | 获取指示发送数据时是否启用缓冲的值。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](../webrequest/get_cachepolicy/)() | 获取缓存策略。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | 获取与当前请求关联的证书集合。 |
| [System::String](../../system/string/) [get_ConnectionGroupName](./get_connectiongroupname/)() override | 获取连接组的名称。 |
| **int64_t** [get_ContentLength](./get_contentlength/)() override | 获取要发送的请求数据的字节数。 |
| [String](../../system/string/) [get_ContentType](./get_contenttype/)() override | 获取请求的 MIME 类型。 |
| **int32_t** [get_ContinueTimeout](./get_continuetimeout/)() | 获取等待 100-Continue 状态码的超时时间。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | 获取与当前 Web 请求关联的 Cookie 容器。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() override | 获取与当前请求关联的身份验证信息。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](../webrequest/get_defaultwebproxy/)() | 获取全局 HTTP 代理。 |
| virtual **bool** [get_HaveResponse](./get_haveresponse/)() | 返回指示是否收到响应的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](./get_headers/)() override | 获取 HTTP 标头的集合。 |
| virtual **bool** [get_KeepAlive](./get_keepalive/)() | 获取指示当前请求是否必须包含 'Keep-Alive' 标头的值。 |
| virtual int [get_MaximumAutomaticRedirections](./get_maximumautomaticredirections/)() | 获取允许的最大重定向次数。 |
| [String](../../system/string/) [get_Method](./get_method/)() override | 获取 HTTP 方法。 |
| **bool** [get_PreAuthenticate](./get_preauthenticate/)() override | 获取指示请求是否必须预先认证的值。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](../webrequest/get_prefixlist/)() | 获取前缀列表。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](./get_proxy/)() override | 获取 HTTP 代理。 |
| virtual [System::String](../../system/string/) [get_Referer](./get_referer/)() | 获取 'Referer' 标头的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() override | 返回请求的 URI。 |
| virtual **bool** [get_SendChunked](./get_sendchunked/)() | 获取指示数据是否必须分段发送的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ServicePoint](../servicepoint/)\> [get_ServicePoint](./get_servicepoint/)() | 返回表示到资源的网络连接的服务点。 |
| virtual **bool** [get_SupportsCookieContainer](./get_supportscookiecontainer/)() | 返回指示当前请求是否可以使用 Cookie 容器的值。 |
| **int32_t** [get_Timeout](./get_timeout/)() override | 获取请求将在其后超时的毫秒时间量。 |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() override | 获取指示 'Credential' 属性是否等于 'DefaultCredentials' 属性的值。 |
| virtual [System::String](../../system/string/) [get_UserAgent](./get_useragent/)() | 获取 'User-Agent' 标头的值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希计算。 |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](./getrequeststream/)() override | 返回用于向资源写入数据的流。 |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](./getresponse/)() override | 返回与当前 Web 请求关联的 Web 响应。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
|  [HttpWebRequest](./httpwebrequest/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 构造一个新实例。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示由 targetType 描述的类型实例。相当于 C# 'is' 操作符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对 string 与 nullptr 情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| static **bool** [RegisterPrefix](../webrequest/registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | 为指定的 URI 注册 [WebRequest](../webrequest/) 后代。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| void [set_Accept](./set_accept/)([String](../../system/string/)) | 设置 'Accept' HTTP 标头的值。 |
| virtual void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | 设置指示请求是否应遵循重定向的值。 |
| virtual void [set_AllowReadStreamBuffering](./set_allowreadstreambuffering/)(**bool**) | 设置指示是否必须对从资源接收的数据进行缓冲的值。 |
| virtual void [set_AllowWriteStreamBuffering](./set_allowwritestreambuffering/)(**bool**) | 设置指示发送数据时是否启用缓冲的值。 |
| virtual void [set_CachePolicy](../webrequest/set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | 设置缓存策略。 |
| virtual void [set_ClientCertificates](./set_clientcertificates/)([System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>) | 设置与当前请求关联的证书集合。 |
| void [set_ConnectionGroupName](./set_connectiongroupname/)([System::String](../../system/string/)) override | 设置连接组的名称。 |
| void [set_ContentLength](./set_contentlength/)(**int64_t**) override | 设置要发送的请求数据的字节数。 |
| void [set_ContentType](./set_contenttype/)([String](../../system/string/)) override | 设置请求的 MIME 类型。 |
| void [set_ContinueTimeout](./set_continuetimeout/)(**int32_t**) | 设置等待 100-Continue 状态码的超时时间。 |
| virtual void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\>) | 设置与当前 Web 请求关联的 Cookie 容器。 |
| void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) override | 设置与当前请求关联的身份验证信息。 |
| static void [set_DefaultWebProxy](../webrequest/set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | 设置全局 HTTP 代理。 |
| void [set_Headers](./set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) override | 设置 HTTP 标头的集合。 |
| virtual void [set_KeepAlive](./set_keepalive/)(**bool**) | 设置指示当前请求是否必须包含 'Keep-Alive' 标头的值。 |
| virtual void [set_MaximumAutomaticRedirections](./set_maximumautomaticredirections/)(int) | 设置允许的最大重定向次数。 |
| void [set_Method](./set_method/)([String](../../system/string/)) override | 设置 HTTP 方法。 |
| void [set_PreAuthenticate](./set_preauthenticate/)(**bool**) override | 设置指示请求是否必须预先认证的值。 |
| static void [set_PrefixList](../webrequest/set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | 设置前缀列表。 |
| void [set_ProtocolVersion](./set_protocolversion/)([System::Version](../../system/version/)) | 设置 HTTP 的版本。 |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) override | 设置 HTTP 代理。 |
| virtual void [set_Referer](./set_referer/)([System::String](../../system/string/)) | 设置 'Referer' 标头的值。 |
| virtual void [set_SendChunked](./set_sendchunked/)(**bool**) | 设置指示数据是否必须分段发送的值。 |
| void [set_Timeout](./set_timeout/)(int) override | 设置请求将在其后超时的毫秒时间量。 |
| virtual void [set_Timeout](../webrequest/set_timeout/)(**int32_t**) | 设置请求将在其后超时的毫秒时间量。 |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) override | 设置指示 'Credential' 属性是否等于 'DefaultCredentials' 属性的值。 |
| virtual void [set_UserAgent](./set_useragent/)([System::String](../../system/string/)) | 设置 'User-Agent' 标头的值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参见

* 类 [WebRequest](../webrequest/)
* 命名空间 [System::Net](../)
* 库 [Aspose.Slides](../../)