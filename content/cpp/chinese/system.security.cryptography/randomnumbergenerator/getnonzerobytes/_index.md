---
title: GetNonZeroBytes()
second_title: Aspose.Slides for C++ API 参考
description: 使用随机非零字节填充现有数组元素。
type: docs
weight: 27
url: /zh/system.security.cryptography/randomnumbergenerator/getnonzerobytes/
---
## RandomNumberGenerator::GetNonZeroBytes(ArrayPtr\<uint8_t\>) 方法

使用随机非零字节填充现有数组元素。

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetNonZeroBytes(ArrayPtr<uint8_t> bytes)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 用于填充的字节数组。 |

## RandomNumberGenerator::GetNonZeroBytes(System::Details::ArrayView\<uint8_t\>) 方法

使用随机非零字节填充现有数组视图元素。

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetNonZeroBytes(System::Details::ArrayView<uint8_t> bytes)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | 用于填充的字节数组视图。 |

## RandomNumberGenerator::GetNonZeroBytes(System::Details::StackArray\<uint8_t, N\>\&) 方法

使用随机非零字节填充现有堆栈数组元素。

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetNonZeroBytes(System::Details::StackArray<uint8_t, N> &bytes)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | 用于填充的字节堆栈数组。 |

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [RandomNumberGenerator](../)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)