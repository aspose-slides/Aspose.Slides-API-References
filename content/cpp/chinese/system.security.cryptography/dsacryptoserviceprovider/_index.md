---
title: DSACryptoServiceProvider
second_title: Aspose.Slides C++ API 参考
description: "DSA 算法的 CSP 形式。此类对象只能使用 System::MakeObject() 函数进行分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类包装为 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 144
url: /zh/system.security.cryptography/dsacryptoserviceprovider/
---
## DSACryptoServiceProvider 类

[DSA](../dsa/) 算法的 CSP 形式。此类对象只能使用 [System::MakeObject()](../../system/makeobject/) 函数进行分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
class DSACryptoServiceProvider : public System::Security::Cryptography::DSA,
                                 public System::Security::Cryptography::ICspAsymmetricAlgorithm
```

## 方法

| 方法 | 描述 |
| --- | --- |
| void [Clear](../asymmetricalgorithm/clear/)() | 释放所有资源。 |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](../dsa/)\> [Create](../dsa/create/)() | 创建默认的 [DSA](../dsa/) 算法实现。 |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](../dsa/)\> [Create](../dsa/create/)(const [String](../../system/string/)\&) | 创建默认的 [DSA](../dsa/) 算法实现。 |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](../dsa/)\> [Create](../dsa/create/)(**int32_t**) | 创建默认的 [DSA](../dsa/) 算法实现，使用指定的密钥大小。 |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](../dsa/)\> [Create](../dsa/create/)(const [DSAParameters](../dsaparameters/)\&) | 创建默认的 [DSA](../dsa/) 算法实现，使用指定的参数。 |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](../dsa/)\> [CreateFromXmlString](../dsa/createfromxmlstring/)(const [String](../../system/string/)\&) | 创建默认的 [DSA](../dsa/) 算法实现，使用指定的 XML 编码参数。 |
| [ByteArrayPtr](../../system/bytearrayptr/) [CreateSignature](./createsignature/)([ByteArrayPtr](../../system/bytearrayptr/)) override | 为指定的数据创建 [DSA](../dsa/) 签名。 |
| void [Dispose](./dispose/)() override | 释放与对象关联的数据。 |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)() | 构造函数。使用默认参数。 |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(const [DSAParameters](../dsaparameters/)\&) | 构造函数。 |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(const [SharedPtr](../../system/sharedptr/)\<[CspParameters](../cspparameters/)\>\&) | 构造函数。未实现。 |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(**int32_t**) | 构造函数。 |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(**int32_t**, const [SharedPtr](../../system/sharedptr/)\<[CspParameters](../cspparameters/)\>\&) | 构造函数。未实现。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| [ByteArrayPtr](../../system/bytearrayptr/) [ExportCspBlob](./exportcspblob/)(**bool**) override | 导出包含密钥信息的 blob。未实现。 |
| [DSAParameters](../dsaparameters/) [ExportParameters](./exportparameters/)(**bool**) override | 导出 CSP 参数。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| void [FromXmlString](../dsa/fromxmlstring/)([String](../../system/string/)) override | 使用 XML 编码参数初始化对象。 |
| [SharedPtr](../../system/sharedptr/)\<[CspKeyContainerInfo](../cspkeycontainerinfo/)\> [get_CspKeyContainerInfo](./get_cspkeycontainerinfo/)() override | 获取一个 [CspKeyContainerInfo](../cspkeycontainerinfo/) 对象。 |
| [String](../../system/string/) [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | 检查与对象关联的密钥交换算法。 |
| **int32_t** [get_KeySize](./get_keysize/)() override | 获取密钥大小。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[KeySizes](../keysizes/)\>\> [get_LegalKeySizes](../asymmetricalgorithm/get_legalkeysizes/)() | 获取允许的密钥大小数组。 |
| **bool** [get_PersistKeyInCsp](./get_persistkeyincsp/)() const | 检查密钥是否持久保存在 CSP 对象中。 |
| **bool** [get_PublicOnly](./get_publiconly/)() const | 检查 CSP 对象中是否仅存在公钥。 |
| [String](../../system/string/) [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | 获取要使用的签名算法。 |
| static **bool** [get_UseMachineKeyStore](./get_usemachinekeystore/)() | 检查密钥是否保存在机器存储而非用户存储中。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| void [ImportCspBlob](./importcspblob/)([ByteArrayPtr](../../system/bytearrayptr/)) override | 导入包含密钥信息的 blob。未实现。 |
| void [ImportParameters](./importparameters/)([DSAParameters](../dsaparameters/)) override | 从数据结构导入所有参数。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
| [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串和 nullptr 情况下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串情形下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定的值。 |
| virtual void [set_KeySize](../asymmetricalgorithm/set_keysize/)(**int32_t**) | 设置密钥大小。 |
| void [set_PersistKeyInCsp](./set_persistkeyincsp/)(**bool**) | 定义密钥是否持久保存在 CSP 对象中。 |
| static void [set_UseMachineKeyStore](./set_usemachinekeystore/)(**bool**) | 定义密钥是否保存在机器存储而非用户存储中。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | 计算指定输入值的签名。 |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | 计算指定输入值的签名。 |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**) | 计算指定输入值的签名。 |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | 使用指定的哈希算法计算指定数据数组的哈希值并对结果进行签名。 |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [HashAlgorithmName](../hashalgorithmname/)\&) | 使用指定的哈希算法计算指定数据数组的哈希值并对结果进行签名。 |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [StreamPtr](../../system/streamptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | 使用指定的哈希算法计算指定二进制流的哈希值并对结果进行签名。 |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | 计算指定输入值的签名。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| [String](../../system/string/) [ToXmlString](../dsa/toxmlstring/)(**bool**) override | 以 XML 格式导出所有参数。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | 检查数据签名。 |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | 验证指定数据的签名是否有效。 |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | 验证指定数据的签名是否有效。 |
| **bool** [VerifyData](./verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | 验证指定二进制流的签名是否有效。 |
| **bool** [VerifyHash](./verifyhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | 检查数据签名。 |
| **bool** [VerifySignature](./verifysignature/)([ByteArrayPtr](../../system/bytearrayptr/), [ByteArrayPtr](../../system/bytearrayptr/)) override | 验证指定数据的 [DSA](../dsa/) 签名。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参阅

* 类 [DSA](../dsa/)
* 类 [ICspAsymmetricAlgorithm](../icspasymmetricalgorithm/)
* 命名空间 [System::Security::Cryptography](../)
* Library [Aspose.Slides](../../)