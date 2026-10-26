---
title: ToUInt32()
second_title: Aspose.Slides for C++ API 参考
description: 将指定数组中从指定索引开始的四个字节转换为无符号 32 位整数值。
type: docs
weight: 105
url: /zh/system/bitconverter/touint32/
---
## BitConverter::ToUInt32(const System::ArrayPtr\<uint8_t\>\&, int) 方法

将指定数组中从指定索引开始的四个字节转换为无符号 32 位整数值。

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 包含要转换的字节 |
| startIndex | int | 数组中用于开始取字节进行转换的索引 |

### 返回值

转换得到的无符号 32 位整数值

## BitConverter::ToUInt32(const System::Details::ArrayView\<uint8_t\>\&, int) 方法

将指定数组中从指定索引开始的四个字节转换为无符号 32 位整数值。

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView 包含要转换的字节 |
| startIndex | int | 数组中用于开始取字节进行转换的索引 |

### 返回值

转换得到的无符号 32 位整数值

## 参见

* 类型定义 [ArrayPtr](../../arrayptr/)
* 类 [BitConverter](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)