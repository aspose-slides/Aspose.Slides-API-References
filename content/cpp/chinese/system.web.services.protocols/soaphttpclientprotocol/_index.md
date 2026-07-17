---
title: SoapHttpClientProtocol
second_title: Aspose.Slides C++ API 参考
description: "在使用 SOAP 时，客户端代理服务必须继承此类。此类的对象只能使用 System::MakeObject() 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言错误。始终将此类封装为 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 118
url: /zh/system.web.services.protocols/soaphttpclientprotocol/
---
## SoapHttpClientProtocol 类


当使用 SOAP 时，客户端代理服务必须继承此类。此类的对象只能使用 [System::MakeObject()](../../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言错误。始终将此类封装为 [System::SmartPtr](../../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
class SoapHttpClientProtocol : public System::Web::Services::Protocols::HttpWebClientProtocol
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual void [Abort](../webclientprotocol/abort/)() | 取消请求。 |
| virtual void [CheckForCookies](../httpwebclientprotocol/checkforcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Net::HttpWebResponse](../../system.net/httpwebresponse/)\>) | 将指定请求中的 cookie 附加到内部 cookie 容器。 |
| void [Discover](./discover/)() | 将当前实例绑定到 XML [Web](../../system.web/) 服务。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，在该比较中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，在该比较中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| **bool** [get_AllowAutoRedirect](../httpwebclientprotocol/get_allowautoredirect/)() | 获取一个值，指示客户端是否遵循服务器重定向。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](../httpwebclientprotocol/get_clientcertificates/)() | 返回客户端证书的集合。 |
| [String](../../system/string/) [get_ConnectionGroupName](../webclientprotocol/get_connectiongroupname/)() | 获取连接组的名称。 |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../../system.net/cookiecontainer/)\> [get_CookieContainer](../httpwebclientprotocol/get_cookiecontainer/)() | 获取用于存储 cookie 的容器。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\> [get_Credentials](../webclientprotocol/get_credentials/)() | 获取身份验证信息。 |
| **bool** [get_EnableDecompression](../httpwebclientprotocol/get_enabledecompression/)() | 获取一个值，指示是否已启用解压缩。 |
| **bool** [get_PreAuthenticate](../webclientprotocol/get_preauthenticate/)() | 获取一个值，指示是否已启用预身份验证。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::IWebProxy](../../system.net/iwebproxy/)\> [get_Proxy](../httpwebclientprotocol/get_proxy/)() | 获取代理信息。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_RequestEncoding](../webclientprotocol/get_requestencoding/)() | 获取用于发起客户端请求的编码。 |
| [SoapProtocolVersion](../soapprotocolversion/) [get_SoapVersion](./get_soapversion/)() | 获取 SOAP 版本。 |
| **int32_t** [get_Timeout](../webclientprotocol/get_timeout/)() | 获取请求超时前的等待时间间隔。 |
| **bool** [get_UnsafeAuthenticatedConnectionSharing](../httpwebclientprotocol/get_unsafeauthenticatedconnectionsharing/)() | 获取一个值，指示客户端使用 NTLM 身份验证时是否启用连接共享。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Uri](../webclientprotocol/get_uri/)() | 获取 XML [Web](../../system.web/) 服务的 URI。 |
| [String](../../system/string/) [get_Url](../webclientprotocol/get_url/)() | 获取 XML [Web](../../system.web/) 服务的 URL。 |
| **bool** [get_UseDefaultCredentials](../webclientprotocol/get_usedefaultcredentials/)() | 获取一个值，指示 'Credential' 属性是否等于 'DefaultCredentials' 属性。 |
| [String](../../system/string/) [get_UserAgent](../httpwebclientprotocol/get_useragent/)() | 获取 'User-Agent' 头的值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希处理。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| void [InitializeSerializers](./initializeserializers/)(const [System::TypeInfo](../../system/typeinfo/)\&, [System::SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerImplementation](../../system.xml.serialization/xmlserializerimplementation/)\>, [String](../../system/string/)) | 初始化内部字段。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，仅初始化新对象并启用子类的复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并启用子类的复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 情形。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串情形。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定值。 |
| void [set_AllowAutoRedirect](../httpwebclientprotocol/set_allowautoredirect/)(**bool**) | 设置一个值，指示客户端是否遵循服务器重定向。 |
| void [set_ConnectionGroupName](../webclientprotocol/set_connectiongroupname/)([String](../../system/string/)) | 设置连接组的名称。 |
| void [set_CookieContainer](../httpwebclientprotocol/set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../../system.net/cookiecontainer/)\>) | 设置用于存储 cookie 的容器。 |
| void [set_Credentials](../webclientprotocol/set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\>) | 设置身份验证信息。 |
| void [set_EnableDecompression](../httpwebclientprotocol/set_enabledecompression/)(**bool**) | 设置一个值，指示是否启用解压缩。 |
| void [set_PreAuthenticate](../webclientprotocol/set_preauthenticate/)(**bool**) | 设置一个值，指示是否启用预身份验证。 |
| void [set_Proxy](../httpwebclientprotocol/set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[Net::IWebProxy](../../system.net/iwebproxy/)\>) | 设置代理信息。 |
| void [set_RequestEncoding](../webclientprotocol/set_requestencoding/)([System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>) | 设置用于发起客户端请求的编码。 |
| void [set_SoapVersion](./set_soapversion/)([SoapProtocolVersion](../soapprotocolversion/)) | 设置 SOAP 版本。 |
| void [set_Timeout](../webclientprotocol/set_timeout/)(**int32_t**) | 设置请求超时前的等待时间间隔。 |
| void [set_UnsafeAuthenticatedConnectionSharing](../httpwebclientprotocol/set_unsafeauthenticatedconnectionsharing/)(**bool**) | 设置一个值，指示客户端使用 NTLM 身份验证时是否启用连接共享。 |
| void [set_Uri](../webclientprotocol/set_uri/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 设置 XML [Web](../../system.web/) 服务的 URI。 |
| void [set_Url](../webclientprotocol/set_url/)([String](../../system/string/)) | 设置 XML [Web](../../system.web/) 服务的 URL。 |
| void [set_UseDefaultCredentials](../webclientprotocol/set_usedefaultcredentials/)(**bool**) | 设置一个值，指示 'Credential' 属性是否等于 'DefaultCredentials' 属性。 |
| void [set_UserAgent](../httpwebclientprotocol/set_useragent/)([String](../../system/string/)) | 设置 'User-Agent' 头的值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
|  [SoapHttpClientProtocol](./soaphttpclientprotocol/)() | 构造一个新实例。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| void [UnregisterMapping](../httpwebclientprotocol/unregistermapping/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) |  |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参见

* 类 [HttpWebClientProtocol](../httpwebclientprotocol/)
* 命名空间 [System::Web::Services::Protocols](../)
* 库 [Aspose.Slides](../../)