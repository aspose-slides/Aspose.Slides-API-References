---
title: VerifyData()
second_title: Aspose.Slides for C++ API 参考
description: 验证指定数据的签名是否有效。
type: docs
weight: 170
url: /zh/system.security.cryptography/ecdsabotan/verifydata/
---
## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) method

验证指定数据的签名是否有效。

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 已签名的数据。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 签名数据。若签名有效返回 true，否则返回 false。 |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&) method

验证指定数据的签名是否有效。

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 已签名的数据。 |
| offset | **int32_t** | 在 **data** 中的偏移量。 |
| count | **int32_t** | 要进行哈希的字节数。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 签名数据。若签名有效返回 true，否则返回 false。 |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&) method

验证指定二进制流的签名是否有效。

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 已签名的数据。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 签名数据。若签名有效返回 true，否则返回 false。 |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method

验证指定数据的签名是否有效。

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 已签名的数据。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 签名数据。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 哈希算法。若签名有效返回 true，否则返回 false。 |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) method

验证指定数据的签名是否有效。

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 已签名的数据。 |
| offset | **int32_t** | 在 **data** 中的偏移量。 |
| count | **int32_t** | 要进行哈希的字节数。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 签名数据。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 哈希算法。若签名有效返回 true，否则返回 false。 |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method

验证指定二进制流的签名是否有效。

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 已签名的数据。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 签名数据。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 哈希算法。若签名有效返回 true，否则返回 false。 |

## 另请参见

* 类型别名 [ByteArrayPtr](../../../system/bytearrayptr/)
* 类型别名 [StreamPtr](../../../system/streamptr/)
* 类 [ECDsaBotan](../)
* 结构体 [HashAlgorithmName](../../hashalgorithmname/)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)