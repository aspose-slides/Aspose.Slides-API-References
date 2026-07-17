---
title: CacheControlHeaderValue
second_title: Aspose.Slides for C++ API 参考
description: "表示 'Cache-Control' 头部的值。此类的对象应仅使用 System::MakeObject() 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言错误。始终将此类包装为 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 14
url: /zh/system.net.http.headers/cachecontrolheadervalue/
---
## CacheControlHeaderValue 类

表示 'Cache-Control' 头部的值。此类的对象应仅使用 [System::MakeObject()](../../system/makeobject/) 函数进行分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言错误。始终将此类包装为 [System::SmartPtr](../../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
class CacheControlHeaderValue : public System::ICloneable
```

## 方法

| 方法 | 描述 |
| --- | --- |
|  [CacheControlHeaderValue](./cachecontrolheadervalue/)() | 构造一个新实例。 |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Extensions](./get_extensions/)() | 返回缓存扩展标记的集合。 |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxAge](./get_maxage/)() | 获取以秒为单位的最大年龄值，该值决定客户端在此期间接受响应的时间。 |
| **bool** [get_MaxStale](./get_maxstale/)() | 获取决定客户端是否接受已过期响应的值。 |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxStaleLimit](./get_maxstalelimit/)() | 获取以秒为单位的值，该值决定客户端在此期间接受已过期响应的时间。 |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MinFresh](./get_minfresh/)() | 获取决定新鲜度存活时间的值。 |
| **bool** [get_MustRevalidate](./get_mustrevalidate/)() | 获取决定服务器在缓存条目变陈旧时是否需要重新验证的值。 |
| **bool** [get_NoCache](./get_nocache/)() | 获取决定客户端是否接受缓存响应的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_NoCacheHeaders](./get_nocacheheaders/)() | 获取 'Cache-Control' 头部中 'no-cache' 指令的字段名集合。 |
| **bool** [get_NoStore](./get_nostore/)() | 获取决定缓存是否不得存储 HTTP 请求或响应任何部分的值。 |
| **bool** [get_NoTransform](./get_notransform/)() | 获取决定缓存或代理不得更改实体正文任何部分的值。 |
| **bool** [get_OnlyIfCached](./get_onlyifcached/)() | 获取决定客户端必须仅使用缓存条目的值。 |
| **bool** [get_Private](./get_private/)() | 获取决定 HTTP 响应消息或其部分是针对单个用户且不得由共享缓存缓存的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_PrivateHeaders](./get_privateheaders/)() | 获取 'Cache-Control' 头部中 'private' 指令的字段名集合。 |
| **bool** [get_ProxyRevalidate](./get_proxyrevalidate/)() | 获取决定服务器在共享用户代理缓存中缓存条目变陈旧时是否需要重新验证的值。 |
| **bool** [get_Public](./get_public/)() | 获取决定 HTTP 响应是否可以被任何缓存缓存的值。 |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_SharedMaxAge](./get_sharedmaxage/)() | 获取共享最大年龄值（秒），该值会覆盖共享缓存中 'Cache-Control' 头部的 'max-age' 指令或 'Expires' 头部。 |
| static **int32_t** [GetCacheControlLength](./getcachecontrollength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | 将传入的字符串从指定索引转换为 [CacheControlHeaderValue](./) 类的实例。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的复制构造。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | 将传入的字符串转换为 [CacheControlHeaderValue](./) 类的实例。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数降低指定值。 |
| void [set_MaxAge](./set_maxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | 设置以秒为单位的最大年龄值，该值决定客户端在此期间接受响应的时间。 |
| void [set_MaxStale](./set_maxstale/)(**bool**) | 设置决定客户端是否接受已过期响应的值。 |
| void [set_MaxStaleLimit](./set_maxstalelimit/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | 设置以秒为单位的值，该值决定客户端在此期间接受已过期响应的时间。 |
| void [set_MinFresh](./set_minfresh/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | 设置决定新鲜度存活时间的值。 |
| void [set_MustRevalidate](./set_mustrevalidate/)(**bool**) | 设置决定服务器在缓存条目变陈旧时是否需要重新验证的值。 |
| void [set_NoCache](./set_nocache/)(**bool**) | 设置决定客户端是否接受缓存响应的值。 |
| void [set_NoStore](./set_nostore/)(**bool**) | 设置决定缓存是否不得存储 HTTP 请求或响应任何部分的值。 |
| void [set_NoTransform](./set_notransform/)(**bool**) | 设置决定缓存或代理不得更改实体正文任何部分的值。 |
| void [set_OnlyIfCached](./set_onlyifcached/)(**bool**) | 设置决定客户端必须仅使用缓存条目的值。 |
| void [set_Private](./set_private/)(**bool**) | 设置决定 HTTP 响应消息或其部分是针对单个用户且不得由共享缓存缓存的值。 |
| void [set_ProxyRevalidate](./set_proxyrevalidate/)(**bool**) | 设置决定服务器在共享用户代理缓存中缓存条目变陈旧时是否需要重新验证的值。 |
| void [set_Public](./set_public/)(**bool**) | 设置决定 HTTP 响应是否可以被任何缓存缓存的值。 |
| void [set_SharedMaxAge](./set_sharedmaxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | 设置共享最大年龄值（秒），该值会覆盖共享缓存中 'Cache-Control' 头部的 'max-age' 指令或 'Expires' 头部。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | 尝试将传入的字符串转换为 [CacheControlHeaderValue](./) 类的实例。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 参见

* 类 [ICloneable](../../system/icloneable/)
* 命名空间 [System::Net::Http::Headers](../)
* 库 [Aspose.Slides](../../)