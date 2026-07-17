---
title: X509KeyUsageFlags
second_title: Aspose.Slides C++ API 参考
description: 定义证书密钥的使用方式。
type: docs
weight: 274
url: /zh/system.security.cryptography.x509certificates/x509keyusageflags/
---
## X509KeyUsageFlags enum

定义证书密钥的使用方式。

```cpp
enum class X509KeyUsageFlags : int32_t
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | 0 | 无密钥使用参数。 |
| EncipherOnly | 1 | 密钥只能用于加密。 |
| CrlSign | 2 | 密钥可用于对证书吊销列表签名。 |
| KeyCertSign | 4 | 密钥可用于签署证书。 |
| KeyAgreement | 8 | 密钥可用于确定密钥协商。 |
| DataEncipherment | 16 | 密钥可用于数据加密。 |
| KeyEncipherment | 32 | 密钥可用于密钥加密。 |
| NonRepudiation | 64 | 密钥可用于身份验证。 |
| DigitalSignature | 128 | 密钥可用作数字签名。 |
| DecipherOnly | 32768 | 密钥只能用于解密。 |

## 另请参阅

* 命名空间 [System::Security::Cryptography::X509Certificates](../)
* 库 [Aspose.Slides](../../)