---
title: VerifyData()
second_title: Aspose.Slides for C++ API 参考
description: 验证指定数据的签名是否有效。
type: docs
weight: 92
url: /zh/system.security.cryptography/dsa/verifydata/
---
## DSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) 方法

验证指定数据的签名是否有效。

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 已签名的数据。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 签名数据。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 哈希算法。如果签名有效则返回 true，否则返回 false。 |

## DSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) 方法

验证指定数据的签名是否有效。

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 已签名的数据。 |
| offset | **int32_t** | 在 **data** 中的偏移。 |
| count | **int32_t** | 要散列的字节数。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 签名数据。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 哈希算法。如果签名有效则返回 true，否则返回 false。 |

## DSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) 方法

验证指定二进制流的签名是否有效。

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 已签名的数据。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 签名数据。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 哈希算法。如果签名有效则返回 true，否则返回 false。 |

## 另见

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* 类 [DSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* 命名空间 [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)