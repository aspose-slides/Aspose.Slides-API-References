---
title: SignData()
second_title: Aspose.Slides for C++ API 参考
description: 计算指定输入值的签名。
type: docs
weight: 183
url: /zh/system.security.cryptography/rsacryptoserviceprovider/signdata/
---
## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&) 方法


计算指定输入值的签名。

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) 从中读取输入数据。 |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 要使用的哈希算法。 |

### 返回值

[RSA](../../rsa/) 指定数据的签名。

## RSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Object\>\&) 方法


计算指定输入值的签名。

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream, const SharedPtr<Object> &halg)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 用于读取被签名数据的流。 |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 要使用的哈希算法。 |

### 返回值

[RSA](../../rsa/) 指定数据的签名。

## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const SharedPtr\<Object\>\&) 方法


计算指定输入值的签名。

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count, const SharedPtr<Object> &halg)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) 从中读取输入数据。 |
| offset | **int32_t** | 输入缓冲区切片的起始索引。 |
| count | **int32_t** | 输入缓冲区切片的大小。 |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 要使用的哈希算法。 |

### 返回值

[RSA](../../rsa/) 指定数据的签名。

## 另请参阅

* 类型定义 [ByteArrayPtr](../../../system/bytearrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [RSACryptoServiceProvider](../)
* 类 [Stream](../../../system.io/stream/)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)