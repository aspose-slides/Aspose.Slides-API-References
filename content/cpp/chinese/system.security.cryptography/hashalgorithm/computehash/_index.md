---
title: ComputeHash()
second_title: Aspose.Slides C++ API 参考
description: 对缓冲区进行哈希。
type: docs
weight: 14
url: /zh/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) 方法

对缓冲区进行哈希。

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 源缓冲区。 |

### 返回值

计算得到的哈希值。

## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) 方法

对缓冲区切片进行哈希。

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 源缓冲区。 |
| offset | int | 源缓冲区中的偏移。 |
| count | int | 要从源缓冲区使用的字节数。 |

### 返回值

计算得到的哈希值。

## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) 方法

读取流直至结束并计算读取数据的哈希。

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> const\& | 要读取数据的流。 |

### 返回值

对整个流数据计算得到的哈希值。

## 另见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HashAlgorithm](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)