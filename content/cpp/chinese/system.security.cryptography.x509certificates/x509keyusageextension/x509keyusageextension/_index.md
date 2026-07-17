---
title: X509KeyUsageExtension()
second_title: Aspose.Slides C++ API 参考
description: 默认构造函数。
type: docs
weight: 1
url: /zh/system.security.cryptography.x509certificates/x509keyusageextension/x509keyusageextension/
---
## X509KeyUsageExtension::X509KeyUsageExtension() 构造函数

默认构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension()
```

## X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr\<AsnEncodedData\>\&, bool) 构造函数

构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr<AsnEncodedData> &encoded_key_usage, bool critical)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encoded_key_usage | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | 密钥用法的编码数据。 |
| critical | **bool** | 关键性标志。 |

## X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags, bool) 构造函数

构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags key_usages, bool critical)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| key_usages | [X509KeyUsageFlags](../../x509keyusageflags/) | 密钥用法。 |
| critical | **bool** | 关键性标志。 |

## 另请参见

* 枚举 [X509KeyUsageFlags](../../x509keyusageflags/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [X509KeyUsageExtension](../)
* 类 [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* 命名空间 [System::Security::Cryptography::X509Certificates](../../)
* 库 [Aspose.Slides](../../../)