---
title: SetByte()
second_title: Aspose.Slides C++ API 参考
description: 将指定的类型化数组解释为原始字节数组，并在指定的字节偏移处设置指定的字节值。
type: docs
weight: 40
url: /zh/system/buffer/setbyte/
---
## Buffer::SetByte(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) 方法

将指定的类型化数组解释为原始字节数组，并在指定的字节偏移处设置指定的字节值。

```cpp
template<typename T> static void System::Buffer::SetByte(const SharedPtr<Array<T>> &array, int index, uint8_t value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 数组中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | 目标数组 |
| index | int | 要设置的字节的零基偏移 |
| value | **uint8_t** | 要设置的字节值 |

## Buffer::SetByte(const System::Details::ArrayView\<T\>\&, int, uint8_t) 方法

将指定的类型化数组解释为原始字节数组，并在指定的字节偏移处设置指定的字节值。

```cpp
template<typename T> static void System::Buffer::SetByte(const System::Details::ArrayView<T> &array, int index, uint8_t value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 数组中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | 目标数组视图 |
| index | int | 要设置的字节的零基偏移 |
| value | **uint8_t** | 要设置的字节值 |

## Buffer::SetByte(const System::Details::StackArray\<T, N\>\&, int, uint8_t) 方法

将指定的类型化数组解释为原始字节数组，并在指定的字节偏移处设置指定的字节值。

```cpp
template<typename T,std::size_t> static void System::Buffer::SetByte(const System::Details::StackArray<T, N> &array, int index, uint8_t value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 数组中元素的类型 |
| N | 栈数组的大小 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | 目标栈数组 |
| index | int | 要设置的字节的零基偏移 |
| value | **uint8_t** | 要设置的字节值 |

## 另见

* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [Array](../../array/)
* 类 [Buffer](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)