---
title: VerifySignature()
second_title: Aspose.Slides for C++ API 参考
description: 验证指定数据的 DSA 签名。
type: docs
weight: 14
url: /zh/system.security.cryptography/dsa/verifysignature/
---
## DSA::VerifySignature(ByteArrayPtr, ByteArrayPtr) 方法

验证指定数据的 [DSA](../) 签名。

```cpp
virtual bool System::Security::Cryptography::DSA::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) 使用 **rgb_signature** 签名。 |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../) 签名。 |

### 返回值

true - 如果 **rgb_signature** 与在 **rgb_hash** 上计算的 [DSA](../) 签名匹配，则为 true；否则为 false。

## 另请参阅

* 类型定义 [ByteArrayPtr](../../../system/bytearrayptr/)
* 类 [DSA](../)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)