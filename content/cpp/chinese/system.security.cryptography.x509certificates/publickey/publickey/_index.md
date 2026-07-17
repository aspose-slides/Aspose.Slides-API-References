---
title: PublicKey()
second_title: Aspose.Slides for C++ API 参考
description: 构造函数。
type: docs
weight: 1
url: /zh/system.security.cryptography.x509certificates/publickey/publickey/
---
## PublicKey::PublicKey(const SharedPtr\<Oid\>\&, const SharedPtr\<AsnEncodedData\>\&, const SharedPtr\<AsnEncodedData\>) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::PublicKey::PublicKey(const SharedPtr<Oid> &oid, const SharedPtr<AsnEncodedData> &parameters, const SharedPtr<AsnEncodedData> key_value)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | 表示公共密钥的标识符对象。 |
| parameters | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | ASN.1 编码的公共密钥参数。 |
| key_value | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\> | ASN.1 编码的公共密钥值。 |

## 参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [Oid](../../../system.security.cryptography/oid/)
* 类 [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* 类 [PublicKey](../)
* 命名空间 [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)