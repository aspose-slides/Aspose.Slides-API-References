---
title: ToBoolean()
second_title: Aspose.Slides C++ API 参考
description: 将指定数组中从指定索引开始的一个字节转换为布尔值。
type: docs
weight: 27
url: /zh/system/bitconverter/toboolean/
---
## BitConverter::ToBoolean(const System::ArrayPtr\<uint8_t\>\&, int) 方法

将指定数组中从指定索引开始的一个字节转换为布尔值。

```cpp
static bool System::BitConverter::ToBoolean(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 其中包含要转换的字节 |
| startIndex | int | 在数组中开始取字节进行转换的索引 |

### 返回值

[Boolean](../../boolean/) 由转换产生的值

## BitConverter::ToBoolean(const System::Details::ArrayView\<uint8_t\>\&, int) 方法

将指定数组中从指定索引开始的一个字节转换为布尔值。

```cpp
static bool System::BitConverter::ToBoolean(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView 其中包含要转换的字节 |
| startIndex | int | 在数组中开始取字节进行转换的索引 |

### 返回值

[Boolean](../../boolean/) 由转换产生的值

## 另请参见

* Typedef [ArrayPtr](../../arrayptr/)
* 类 [BitConverter](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)