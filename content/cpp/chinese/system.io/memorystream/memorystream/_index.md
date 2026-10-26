---
title: MemoryStream()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个新的 MemoryStream 类实例，初始容量为 0。
type: docs
weight: 1
url: /zh/system.io/memorystream/memorystream/
---
## MemoryStream::MemoryStream() 构造函数

构造一个新的 [MemoryStream](../) 类实例，初始容量为 0。

```cpp
System::IO::MemoryStream::MemoryStream()
```

## MemoryStream::MemoryStream(int) 构造函数

构造一个新的 [MemoryStream](../) 类实例，表示基于指定大小的内存缓冲区的流。

```cpp
System::IO::MemoryStream::MemoryStream(int capacity_)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| capacity_ | int | 与正在创建的对象所表示的流关联的内存缓冲区的字节大小 |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, bool) 构造函数

构造一个新的 [MemoryStream](../) 类实例，表示连接到指定内存缓冲区的内存流。一个参数指定该流是否可写。

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, bool writable=1)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 用作内存缓冲区的字节数组，创建的对象所表示的流将基于该缓冲区 |
| writable | **bool** | 指定该流是否可写 |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) 构造函数

构造一个新的 [MemoryStream](../) 类实例，表示连接到指定内存缓冲区的一个段（从指定索引开始并包含指定数量的元素）的内存流。参数指定该流是否可写，以及是否可以调用方法 GetBytes()。

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, int index, int count, bool writable=1, bool publiclyVisible=false)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 一个字节数组，其段将用作内存缓冲区，创建的对象所表示的流将基于该缓冲区 |
| index | int | 在 **content** 中段开始的元素的基于 0 的索引 |
| count | int | **content** 中包含在段中的元素数量 |
| writable | **bool** | 指定该流是否可写 |
| publiclyVisible | **bool** | 指定底层内存缓冲区是否应向方法 GetByte() 的调用者公开 |

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [MemoryStream](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)