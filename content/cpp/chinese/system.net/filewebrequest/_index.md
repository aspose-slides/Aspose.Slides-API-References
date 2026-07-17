---
title: FileWebRequest
second_title: Aspose.Slides for C++ API 参考
description: "提供 WebRequest 抽象类的实现以在文件系统上工作。此类的对象应仅使用 System::MakeObject() 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装在 System::SmartPtr 指针中，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 144
url: /zh/system.net/filewebrequest/
---
## FileWebRequest 类

Provides implementation of the [WebRequest](../webrequest/) abstract class to work with the file system. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class FileWebRequest : public System::Net::WebRequest
```

## 方法

| 方法 | 描述 |
| --- | --- |
| void [Abort](./abort/)() override | 中止当前请求。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](./begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 启动一个异步操作，以获取用于向资源写入数据的流。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](./begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 启动对资源的异步请求。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([String](../../system/string/)) | 使用指定的 URI 创建 [WebRequest](../webrequest/) 类的新实例。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 使用指定的 URI 创建 [WebRequest](../webrequest/) 类的新实例。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [CreateDefault](../webrequest/createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 为指定的 URI 模式创建 [WebRequest](../webrequest/) 派生类。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](../httpwebrequest/)\> [CreateHttp](../webrequest/createhttp/)([String](../../system/string/)) | 使用指定的 URI 创建 [WebRequest](../webrequest/) 类的新实例。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](../httpwebrequest/)\> [CreateHttp](../webrequest/createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 使用指定的 URI 创建 [WebRequest](../webrequest/) 类的新实例。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](./endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | 等待指定获取流的异步操作完成。 |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](./endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | 等待指定资源的异步请求完成。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
|  [FileWebRequest](./filewebrequest/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 构造一个新实例。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](../webrequest/get_cachepolicy/)() | 获取缓存策略。 |
| virtual [System::String](../../system/string/) [get_ConnectionGroupName](../webrequest/get_connectiongroupname/)() | 获取连接组的名称。 |
| virtual **int64_t** [get_ContentLength](../webrequest/get_contentlength/)() | 获取要发送的请求数据的字节数。 |
| [String](../../system/string/) [get_ContentType](./get_contenttype/)() override | 获取请求的 MIME 类型。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](../webrequest/get_credentials/)() | 获取与当前请求关联的身份验证信息。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](../webrequest/get_defaultwebproxy/)() | 获取全局 HTTP 代理。 |
| [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](./get_headers/)() override | 获取 HTTP 标头的集合。 |
| [String](../../system/string/) [get_Method](./get_method/)() override | 获取 HTTP 方法。 |
| virtual **bool** [get_PreAuthenticate](../webrequest/get_preauthenticate/)() | 获取一个值，指示请求是否必须预先认证。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](../webrequest/get_prefixlist/)() | 获取前缀列表。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](../webrequest/get_proxy/)() | 获取 HTTP 代理。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() override | 返回请求的 URI。 |
| virtual **int32_t** [get_Timeout](../webrequest/get_timeout/)() | 获取请求将在超时前的毫秒数。 |
| virtual **bool** [get_UseDefaultCredentials](../webrequest/get_usedefaultcredentials/)() | 获取一个值，指示 'Credential' 属性是否等于 'DefaultCredentials' 属性。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](../webrequest/getrequeststream/)() | 返回用于向资源写入数据的流。 |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](./getresponse/)() override | 返回与当前 web 请求关联的 web 响应。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| static **bool** [RegisterPrefix](../webrequest/registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | 为指定的 URI 注册 [WebRequest](../webrequest/) 派生类。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_CachePolicy](../webrequest/set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | 设置缓存策略。 |
| virtual void [set_ConnectionGroupName](../webrequest/set_connectiongroupname/)([System::String](../../system/string/)) | 设置连接组的名称。 |
| virtual void [set_ContentLength](../webrequest/set_contentlength/)(**int64_t**) | 设置要发送的请求数据的字节数。 |
| void [set_ContentType](./set_contenttype/)([String](../../system/string/)) override | 设置请求的 MIME 类型。 |
| virtual void [set_Credentials](../webrequest/set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) | 设置与当前请求关联的身份验证信息。 |
| static void [set_DefaultWebProxy](../webrequest/set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | 设置全局 HTTP 代理。 |
| void [set_Headers](./set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) override | 设置 HTTP 标头的集合。 |
| void [set_Method](./set_method/)([String](../../system/string/)) override | 设置 HTTP 方法。 |
| virtual void [set_PreAuthenticate](../webrequest/set_preauthenticate/)(**bool**) | 设置一个值，指示请求是否必须预先认证。 |
| static void [set_PrefixList](../webrequest/set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | 设置前缀列表。 |
| virtual void [set_Proxy](../webrequest/set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | 设置 HTTP 代理。 |
| void [set_Timeout](./set_timeout/)(int) override | 设置请求将在超时前的毫秒数。 |
| virtual void [set_Timeout](../webrequest/set_timeout/)(**int32_t**) | 设置请求将在超时前的毫秒数。 |
| virtual void [set_UseDefaultCredentials](../webrequest/set_usedefaultcredentials/)(**bool**) | 设置一个值，指示 'Credential' 属性是否等于 'DefaultCredentials' 属性。 |
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
## 另见

* 类 [WebRequest](../webrequest/)
* 命名空间 [System::Net](../)
* 库 [Aspose.Slides](../../)