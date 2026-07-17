---
title: VerifyData()
second_title: Aspose.Slides for C++ API 参考
description: 检查数据签名。
type: docs
weight: 209
url: /zh/system.security.cryptography/dsacryptoserviceprovider/verifydata/
---
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) 方法

检查数据签名。

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const ByteArrayPtr &signature)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 用于检查签名的 [Data](../../../system.data/)。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 接收到的签名。 |

### 返回值

如果签名有效返回 true，否则返回 false。

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) 方法

验证指定数据的签名是否有效。

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 已签名的数据。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 签名数据。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 哈希算法。若签名有效返回 true，否则返回 false。 |

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) 方法

验证指定数据的签名是否有效。

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 已签名的数据。 |
| offset | **int32_t** | **data** 中的偏移量。 |
| count | **int32_t** | 要进行哈希的字节数。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 签名数据。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 哈希算法。若签名有效返回 true，否则返回 false。 |

## DSACryptoServiceProvider::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) 方法

验证指定二进制流的签名是否有效。

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 已签名的数据。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 签名数据。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 哈希算法。若签名有效返回 true，否则返回 false。 |

## 另请参阅

* 类型定义 [ByteArrayPtr](../../../system/bytearrayptr/)
* 类型定义 [StreamPtr](../../../system/streamptr/)
* 类 [DSACryptoServiceProvider](../)
* 结构 [HashAlgorithmName](../../hashalgorithmname/)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)