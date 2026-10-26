---
title: ToUInt16()
second_title: Aspose.Slides for C++ API 参考
description: 将指定数组中从指定索引开始的两个字节转换为无符号 16 位整数值。
type: docs
weight: 92
url: /zh/system/bitconverter/touint16/
---
## BitConverter::ToUInt16(const System::ArrayPtr\<uint8_t\>\&, int) 方法

将指定数组中从指定索引开始的两个字节转换为无符号 16 位整数值。

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 包含要转换的字节 |
| startIndex | int | 数组中用于开始提取字节进行转换的索引 |

### 返回值

转换后得到的无符号 16 位整数值

## BitConverter::ToUInt16(const System::Details::ArrayView\<uint8_t\>\&, int) 方法

将指定数组中从指定索引开始的两个字节转换为无符号 16 位整数值。

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | 包含要转换的字节的 ArrayView |
| startIndex | int | 数组中用于开始提取字节进行转换的索引 |

### 返回值

转换后得到的无符号 16 位整数值

## 另见

* 类型定义 [ArrayPtr](../../arrayptr/)
* 类 [BitConverter](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)