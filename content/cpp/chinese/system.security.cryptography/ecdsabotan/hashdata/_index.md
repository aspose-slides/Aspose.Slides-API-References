---
title: HashData()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的哈希算法计算指定数据数组的哈希值。
type: docs
weight: 105
url: /zh/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) 方法

使用指定的哈希算法计算指定数据数组的哈希值。

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) 用于哈希。 |
| offset | **int32_t** | **data** 中的偏移量。 |
| count | **int32_t** | 要进行哈希的字节数。 |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | 哈希算法。 |

### 返回值

哈希后的数据。

## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) 方法

使用指定的哈希算法计算指定二进制流的哈希值。

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [StreamPtr](../../../system/streamptr/) | 要进行哈希的二进制流。 |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | 哈希算法。 |

### 返回值

哈希后的数据。

## 另请参阅

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* 类 [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* 命名空间 [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)