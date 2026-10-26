---
title: ToDouble()
second_title: Aspose.Slides for C++ API 参考
description: 将指定数组中从指定索引开始的八个字节转换为双精度浮点值。
type: docs
weight: 144
url: /zh/system/bitconverter/todouble/
---
## BitConverter::ToDouble(const System::ArrayPtr\<uint8_t\>\&, int) 方法

将指定数组中从指定索引开始的八个字节转换为双精度浮点值。

```cpp
static double System::BitConverter::ToDouble(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 包含要转换的字节 |
| startIndex | int | 数组中开始取字节进行转换的索引 |

### 返回值

双精度浮点值，转换所得

## BitConverter::ToDouble(const System::Details::ArrayView\<uint8_t\>\&, int) 方法

将指定数组中从指定索引开始的八个字节转换为双精度浮点值。

```cpp
static double System::BitConverter::ToDouble(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView 包含要转换的字节 |
| startIndex | int | 数组中开始取字节进行转换的索引 |

### 返回值

双精度浮点值，转换所得

## 另请参阅

* 类型定义 [ArrayPtr](../../arrayptr/)
* 类 [BitConverter](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)