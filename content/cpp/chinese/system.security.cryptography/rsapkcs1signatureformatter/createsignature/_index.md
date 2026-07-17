---
title: CreateSignature()
second_title: Aspose.Slides C++ API 参考
description: 对数据进行签名。
type: docs
weight: 27
url: /zh/system.security.cryptography/rsapkcs1signatureformatter/createsignature/
---
## RSAPKCS1SignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) 方法


对数据进行签名。

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::RSAPKCS1SignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 用于签名的数据的哈希。 |

### 返回值

已计算的签名。

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [RSAPKCS1SignatureFormatter](../)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)