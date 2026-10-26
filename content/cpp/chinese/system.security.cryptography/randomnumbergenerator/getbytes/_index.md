---
title: GetBytes()
second_title: Aspose.Slides for C++ API 参考
description: 用随机字节填充现有数组元素。
type: docs
weight: 14
url: /zh/system.security.cryptography/randomnumbergenerator/getbytes/
---
## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>) 方法

用随机字节填充现有数组元素。

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要填充的字节数组。 |

## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>, int, int) 方法

用随机字节填充现有数组切片。

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes, int offset, int count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要填充切片的字节数组。 |
| offset | int | 切片起始索引。 |
| count | int | 切片大小。 |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>) 方法

用随机字节填充现有数组视图元素。

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | 要填充的字节数组视图。 |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>, int, int) 方法

用随机字节填充现有数组视图切片。

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes, int offset, int count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | 要填充切片的字节数组视图。 |
| offset | int | 切片起始索引。 |
| count | int | 切片大小。 |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&) 方法

用随机字节填充现有栈数组元素。

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | 要填充的字节栈数组。 |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&, int, int) 方法

用随机字节填充现有栈数组切片。

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes, int offset, int count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | 要填充切片的字节栈数组。 |
| offset | int | 切片起始索引。 |
| count | int | 切片大小。 |

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [RandomNumberGenerator](../)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)