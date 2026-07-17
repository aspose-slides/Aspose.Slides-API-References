---
title: ToInt64()
second_title: Aspose.Slides C++ API 参考
description: 将指定数组中从指定索引开始的八个字节转换为 64 位整数值。
type: docs
weight: 79
url: /zh/system/bitconverter/toint64/
---
## BitConverter::ToInt64(const System::ArrayPtr\<uint8_t\>\&, int) 方法


将指定数组中从指定索引开始的八个字节转换为 64 位整数值。

```cpp
static int64_t System::BitConverter::ToInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 包含要转换的字节 |
| startIndex | int | 在数组中开始取字节进行转换的索引 |

### 返回值

64 位整数值，转换结果

## BitConverter::ToInt64(const System::Details::ArrayView\<uint8_t\>\&, int) 方法


将指定数组中从指定索引开始的八个字节转换为 64 位整数值。

```cpp
static int64_t System::BitConverter::ToInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView 包含要转换的字节 |
| startIndex | int | 在数组中开始取字节进行转换的索引 |

### 返回值

64 位整数值，转换结果

## 另请参见

* 类型定义 [ArrayPtr](../../arrayptr/)
* 类 [BitConverter](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)