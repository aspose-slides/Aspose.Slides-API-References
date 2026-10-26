---
title: SignData()
second_title: Aspose.Slides for C++ API 参考
description: 计算指定输入值的签名。
type: docs
weight: 183
url: /zh/system.security.cryptography/dsacryptoserviceprovider/signdata/
---
## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&) method

计算指定输入值的签名。

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) 用于读取输入数据。 |

### 返回值

[DSA](../../dsa/) 指定数据的签名。

## DSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&) method

计算指定输入值的签名。

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 用于读取待签名数据的流。 |

### 返回值

[DSA](../../dsa/) 指定数据的签名。

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t) method

计算指定输入值的签名。

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) 用于读取输入数据。 |
| offset | **int32_t** | 输入缓冲区切片的起始索引。 |
| count | **int32_t** | 输入缓冲区切片的大小。 |

### 返回值

[DSA](../../dsa/) 指定数据的签名。

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) method

使用指定的散列算法计算指定数据数组的散列值，并对结果进行签名。

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 输入数据数组。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 散列算法。返回 [DSA](../../dsa/) 指定数据的签名。 |

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) method

使用指定的散列算法计算指定数据数组的散列值，并对结果进行签名。

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 输入数据数组。 |
| offset | **int32_t** | **data** 中的偏移量。 |
| count | **int32_t** | 用作输入数据的字节数。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 散列算法。返回 [DSA](../../dsa/) 指定数据的签名。 |

## DSACryptoServiceProvider::SignData(const StreamPtr\&, const HashAlgorithmName\&) method

使用指定的散列算法计算指定二进制流的散列值，并对结果进行签名。

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 二进制流。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 散列算法。返回 [DSA](../../dsa/) 指定数据的签名。 |

## 另请参见

* 类型定义 [ByteArrayPtr](../../../system/bytearrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [StreamPtr](../../../system/streamptr/)
* 类 [DSACryptoServiceProvider](../)
* 类 [Stream](../../../system.io/stream/)
* 结构体 [HashAlgorithmName](../../hashalgorithmname/)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)