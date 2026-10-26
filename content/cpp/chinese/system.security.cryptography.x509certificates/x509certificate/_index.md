---
title: X509Certificate
second_title: Aspose.Slides C++ API 参考
description: "X.509 v.3 证书。不支持加密证书。仅支持 X509KeyStorageFlags::DefaultKeySet 标志。该类的对象应仅使用 System::MakeObject() 函数分配。不要在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言错误。始终将此类包装在 System::SmartPtr 指针中，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 27
url: /zh/system.security.cryptography.x509certificates/x509certificate/
---
## X509Certificate 类

X.509 v.3 证书。不支持加密证书。仅支持 [X509KeyStorageFlags::DefaultKeySet](../x509keystorageflags/) 标志。此类的对象应仅使用 [System::MakeObject()](../../system/makeobject/) 函数分配。不要在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言错误。始终将此类包装在 [System::SmartPtr](../../system/smartptr/) 指针中，并使用该指针将其作为参数传递给函数。

```cpp
class X509Certificate : public virtual System::Object,
                        public System::IDisposable
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\> [CreateFromCertFile](./createfromcertfile/)(const [String](../../system/string/)\&) | 从指定的 PKCS7 文件创建证书。 |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\> [CreateFromSignedFile](./createfromsignedfile/)(const [String](../../system/string/)\&) | 从指定的已签名文件创建证书。 |
| void [Dispose](./dispose/)() override | 不执行任何操作。 |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 比较两个证书。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 仿真 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 仿真 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/)) const | 使用指定格式将当前对象导出为字节数组。未实现。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/), const [SecureStringPtr](../../system.security/securestringptr/)\&) const | 使用指定格式将当前对象导出为字节数组。未实现。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/), const [String](../../system/string/)\&) const | 使用指定格式将当前对象导出为字节数组。未实现。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅用于内部目的。 |
| IntPtr [get_Handle](./get_handle/)() const | 获取指向 Microsoft Cryptographic API 证书上下文的句柄。 |
| [String](../../system/string/) [get_Issuer](./get_issuer/)() const | 获取颁发 X.509v3 证书的证书颁发机构名称。 |
| [String](../../system/string/) [get_Subject](./get_subject/)() const | 获取证书的主体可辨识名称。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](./getcerthash/)() const | 以字节数组形式获取当前对象的哈希值。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](./getcerthash/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | 以字节数组形式获取当前对象的哈希值。 |
| virtual [String](../../system/string/) [GetCertHashString](./getcerthashstring/)() const | 以十六进制字符串获取当前对象的 [SHA1](../../system.security.cryptography/sha1/) 哈希值。 |
| virtual [String](../../system/string/) [GetCertHashString](./getcerthashstring/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | 以十六进制字符串获取当前对象的 [SHA1](../../system.security.cryptography/sha1/) 哈希值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual [String](../../system/string/) [GetEffectiveDateString](./geteffectivedatestring/)() const | 获取当前证书的生效日期。 |
| virtual [String](../../system/string/) [GetExpirationDateString](./getexpirationdatestring/)() const | 获取当前证书的到期日期。 |
| virtual [String](../../system/string/) [GetFormat](./getformat/)() const | 获取证书格式的名称。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 获取证书哈希码。 |
| virtual [String](../../system/string/) [GetIssuerName](./getissuername/)() const | 获取颁发当前证书的认证机构名称。 |
| virtual [String](../../system/string/) [GetKeyAlgorithm](./getkeyalgorithm/)() const | 以字符串形式获取当前证书的密钥信息。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetKeyAlgorithmParameters](./getkeyalgorithmparameters/)() const | 以字节数组形式获取当前证书的密钥信息。 |
| virtual [String](../../system/string/) [GetKeyAlgorithmParametersString](./getkeyalgorithmparametersstring/)() const | 以十六进制字符串获取当前证书的密钥信息。 |
| virtual [String](../../system/string/) [GetName](./getname/)() const | 获取当前证书颁发给的主体名称。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetPublicKey](./getpublickey/)() const | 以字节数组形式获取证书中的公钥。 |
| virtual [String](../../system/string/) [GetPublicKeyString](./getpublickeystring/)() const | 以十六进制字符串获取证书中的公钥。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetRawCertData](./getrawcertdata/)() const | 以字节数组形式获取证书的原始数据。 |
| virtual [String](../../system/string/) [GetRawCertDataString](./getrawcertdatastring/)() const | 以十六进制字符串获取证书的原始数据。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetSerialNumber](./getserialnumber/)() const | 以字节数组形式获取证书的序列号。 |
| virtual [String](../../system/string/) [GetSerialNumberString](./getserialnumberstring/)() const | 以十六进制字符串获取证书的序列号。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual void [Import](./import/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 从指定的证书文件导入信息。未实现。 |
| virtual void [Import](./import/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 从指定的证书文件导入信息。未实现。 |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 从指定的证书数据导入信息。未实现。 |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 从指定的证书数据导入信息。未实现。 |
| virtual void [Import](./import/)(const [String](../../system/string/)\&) | 从指定的证书文件导入信息。未实现。 |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | 从指定的证书数据导入信息。未实现。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
| [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| [X509Certificate](./)\& [operator=](./operator_equal/)(const [X509Certificate](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串和 nullptr 情形的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串情形的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [Reset](./reset/)() | 重置证书状态。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](./tostring/)(**bool**) const | 以文本格式返回证书信息。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | 以文本格式返回证书信息。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| [X509Certificate](./x509certificate/)(const [X509Certificate](./)\&) |  |
| [X509Certificate](./x509certificate/)() | 构造函数。 |
| [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | 构造函数。 |
| [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&) | 构造函数。 |
| [X509Certificate](./x509certificate/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\>\&) | 构造函数。 |
| [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | 构造函数。 |
| [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | 构造函数。 |
| [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 构造函数。 |
| [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | 构造函数。 |
| [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 构造函数。 |
| [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 构造函数。 |
| [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 构造函数。 |
| [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 构造函数。 |
| [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 构造函数。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 类型定义

| 类型定义 | 描述 |
| --- | --- |
| [Ptr](./ptr/) | 指针类型。 |

## 另请参阅

* 类 [Object](../../system/object/)
* 类 [IDisposable](../../system/idisposable/)
* 命名空间 [System::Security::Cryptography::X509Certificates](../)
* 库 [Aspose.Slides](../../)