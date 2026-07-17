---
title: GetByte()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的类型化数组解释为原始字节数组，并检索指定字节偏移处的字节值。
type: docs
weight: 27
url: /zh/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) 方法

将指定的类型化数组解释为原始字节数组，并检索指定字节偏移处的字节值。

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 数组元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | 目标数组 |
| index | int | 要检索的字节的零基偏移量 |

### 返回值

指定索引处的字节值

## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) 方法

将指定的类型化数组解释为原始字节数组，并检索指定字节偏移处的字节值。

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 数组视图元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | 目标数组视图 |
| index | int | 要检索的字节的零基偏移量 |

### 返回值

指定索引处的字节值

## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) 方法

将指定的类型化数组解释为原始字节数组，并检索指定字节偏移处的字节值。

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 栈数组元素的类型 |
| N | 栈数组的大小 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | 目标栈数组 |
| index | int | 要检索的字节的零基偏移量 |

### 返回值

指定索引处的字节值

## 另请参见

* 类型别名 [SharedPtr](../../sharedptr/)
* 类 [Array](../../array/)
* 类 [Buffer](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)