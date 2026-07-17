---
title: BlockCopy()
second_title: Aspose.Slides for C++ API 参考
description: 将指定数量的字节从源缓冲区复制到目标缓冲区。
type: docs
weight: 1
url: /zh/system/buffer/blockcopy/
---
## Buffer::BlockCopy(const uint8_t *, int, uint8_t *, int, int) 方法

将指定数量的字节从源缓冲区复制到目标缓冲区。

```cpp
static void System::Buffer::BlockCopy(const uint8_t *src, int srcOffset, uint8_t *dst, int dstOffset, int count)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| src | const **uint8_t** * | 指向源缓冲区的指针 |
| srcOffset | int | 源缓冲区中开始复制的字节偏移 |
| dst | **uint8_t** * | 指向目标缓冲区的指针 |
| dstOffset | int | 目标缓冲区中开始插入数据的字节偏移 |
| count | int | 要复制的字节数 |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) 方法

将两个指定的强类型数组解释为原始字节数组，并将数据从其中一个复制到另一个。

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### 模板参数

| 参数 | 说明 |
| --- | --- |
| TSrc | 源数组元素的类型 |
| TDst | 目标数组元素的类型 |

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | 源数组 |
| srcOffset | int | 源数组中开始复制的字节偏移 |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | 目标数组 |
| dstOffset | int | 目标数组中开始插入数据的字节偏移 |
| count | int | 要复制的字节数 |

## Buffer::BlockCopy(const SharedPtr\<ArrayBase\>\&, int, const SharedPtr\<ArrayBase\>\&, int, int) 方法

将两个指定的数组解释为原始字节数组，并将数据从其中一个复制到另一个。

```cpp
static void System::Buffer::BlockCopy(const SharedPtr<ArrayBase> &src, int srcOffset, const SharedPtr<ArrayBase> &dst, int dstOffset, int count)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | 源数组 |
| srcOffset | int | 源数组中开始复制的字节偏移 |
| dst | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | 目标数组 |
| dstOffset | int | 目标数组中开始插入数据的字节偏移 |
| count | int | 要复制的字节数 |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) 方法

将两个指定的强类型数组解释为原始字节数组，并将数据从其中一个复制到另一个。

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### 模板参数

| 参数 | 说明 |
| --- | --- |
| TSrc | 源数组视图元素的类型 |
| TDst | 目标数组视图元素的类型 |

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | 源数组视图 |
| srcOffset | int | 源数组视图中开始复制的字节偏移 |
| dst | const System::Details::ArrayView\<TDst\>\& | 目标数组视图 |
| dstOffset | int | 目标数组视图中开始插入数据的字节偏移 |
| count | int | 要复制的字节数 |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) 方法

将两个指定的强类型数组解释为原始字节数组，并将数据从其中一个复制到另一个。

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### 模板参数

| 参数 | 说明 |
| --- | --- |
| TSrc | 源数组元素的类型 |
| TDst | 目标数组视图元素的类型 |

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | 源数组 |
| srcOffset | int | 源数组中开始复制的字节偏移 |
| dst | const System::Details::ArrayView\<TDst\>\& | 目标数组视图 |
| dstOffset | int | 目标数组视图中开始插入数据的字节偏移 |
| count | int | 要复制的字节数 |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) 方法

将两个指定的强类型数组解释为原始字节数组，并将数据从其中一个复制到另一个。

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### 模板参数

| 参数 | 说明 |
| --- | --- |
| TSrc | 源数组视图元素的类型 |
| TDst | 目标数组元素的类型 |

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | 源数组视图 |
| srcOffset | int | 源数组视图中开始复制的字节偏移 |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | 目标数组 |
| dstOffset | int | 目标数组中开始插入数据的字节偏移 |
| count | int | 要复制的字节数 |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) 方法

将两个指定的强类型数组解释为原始字节数组，并将数据从其中一个复制到另一个。

```cpp
template<typename TSrc,std::size_t,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### 模板参数

| 参数 | 说明 |
| --- | --- |
| TSrc | 源堆栈数组元素的类型 |
| NS | 源堆栈数组的大小 |
| TDst | 目标堆栈数组元素的类型 |
| ND | 目标堆栈数组的大小 |

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | 源堆栈数组 |
| srcOffset | int | 源堆栈数组中开始复制的字节偏移 |
| dst | const System::Details::StackArray\<TDst, ND\>\& | 目标堆栈数组 |
| dstOffset | int | 目标堆栈数组中开始插入数据的字节偏移 |
| count | int | 要复制的字节数 |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) 方法

将两个指定的强类型数组解释为原始字节数组，并将数据从其中一个复制到另一个。

```cpp
template<typename TSrc,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### 模板参数

| 参数 | 说明 |
| --- | --- |
| TSrc | 源数组元素的类型 |
| TDst | 目标堆栈数组元素的类型 |
| ND | 目标堆栈数组的大小 |

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | 源数组 |
| srcOffset | int | 源数组中开始复制的字节偏移 |
| dst | const System::Details::StackArray\<TDst, ND\>\& | 目标堆栈数组 |
| dstOffset | int | 目标堆栈数组中开始插入数据的字节偏移 |
| count | int | 要复制的字节数 |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) 方法

将两个指定的强类型数组解释为原始字节数组，并将数据从其中一个复制到另一个。

```cpp
template<typename TSrc,std::size_t,typename TDst> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### 模板参数

| 参数 | 说明 |
| --- | --- |
| TSrc | 源堆栈数组元素的类型 |
| NS | 源堆栈数组的大小 |
| TDst | 目标数组元素的类型 |

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | 源堆栈数组 |
| srcOffset | int | 源堆栈数组中开始复制的字节偏移 |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | 目标数组 |
| dstOffset | int | 目标数组中开始插入数据的字节偏移 |
| count | int | 要复制的字节数 |

## 参见

* Typedef [SharedPtr](../../sharedptr/)
* 类 [Buffer](../)
* 类 [Array](../../array/)
* 类 [ArrayBase](../../arraybase/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)