---
title: GetCertHashString()
second_title: Aspose.Slides C++ API 参考
description: 获取当前对象的 SHA1 哈希，以十六进制字符串形式。
type: docs
weight: 92
url: /zh/system.security.cryptography.x509certificates/x509certificate/getcerthashstring/
---
## X509Certificate::GetCertHashString() const 方法

获取当前对象的 [SHA1](../../../system.security.cryptography/sha1/) 哈希，以十六进制字符串形式。

```cpp
virtual String System::Security::Cryptography::X509Certificates::X509Certificate::GetCertHashString() const
```

### 返回值

十六进制字符串。

## X509Certificate::GetCertHashString(const HashAlgorithmName\&) const 方法

获取当前对象的 [SHA1](../../../system.security.cryptography/sha1/) 哈希，以十六进制字符串形式。

```cpp
virtual String System::Security::Cryptography::X509Certificates::X509Certificate::GetCertHashString(const HashAlgorithmName &hash_algorithm) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hash_algorithm | const [HashAlgorithmName](../../../system.security.cryptography/hashalgorithmname/)\& | 哈希算法名称。 |

### 返回值

十六进制字符串。

## 参见

* 类 [String](../../../system/string/)
* 类 [X509Certificate](../)
* 结构体 [HashAlgorithmName](../../../system.security.cryptography/hashalgorithmname/)
* 命名空间 [System::Security::Cryptography::X509Certificates](../../)
* 库 [Aspose.Slides](../../../)