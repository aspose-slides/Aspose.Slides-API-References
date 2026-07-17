---
title: SignHash()
second_title: Aspose.Slides C++ API 参考
description: 计算指定输入值的签名。
type: docs
weight: 196
url: /zh/system.security.cryptography/dsacryptoserviceprovider/signhash/
---
## DSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) 方法

计算指定输入值的签名。

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 要签名的数据的哈希值。 |
| str | const [String](../../../system/string/)\& | 用于创建哈希的哈希算法标识符。 |

### 返回值

[DSA](../../dsa/) 指定数据的签名。

## 另见

* 类型定义 [ByteArrayPtr](../../../system/bytearrayptr/)
* 类 [String](../../../system/string/)
* 类 [DSACryptoServiceProvider](../)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)