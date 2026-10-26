---
title: Uri
second_title: Aspose.Slides C++ API 参考
description: "统一资源标识符。此类的对象只能使用 System::MakeObject() 函数分配。绝不要在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类封装在 System::SmartPtr 指针中，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 1366
url: /zh/system/uri/
---
## Uri 类

统一资源标识符。此类的对象只能使用 [System::MakeObject()](../makeobject/) 函数分配。绝不要在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类封装在 [System::SmartPtr](../smartptr/) 指针中，并使用该指针将其作为参数传递给函数。

```cpp
class Uri : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static [UriHostNameType](../urihostnametype/) [CheckHostName](./checkhostname/)([String](../string/)) | 确定指定主机名的类型。 |
| static **bool** [CheckSchemeName](./checkschemename/)(const [String](../string/)\&) | 确定指定的方案是否有效。 |
| static **int32_t** [Compare](./compare/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [UriComponents](../uricomponents/), [UriFormat](../uriformat/), [StringComparison](../stringcomparison/)) | 使用指定的比较规则比较指定的 [Uri](./) 对象。 |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override | 确定当前对象和指定对象表示的 URI 是否相等。 |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | 使用 C# [Object.Equals](../object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准 NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准 NaN 不等于任何值，包括 NaN 本身。 |
| static [String](../string/) [EscapeDataString](./escapedatastring/)(const [String](../string/)\&) | 将字符串转换为其转义表示。 |
| static [String](../string/) [EscapeUriString](./escapeuristring/)(const [String](../string/)\&) | 将 URI 字符串转换为其转义表示。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| static **int32_t** [FromHex](./fromhex/)(char16_t) | 获取十六进制数字的十进制值。 |
| [String](../string/) [get_AbsolutePath](./get_absolutepath/)() const | 返回 URI 的绝对路径。 |
| [String](../string/) [get_AbsoluteUri](./get_absoluteuri/)() const | 返回绝对 URI。 |
| [String](../string/) [get_Authority](./get_authority/)() const | 返回服务器的主机名和端口号。 |
| [String](../string/) [get_DnsSafeHost](./get_dnssafehost/)() const | 返回未转义的主机名。 |
| [String](../string/) [get_Fragment](./get_fragment/)() const | 返回转义后的 URI 片段。 |
| [String](../string/) [get_Host](./get_host/)() const | 返回主机名。 |
| [UriHostNameType](../urihostnametype/) [get_HostNameType](./get_hostnametype/)() const | 返回主机名类型。 |
| [String](../string/) [get_IdnHost](./get_idnhost/)() const | 返回主机的国际域名。 |
| **bool** [get_IsAbsoluteUri](./get_isabsoluteuri/)() const | 确定当前对象表示的 URI 是否为绝对。 |
| **bool** [get_IsDefaultPort](./get_isdefaultport/)() const | 确定当前对象表示的 URI 对于其方案是否使用默认端口。 |
| **bool** [get_IsFile](./get_isfile/)() const | 确定当前对象表示的 URI 是否为文件。 |
| **bool** [get_IsLoopback](./get_isloopback/)() const | 确定当前对象表示的 URI 是否引用本地主机。 |
| **bool** [get_IsUnc](./get_isunc/)() const | 确定当前对象表示的 URI 是否为 UNC 路径。 |
| [String](../string/) [get_LocalPath](./get_localpath/)() const | 返回当前对象表示的 URI 所引用的文件名的操作系统表示形式。 |
| [String](../string/) [get_OriginalString](./get_originalstring/)() const | 返回构造当前对象时传递给构造函数的 URI 字符串。 |
| [String](../string/) [get_PathAndQuery](./get_pathandquery/)() const | 返回当前对象表示的 URI 的绝对路径和查询部分，二者用问号 (?) 分隔。 |
| **int32_t** [get_Port](./get_port/)() const | 返回当前对象表示的 URI 的端口号。 |
| [String](../string/) [get_Query](./get_query/)() const | 返回当前对象表示的 URI 中包含的查询信息。 |
| [String](../string/) [get_Scheme](./get_scheme/)() const | 返回当前对象表示的 URI 的方案。 |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [get_Segments](./get_segments/)() const | 返回包含当前对象表示的 URI 路径段的字符串数组。 |
| **bool** [get_UserEscaped](./get_userescaped/)() const | 确定传递给当前对象构造函数的 URI 字符串是否已完全转义。 |
| [String](../string/) [get_UserInfo](./get_userinfo/)() const | 返回与当前对象表示的 URI 关联的用户名、密码和其他用户信息。 |
| [String](../string/) [GetComponents](./getcomponents/)([UriComponents](../uricomponents/), [UriFormat](../uriformat/)) const | 使用指定的转义方式返回当前对象表示的 URI 的指定组件。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 获取 URI 的哈希码。 |
| [String](../string/) [GetLeftPart](./getleftpart/)([UriPartial](../uripartial/)) | 返回当前对象表示的 URI 的指定部分。 |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../object/gettype/) 调用。 |
| static [String](../string/) [HexEscape](./hexescape/)(char16_t) | 返回指定字符的十六进制等价字符。 |
| static char16_t [HexUnescape](./hexunescape/)(const [String](../string/)\&, **int32_t**\&) | 将指定字符的十六进制表示转换为字符。 |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| **bool** [IsBaseOf](./isbaseof/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) const | 确定当前 [Uri](./) 对象表示的 URI 是否是指定 [Uri](./) 对象表示的 URI 的基 URI。 |
| static **bool** [IsHexDigit](./ishexdigit/)(char16_t) | 确定指定字符是否为有效的十六进制数字。 |
| static **bool** [IsHexEncoding](./ishexencoding/)(const [String](../string/)\&, **int32_t**) | 确定指定字符串中指定位置的字符是否为十六进制编码。 |
| **bool** [IsWellFormedOriginalString](./iswellformedoriginalstring/)() const | 指示用于构造此 [Uri](./) 的字符串是否格式良好且无需进一步转义。 |
| static **bool** [IsWellFormedUriString](./iswellformeduristring/)(const [String](../string/)\&, [UriKind](../urikind/)) | 确定指定字符串是否为格式良好的 URI。 |
| void [Lock](../object/lock/)() | 实现 C# lock() 语句的锁定。可直接调用或使用 [LockContext](../lockcontext/) 哨兵对象。 |
| [String](../string/) [MakeRelative](./makerelative/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | 确定两个 [Uri](./) 实例之间的差异。 |
| [SharedPtr](../sharedptr/)\<[Uri](./)\> [MakeRelativeUri](./makerelativeuri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | 确定当前对象和指定 [Uri](./) 对象表示的 URI 之间的差异。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../object/object/)([Object](../object/) const\&) | 复制构造函数。实际上不复制任何内容，仅初始化新对象并启用子类的复制构造。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并启用子类的复制构造。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) 的特化，用于字符串和 nullptr 情况。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) 的特化，用于字符串情况。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| [String](../string/) [ToString](./tostring/)() const override | 返回当前对象表示的 URI 的字符串表示。 |
| static **bool** [TryCreate](./trycreate/)(const [String](../string/)\&, [UriKind](../urikind/), [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | 构造一个表示指定 URI 的 [Uri](./) 对象；参数指定 URI 类型。 |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | 从指定的表示基 URI 的 [Uri](./) 对象和相对 URI 的字符串表示构造一个 [Uri](./) 对象。 |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | 从指定的基 URI 和相对 URI 构造一个 [Uri](./) 对象。 |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | 实现 C# typeof([System.Object](../object/)) 构造。 |
| static [String](../string/) [UnescapeDataString](./unescapedatastring/)(const [String](../string/)\&) | 对指定的转义字符串进行反转义。 |
| void [Unlock](../object/unlock/)() | 实现 C# lock() 语句的解锁。可直接调用或使用 [LockContext](../lockcontext/) 哨兵对象。 |
|  [Uri](./uri/)(const [String](../string/)\&) | 构造一个表示指定 URI 的 [Uri](./) 对象。 |
|  [Uri](./uri/)(const [String](../string/)\&, **bool**) | 构造一个表示指定 URI 的 [Uri](./) 对象；参数指定是否应转义 URI。 |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, **bool**) | 从指定的表示基 URI 的 [Uri](./) 对象和相对 URI 的字符串表示构造一个 [Uri](./) 对象；参数指定是否应转义 URI。 |
|  [Uri](./uri/)(const [String](../string/)\&, [UriKind](../urikind/)) | 构造一个表示指定 URI 的 [Uri](./) 对象；参数指定 URI 类型。 |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&) | 从指定的基 URI 和相对 URI 构造一个 [Uri](./) 对象。 |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | 从指定的基 URI 和相对 URI 构造一个 [Uri](./) 对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 字段

| 字段 | 描述 |
| --- | --- |
| static [SchemeDelimiter](./schemedelimiter/) | 指定用于分隔通信协议方案与 [Uri](./) 地址部分的字符。 |
| static [UriSchemeFile](./urischemefile/) | 指定 [Uri](./) 为文件指针。 |
| static [UriSchemeFtp](./urischemeftp/) | 指定通过文件传输协议访问 [Uri](./)。 |
| static [UriSchemeGopher](./urischemegopher/) | 指定通过 Gopher 协议访问 [Uri](./)。 |
| static [UriSchemeHttp](./urischemehttp/) | 指定通过超文本传输协议访问 [Uri](./)。 |
| static [UriSchemeHttps](./urischemehttps/) | 指定通过安全超文本传输协议访问 [Uri](./)。 |
| static [UriSchemeMailto](./urischememailto/) | 指定 [Uri](./) 为电子邮件地址，并通过简单邮件传输协议访问。 |
| static [UriSchemeNetPipe](./urischemenetpipe/) | 指定通过 [Windows](../../system.windows/) 通信基础设施使用的 NetPipe 方案访问 [Uri](./)。 |
| static [UriSchemeNetTcp](./urischemenettcp/) | 指定通过 [Windows](../../system.windows/) 通信基础设施使用的 NetTcp 方案访问 [Uri](./)。 |
| static [UriSchemeNews](./urischemenews/) | 指定 [Uri](./) 为互联网新闻组，并通过网络新闻传输协议访问。 |
| static [UriSchemeNntp](./urischemenntp/) | 指定 [Uri](./) 为互联网新闻组，并通过网络新闻传输协议访问。 |

## 备注

```cpp
#include "system/smart_ptr.h"
#include "system/uri.h"
#include <iostream>

int main()
{
  const auto uri = System::MakeObject<System::Uri>(u"https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/");

std::cout <<
  "AbsolutePath: " << uri->get_AbsolutePath() << std::endl <<
  "AbsoluteUri: " << uri->get_AbsoluteUri() << std::endl <<
  "Authority: " << uri->get_Authority() << std::endl <<
  "DnsSafeHost: " << uri->get_DnsSafeHost() << std::endl <<
  "Fragment: " << uri->get_Fragment() << std::endl <<
  "Host: " << uri->get_Host() << std::endl <<
  "IdnHost: " << uri->get_IdnHost() << std::endl <<
  "LocalPath: " << uri->get_LocalPath() << std::endl <<
  "OriginalString: " << uri->get_OriginalString() << std::endl <<
  "PathAndQuery: " << uri->get_PathAndQuery() << std::endl <<
  "Port: " << uri->get_Port() << std::endl <<
  "Query: " << uri->get_Query() << std::endl <<
  "Scheme: " << uri->get_Scheme() << std::endl;

  return 0;
}
/*
此代码示例产生以下输出:
AbsolutePath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
AbsoluteUri: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Authority: docs.codeporting.com
DnsSafeHost: docs.codeporting.com
Fragment:
Host: docs.codeporting.com
IdnHost: docs.codeporting.com
LocalPath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
OriginalString: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
PathAndQuery: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Port: 443
Query:
Scheme: https
*/
```

## 另见

* 类 [Object](../object/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)