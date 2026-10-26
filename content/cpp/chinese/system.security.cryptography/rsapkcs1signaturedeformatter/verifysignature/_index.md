---
title: VerifySignature()
second_title: Aspose.Slides for C++ API 参考
description: 验证数据哈希的签名。
type: docs
weight: 40
url: /zh/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) 方法

验证数据哈希的签名。

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 针对数据计算的哈希。 |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 接收的数据签名。 |

### 返回值

如果签名有效则返回 true，否则返回 false。

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [RSAPKCS1SignatureDeformatter](../)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)