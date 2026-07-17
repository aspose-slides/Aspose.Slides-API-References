---
title: X509KeyUsageExtension
second_title: Aspose.Slides for C++ API 参考
description: "用于保存密钥使用的额外信息的扩展对象。此类的对象只能使用 System::MakeObject() 函数分配。不要在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类包装在 System::SmartPtr 指针中，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 196
url: /zh/system.security.cryptography.x509certificates/x509keyusageextension/
---
## X509KeyUsageExtension 类

用于保存密钥使用的额外信息的扩展对象。此类的对象只能使用 [System::MakeObject()](../../system/makeobject/) 函数分配。不要在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装在 [System::SmartPtr](../../system/smartptr/) 指针中，并使用该指针将其作为参数传递给函数。

```cpp
class X509KeyUsageExtension : public System::Security::Cryptography::X509Certificates::X509Extension
```

## 方法

| 方法 | 描述 |
| --- | --- |
|  [AsnEncodedData](../../system.security.cryptography/asnencodeddata/asnencodeddata/)(const [SharedPtr](../../system/sharedptr/)\<[AsnEncodedData](../../system.security.cryptography/asnencodeddata/)\>\&) | 复制构造函数。 |
|  [AsnEncodedData](../../system.security.cryptography/asnencodeddata/asnencodeddata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | 构造函数。 |
|  [AsnEncodedData](../../system.security.cryptography/asnencodeddata/asnencodeddata/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../../system.security.cryptography/oid/)\>\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | 构造函数。 |
|  [AsnEncodedData](../../system.security.cryptography/asnencodeddata/asnencodeddata/)(const [String](../../system/string/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | 构造函数。 |
| void [CopyFrom](./copyfrom/)(const [SharedPtr](../../system/sharedptr/)\<[AsnEncodedData](../../system.security.cryptography/asnencodeddata/)\>\&) override | 从其他对象复制扩展数据。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [String](../../system/string/) [Format](../../system.security.cryptography/asnencodeddata/format/)(**bool**) const | 以人类可读的形式格式化数据。 |
| **bool** [get_Critical](../x509extension/get_critical/)() const | 检查扩展是否关键。 |
| [X509KeyUsageFlags](../x509keyusageflags/) [get_KeyUsages](./get_keyusages/)() | 获取密钥使用情况。 |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../../system.security.cryptography/oid/)\> [get_Oid](../../system.security.cryptography/asnencodeddata/get_oid/)() const | 获取编码数据的对象标识符。 |
| [ByteArrayPtr](../../system/bytearrayptr/) [get_RawData](../../system.security.cryptography/asnencodeddata/get_rawdata/)() const | 获取原始编码数据。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。支持自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。支持自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，仅初始化新对象并支持子类的复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并支持子类的复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 用 nullptr 对值类型对象进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定值。 |
| void [set_Critical](../x509extension/set_critical/)(**bool**) | 定义扩展是否关键。 |
| void [set_Oid](../../system.security.cryptography/asnencodeddata/set_oid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../../system.security.cryptography/oid/)\>\&) | 设置编码数据的对象标识符。 |
| void [set_RawData](../../system.security.cryptography/asnencodeddata/set_rawdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | 设置原始编码数据。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。支持将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
|  [X509Extension](../x509extension/x509extension/)(const [SharedPtr](../../system/sharedptr/)\<[AsnEncodedData](../../system.security.cryptography/asnencodeddata/)\>\&, **bool**) | 构造函数。 |
|  [X509Extension](../x509extension/x509extension/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../../system.security.cryptography/oid/)\>\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, **bool**) | 构造函数。 |
|  [X509Extension](../x509extension/x509extension/)(const [String](../../system/string/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, **bool**) | 构造函数。 |
|  [X509KeyUsageExtension](./x509keyusageextension/)() | 默认构造函数。 |
|  [X509KeyUsageExtension](./x509keyusageextension/)(const [SharedPtr](../../system/sharedptr/)\<[AsnEncodedData](../../system.security.cryptography/asnencodeddata/)\>\&, **bool**) | 构造函数。 |
|  [X509KeyUsageExtension](./x509keyusageextension/)([X509KeyUsageFlags](../x509keyusageflags/), **bool**) | 构造函数。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 参见

* 类 [X509Extension](../x509extension/)
* 命名空间 [System::Security::Cryptography::X509Certificates](../)
* 库 [Aspose.Slides](../../)