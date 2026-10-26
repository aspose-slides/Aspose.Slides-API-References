---
title: UnmanagedMemoryStream()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个新的 UnmanagedMemoryStream 实例。
type: docs
weight: 118
url: /zh/system.io/unmanagedmemorystream/unmanagedmemorystream/
---
## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t) 构造函数

构造一个新的 [UnmanagedMemoryStream](../) 实例。

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pointer | **uint8_t** * | 指向非托管缓冲区的指针 |
| length | **int64_t** | 非托管缓冲区的字节大小 |

## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t, int64_t, FileAccess) 构造函数

构造一个新的 [UnmanagedMemoryStream](../) 实例。

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length, int64_t capacity, FileAccess access)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pointer | **uint8_t** * | 指向非托管缓冲区的指针 |
| length | **int64_t** | 非托管缓冲区的字节大小 |
| capacity | **int64_t** | 流分配的内存总量 |
| access | [FileAccess](../../fileaccess/) | 指定流是只读、只写还是两者兼有 |

## 参见

* 枚举 [FileAccess](../../fileaccess/)
* 类 [UnmanagedMemoryStream](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)