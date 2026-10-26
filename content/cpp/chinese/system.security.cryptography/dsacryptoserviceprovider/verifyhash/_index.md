---
title: VerifyHash()
second_title: Aspose.Slides for C++ API 参考
description: 检查数据签名。
type: docs
weight: 222
url: /zh/system.security.cryptography/dsacryptoserviceprovider/verifyhash/
---
## DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) 方法

检查数据签名。

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 对接收数据计算的哈希。 |
| str | const [String](../../../system/string/)\& | 使用的哈希算法名称。 |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 接收的签名。 |

### 返回值

如果签名有效则返回 True，否则返回 false。

## 另请参见

* 类型定义 [ByteArrayPtr](../../../system/bytearrayptr/)
* 类 [String](../../../system/string/)
* 类 [DSACryptoServiceProvider](../)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)