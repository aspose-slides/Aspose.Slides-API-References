---
title: IPAddress
second_title: Aspose.Slides for C++ API 参考
description: "表示 IP 地址。此类的对象只能使用 System::MakeObject() 函数进行分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 326
url: /zh/system.net/ipaddress/
---
## IPAddress 类


表示 IP 地址。此类的对象只能使用 [System::MakeObject()](../../system/makeobject/) 函数进行分配。切勿在栈上或使用 operator new 创建此类型的实例，因为它会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
class IPAddress : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [System::Net::Sockets::AddressFamily](../../system.net.sockets/addressfamily/) [get_AddressFamily](./get_addressfamily/)() | 返回地址族。 |
| **bool** [get_IsIPv4MappedToIPv6](./get_isipv4mappedtoipv6/)() | 返回一个值，指示该地址是否为 IPv4 地址且已映射到 IPv6 地址。 |
| **bool** [get_IsIPv6LinkLocal](./get_isipv6linklocal/)() | 返回一个值，指示该地址是否为 IPv6 链路本地地址。 |
| **bool** [get_IsIPv6Multicast](./get_isipv6multicast/)() | 返回一个值，指示该地址是否为全局 IPv6 多播地址。 |
| **bool** [get_IsIPv6SiteLocal](./get_isipv6sitelocal/)() | 返回一个值，指示该地址是否为 IPv6 站点本地地址。 |
| **bool** [get_IsIPv6Teredo](./get_isipv6teredo/)() | 返回一个值，指示该地址是否为 IPv6 Teredo 地址。 |
| **int64_t** [get_ScopeId](./get_scopeid/)() | 获取 IPv6 地址的作用域标识符。 |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetAddressBytes](./getaddressbytes/)() | 返回 IP 地址的字节数组。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | 返回指向实现的指针。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| static **int64_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int64_t**) | 将指定的主机字节序转换为相应的网络字节序。 |
| static **int32_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int32_t**) | 将指定的主机字节序转换为相应的网络字节序。 |
| static **int16_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int16_t**) | 将指定的主机字节序转换为相应的网络字节序。 |
|  [IPAddress](./ipaddress/)(**int64_t**) | 构造一个新实例。 |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int64_t**) | 构造一个新实例。 |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 构造一个新实例。 |
|  [IPAddress](./ipaddress/)() | 构造一个新实例。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| static **bool** [IsLoopback](./isloopback/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>) | 返回一个值，指示指定的地址是否为环回地址。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv4](./maptoipv4/)() | 将地址映射到 IPv4 地址。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv6](./maptoipv6/)() | 将地址映射到 IPv6 地址。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
| static **int64_t** [NetworkToHostOrder](./networktohostorder/)(**int64_t**) | 将指定的网络字节序转换为相应的主机字节序。 |
| static **int32_t** [NetworkToHostOrder](./networktohostorder/)(**int32_t**) | 将指定的网络字节序转换为相应的主机字节序。 |
| static **int16_t** [NetworkToHostOrder](./networktohostorder/)(**int16_t**) | 将指定的网络字节序转换为相应的主机字节序。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，仅初始化新对象并允许复制构造子类。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许复制构造子类。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [Parse](./parse/)([String](../../system/string/)) | 将传入的字符串转换为 [IPAddress](./) 类的实例。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串和 nullptr 情形下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串情形下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定值。 |
| void [set_ScopeId](./set_scopeid/)(**int64_t**) | 设置 IPv6 地址的作用域标识符。 |
| void [SetImpl](./setimpl/)([ImplPtr](./implptr/)) | 设置指向实现的指针。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>\&) | 尝试将传入的字符串转换为 [IPAddress](./) 类的实例。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 字段

| 字段 | 描述 |
| --- | --- |
| static [Any](./any/) | 指示服务器必须监听所有网络接口的 IPv4 地址。 |
| static [Broadcast](./broadcast/) | IPv4 广播地址。 |
| static [IPv6Any](./ipv6any/) | 指示服务器必须监听所有网络接口的 IPv6 地址。 |
| static [IPv6Loopback](./ipv6loopback/) | IPv6 环回地址。 |
| static [IPv6None](./ipv6none/) | 指示服务器不应监听任何网络接口的 IPv6 地址。 |
| static [Loopback](./loopback/) | IPv4 环回地址。 |
| static [None](./none/) | 指示服务器不应监听任何网络接口的 IPv4 地址。 |

## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [ImplPtr](./implptr/) | 指向实现类型的指针。 |

## 另请参见

* 类 [Object](../../system/object/)
* 命名空间 [System::Net](../)
* 库 [Aspose.Slides](../../)