---
title: VerifySignature()
second_title: Aspose.Slides for C++ API 参考
description: 验证指定数据的 DSA 签名。
type: docs
weight: 118
url: /zh/system.security.cryptography/dsacryptoserviceprovider/verifysignature/
---
## DSACryptoServiceProvider::VerifySignature(ByteArrayPtr, ByteArrayPtr) 方法

验证指定数据的 [DSA](../../dsa/) 签名。

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) 使用 **rgb_signature** 签名。 |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../../dsa/) 签名。 |

### 返回值

true - 如果 **rgb_signature** 与在 **rgb_hash** 上计算的 [DSA](../../dsa/) 签名匹配；否则 - false。

## 另请参见

* 类型定义 [ByteArrayPtr](../../../system/bytearrayptr/)
* 类 [DSACryptoServiceProvider](../)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)