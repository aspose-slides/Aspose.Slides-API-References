---
title: ToSingle()
second_title: Aspose.Slides for C++ API 参考
description: 将指定数组中从指定索引开始的四个字节转换为单精度浮点值。
type: docs
weight: 131
url: /zh/system/bitconverter/tosingle/
---
## BitConverter::ToSingle(const System::ArrayPtr\<uint8_t\>\&, int) 方法

将指定数组中从指定索引开始的四个字节转换为单精度浮点值。

```cpp
static float System::BitConverter::ToSingle(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/)，其中包含要转换的字节 |
| startIndex | int | 数组中开始获取字节进行转换的索引 |

### 返回值

转换后得到的单精度浮点值

## BitConverter::ToSingle(const System::Details::ArrayView\<uint8_t\>\&, int) 方法

将指定数组中从指定索引开始的四个字节转换为单精度浮点值。

```cpp
static float System::BitConverter::ToSingle(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView，其中包含要转换的字节 |
| startIndex | int | 数组中开始获取字节进行转换的索引 |

### 返回值

转换后得到的单精度浮点值

## 参见

* 类型定义 [ArrayPtr](../../arrayptr/)
* 类 [BitConverter](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)