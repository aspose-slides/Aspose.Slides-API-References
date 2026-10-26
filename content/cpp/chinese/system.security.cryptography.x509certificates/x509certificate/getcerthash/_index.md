---
title: GetCertHash()
second_title: Aspose.Slides for C++ API 参考
description: 获取当前对象的哈希，以字节数组形式。
type: docs
weight: 79
url: /zh/system.security.cryptography.x509certificates/x509certificate/getcerthash/
---
## X509Certificate::GetCertHash() const 方法

获取当前对象的哈希，以字节数组形式。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::GetCertHash() const
```

### 返回值

哈希值。

## X509Certificate::GetCertHash(const HashAlgorithmName\&) const 方法

获取当前对象的哈希，以字节数组形式。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::GetCertHash(const HashAlgorithmName &hash_algorithm) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hash_algorithm | const [HashAlgorithmName](../../../system.security.cryptography/hashalgorithmname/)\& | 哈希算法名称。 |

### 返回值

哈希值。

## 另见

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [X509Certificate](../)
* Struct [HashAlgorithmName](../../../system.security.cryptography/hashalgorithmname/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)