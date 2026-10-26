---
title: ToInt16()
second_title: Aspose.Slides for C++ API 参考
description: 将指定数组中从指定索引开始的两个字节转换为16位整数值。
type: docs
weight: 53
url: /zh/system/bitconverter/toint16/
---
## BitConverter::ToInt16(const System::ArrayPtr\<uint8_t\>\&, int) 方法

将指定数组中从指定索引开始的两个字节转换为16位整数值。

```cpp
static int16_t System::BitConverter::ToInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 包含要转换的字节 |
| startIndex | int | 数组中开始取字节进行转换的索引 |

### 返回值

转换后得到的16位整数值

## BitConverter::ToInt16(const System::Details::ArrayView\<uint8_t\>\&, int) 方法

将指定数组中从指定索引开始的两个字节转换为16位整数值。

```cpp
static int16_t System::BitConverter::ToInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView 包含要转换的字节 |
| startIndex | int | 数组中开始取字节进行转换的索引 |

### 返回值

转换后得到的16位整数值

## 另请参见

* Typedef [ArrayPtr](../../arrayptr/)
* 类 [BitConverter](../)
* 命名空间 [System](../../)
* Library [Aspose.Slides](../../../)