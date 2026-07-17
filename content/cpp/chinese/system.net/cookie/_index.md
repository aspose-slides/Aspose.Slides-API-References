---
title: Cookie
second_title: Aspose.Slides for C++ API 参考
description: "表示一个 HTTP cookie。此类的对象应仅使用 System::MakeObject() 函数分配。不要在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装成 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 1
url: /zh/system.net/cookie/
---
## Cookie 类

表示一个 HTTP cookie。此类的对象应仅通过 [System::MakeObject()](../../system/makeobject/) 函数分配。不要在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言失败。始终将此类包装成 [System::SmartPtr](../../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
class Cookie : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Cookie](./)\> [Clone](./clone/)() | 创建当前实例的副本。 |
|  [Cookie](./cookie/)() | 构造一个新实例。 |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/)) | 构造一个新实例。 |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 构造一个新实例。 |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 构造一个新实例。 |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中即使根据 IEC 60559:1989 标准 NaN 不等于任何值（包括 NaN），两个 NaN 仍被视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中即使根据 IEC 60559:1989 标准 NaN 不等于任何值（包括 NaN），两个 NaN 仍被视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [String](../../system/string/) [get_Comment](./get_comment/)() const | 获取 'Comment' 属性的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_CommentUri](./get_commenturi/)() const | 获取 'CommentURL' 属性的值。 |
| **bool** [get_Discard](./get_discard/)() const | 获取 'Discard' 属性的值。 |
| [String](../../system/string/) [get_Domain](./get_domain/)() const | 获取 'Domain' 属性的值。 |
| **bool** [get_DomainImplicit](./get_domainimplicit/)() | 获取指示域是否隐式的值。 |
| [String](../../system/string/) [get_DomainKey](./get_domainkey/)() const | 返回域键。 |
| **bool** [get_Expired](./get_expired/)() | 获取指示 cookie 是否已过期的值。 |
| [DateTime](../../system/datetime/) [get_Expires](./get_expires/)() | 获取 'Expires' 属性的值。 |
| **bool** [get_HttpOnly](./get_httponly/)() const | 获取 'HttpOnly' 属性的值。 |
| [String](../../system/string/) [get_Name](./get_name/)() const | 获取 cookie 的名称。 |
| [String](../../system/string/) [get_Path](./get_path/)() const | 获取 'Path' 属性的值。 |
| **bool** [get_Plain](./get_plain/)() const | 返回指示 cookie 规范是否为 'Plain' 的值。 |
| [String](../../system/string/) [get_Port](./get_port/)() const | 获取 'Port' 属性的值。 |
| [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\> [get_PortList](./get_portlist/)() const | 返回 'Port' 属性值的集合。 |
| **bool** [get_Secure](./get_secure/)() const | 获取 'Secure' 属性的值。 |
| [DateTime](../../system/datetime/) [get_TimeStamp](./get_timestamp/)() const | 返回 cookie 创建的时间。 |
| [String](../../system/string/) [get_Value](./get_value/)() const | 获取 cookie 的值。 |
| [CookieVariant](../cookievariant/) [get_Variant](./get_variant/)() const | 获取 cookie 的规范。 |
| **int32_t** [get_Version](./get_version/)() const | 获取 '[Version](../../system/version/)' 属性的值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的类似实现。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| **bool** [InternalSetName](./internalsetname/)([String](../../system/string/)) | 此方法由其他方法调用以设置方法名称。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定的值。 |
| void [set_Comment](./set_comment/)([String](../../system/string/)) | 设置 'Comment' 属性的值。 |
| void [set_CommentUri](./set_commenturi/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 设置 'CommentURL' 属性的值。 |
| void [set_Discard](./set_discard/)(**bool**) | 设置 'Discard' 属性的值。 |
| void [set_Domain](./set_domain/)([String](../../system/string/)) | 设置 'Domain' 属性的值。 |
| void [set_DomainImplicit](./set_domainimplicit/)(**bool**) | 设置指示域是否隐式的值。 |
| void [set_Expired](./set_expired/)(**bool**) | 设置指示 cookie 是否已过期的值。 |
| void [set_Expires](./set_expires/)([DateTime](../../system/datetime/)) | 设置 'Expires' 属性的值。 |
| void [set_HttpOnly](./set_httponly/)(**bool**) | 设置 'HttpOnly' 属性的值。 |
| void [set_Name](./set_name/)([String](../../system/string/)) | 设置 cookie 的名称。 |
| void [set_Path](./set_path/)([String](../../system/string/)) | 设置 'Path' 属性的值。 |
| void [set_Port](./set_port/)([String](../../system/string/)) | 设置 'Port' 属性的值。 |
| void [set_Secure](./set_secure/)(**bool**) | 设置 'Secure' 属性的值。 |
| void [set_Value](./set_value/)([String](../../system/string/)) | 设置 cookie 的值。 |
| void [set_Variant](./set_variant/)([CookieVariant](../cookievariant/)) | 设置 cookie 的规范。 |
| void [set_Version](./set_version/)(**int32_t**) | 设置 '[Version](../../system/version/)' 属性的值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| [String](../../system/string/) [ToServerString](./toserverstring/)() | 将当前实例序列化为字符串表示。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| **bool** [VerifySetDefaults](./verifysetdefaults/)([CookieVariant](../cookievariant/), [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [String](../../system/string/), **bool**, **bool**) | 验证并设置默认属性的值。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 字段

| 字段 | 描述 |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | 'Comment' 属性的名称。 |
| static [CommentUrlAttributeName](./commenturlattributename/) | 'CommentURL' 属性的名称。 |
| static [DiscardAttributeName](./discardattributename/) | 'Discard' 属性的名称。 |
| static [DomainAttributeName](./domainattributename/) | 'Domain' 属性的名称。 |
| static [EqualsLiteral](./equalsliteral/) | 用于分隔属性名称和值的分隔符。 |
| static [ExpiresAttributeName](./expiresattributename/) | 'Expires' 属性的名称。 |
| static [HttpOnlyAttributeName](./httponlyattributename/) | 'HttpOnly' 属性的名称。 |
| static [MaxAgeAttributeName](./maxageattributename/) | 'Max-Age' 属性的名称。 |
| static [MaxSupportedVersion](./maxsupportedversion/) | 支持的最大版本。 |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | 支持的最大版本的字符串表示。 |
| static [PathAttributeName](./pathattributename/) | 'Path' 属性的名称。 |
| static [PortAttributeName](./portattributename/) | 'Port' 属性的名称。 |
| static [PortSplitDelimiters](./portsplitdelimiters/) | 包含 'Port' 属性值分隔符的数组。 |
| static [QuotesLiteral](./quotesliteral/) | 用于包装属性各部分的符号。 |
| static [ReservedToName](./reservedtoname/) | 为 cookie 名称保留的值。 |
| static [ReservedToValue](./reservedtovalue/) | 为 cookie 值保留的值。 |
| static [SecureAttributeName](./secureattributename/) | 'Secure' 属性的名称。 |
| static [SeparatorLiteral](./separatorliteral/) | 属性分隔符。 |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | 特殊属性名称的前缀。 |
| static [VersionAttributeName](./versionattributename/) | '[Version](../../system/version/)' 属性的名称。 |

## 另见

* 类 [Object](../../system/object/)
* 命名空间 [System::Net](../)
* 库 [Aspose.Slides](../../)