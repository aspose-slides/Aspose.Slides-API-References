---
title: "System::Net"
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 651
url: /zh/system.net/
---
## 类

| 类 | 描述 |
| --- | --- |
| [Cookie](./cookie/) | 表示一个 HTTP cookie。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [CookieCollection](./cookiecollection/) | 表示已排序 cookie 的列表。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [CookieComparer](./cookiecomparer/) | 用于比较 [Cookie](./cookie/) 类实例。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [CookieContainer](./cookiecontainer/) | 提供 CookieCollection 类实例的容器。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [CookieParser](./cookieparser/) | 用于解析 cookie 头并创建 [Cookie](./cookie/) 类的实例。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [CredentialCache](./credentialcache/) | 提供凭据存储。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [Details_CookieException](./details_cookieexception/) | 表示当 [CookieContainer](./cookiecontainer/) 的大小超过 MaxCookieSize 属性值时抛出的异常。切勿手动创建此类的实例。请改用 CookieException 类。切勿将 CookieException 类实例包装为 [System::SmartPtr](../system/smartptr/)。 |
| [Details_WebException](./details_webexception/) | 表示当 [WebRequest](./webrequest/) 发生错误时抛出的异常。切勿手动创建此类的实例。请改用 WebException 类。切勿将 WebException 类实例包装为 [System::SmartPtr](../system/smartptr/)。 |
| [Dns](./dns/) | 提供用于 DNS 的方法。 |
| [DnsEndPoint](./dnsendpoint/) | 包含应用程序用于连接服务的信息。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [EndPoint](./endpoint/) | 抽象类，包含网络地址。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [FileWebRequest](./filewebrequest/) | 提供 [WebRequest](./webrequest/) 抽象类的实现，以便与文件系统协作。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [FileWebResponse](./filewebresponse/) | 提供 [WebResponse](./webresponse/) 抽象类的实现，以便与文件系统协作。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [FtpWebRequest](./ftpwebrequest/) | 实现文件传输协议 (FTP) 客户端。虚拟类，用于在翻译代码中链接 [FtpWebRequest](./ftpwebrequest/) 引用，但不执行。未包含任何正确实现的成员。 |
| [FtpWebResponse](./ftpwebresponse/) | 虚拟类，用于在翻译代码中链接 [FtpWebResponse](./ftpwebresponse/) 引用，但不执行。未包含任何正确实现的成员。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [HeaderVariantInfo](./headervariantinfo/) | 用于匹配 cookie 名称和规范。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [HttpKnownHeaderNames](./httpknownheadernames/) | 包含已知头部名称的字符串值。 |
| [HttpRequestHeaderExtensions](./httprequestheaderextensions/) | 包含用于处理 HttpRequestHeader 枚举值的实用方法。 |
| [HttpResponseHeaderExtensions](./httpresponseheaderextensions/) | 包含用于处理 HttpResponseHeader 枚举值的实用方法。 |
| [HttpStatusDescription](./httpstatusdescription/) | 包含获取 HTTP 状态字符串表示的实用方法。 |
| [HttpVersion](./httpversion/) | 包含 HTTP 的版本。 |
| [HttpWebRequest](./httpwebrequest/) | 表示 HTTP Web 请求。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [HttpWebResponse](./httpwebresponse/) | 表示 HTTP Web 响应。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [ICredentials](./icredentials/) | 提供身份验证接口。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [ICredentialsByHost](./icredentialsbyhost/) | 提供用于检索主机、端口和身份验证类型凭据的身份验证接口。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [IPAddress](./ipaddress/) | 表示 IP 地址。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [IPEndPoint](./ipendpoint/) | 表示包含 IP 地址和端口的网络端点。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [IPHostEntry](./iphostentry/) | 表示互联网主机地址的信息。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [IWebProxy](./iwebproxy/) | 此接口用于实现对 [WebRequest](./webrequest/) 类的代理访问。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [IWebRequestCreate](./iwebrequestcreate/) | 提供创建 [WebRequest](./webrequest/) 类实例的方法。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [NetworkCredential](./networkcredential/) | 为基于密码的身份验证方案提供凭据。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [PathList](./pathlist/) | 表示 [CookieCollection](./cookiecollection/) 类实例的列表。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [ServicePoint](./servicepoint/) | 提供 HTTP 连接管理。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [ServicePointManager](./servicepointmanager/) | 管理 [ServicePoint](./servicepoint/) 类实例的生命周期阶段（创建、维护和删除）。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [SocketAddress](./socketaddress/) | 用于存储关于 [EndPoint](./endpoint/) 类实例的序列化信息。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [UriScheme](./urischeme/) | 表示 URI 的方案。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [WebClient](./webclient/) | [WebClient](./webclient/) 提供发送和接收数据的通用方法。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [WebHeaderCollection](./webheadercollection/) | 表示协议头集合。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [WebProxy](./webproxy/) | 表示 HTTP Web 代理服务器。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [WebRequest](./webrequest/) | 表示 Web 请求。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [WebRequestMethods](./webrequestmethods/) | 表示 Web 请求的字符串常量。 |
| [WebResponse](./webresponse/) | 表示 Web 响应。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |

## 枚举

| 枚举 | 描述 |
| --- | --- |
| [AuthenticationSchemes](./authenticationschemes/) | 枚举身份验证方案。 |
| [CookieVariant](./cookievariant/) | 枚举 Cookie 规范。 |
| [DecompressionMethods](./decompressionmethods/) | 枚举压缩/解压缩算法。 |
| [HttpRequestHeader](./httprequestheader/) | 枚举请求头。 |
| [HttpResponseHeader](./httpresponseheader/) | 枚举 HTTP 响应头。 |
| [HttpStatusCode](./httpstatuscode/) |  |
| [SecurityProtocolType](./securityprotocoltype/) | 枚举安全协议类型。 |
| [TransportType](./transporttype/) | 定义套接字允许的传输类型。 |
| [WebExceptionStatus](./webexceptionstatus/) | 枚举 WebException 类的状态码。 |
| [WebHeaderCollectionType](./webheadercollectiontype/) | 枚举协议头集合的类型。 |

## 类型定义

| 类型定义 | 描述 |
| --- | --- |
| [CookieException](./cookieexception/) |  |
| [BindIPEndPoint](./bindipendpoint/) |  |
| [WebException](./webexception/) |  |