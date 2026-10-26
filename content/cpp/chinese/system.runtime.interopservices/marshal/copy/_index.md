---
title: Copy()
second_title: Aspose.Slides for C++ API 参考
description: 实现 public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) 语义。
type: docs
weight: 1
url: /zh/system.runtime.interopservices/marshal/copy/
---
## Marshal::Copy(const IntPtr, container\&&, int, int) 方法

实现 public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) 语义。

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const IntPtr source, container &&destination, int startIndex, int length)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| container | 目标容器类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | const IntPtr | 源数据指针。 |
| destination | container\&& | 要复制数据的容器。 |
| startIndex | int | 源起始索引。 |
| length | int | 要复制的元素数量。 |

## Marshal::Copy(const void *, container\&&, int, int) 方法

实现 public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) 语义。

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const void *source, container &&destination, int startIndex, int length)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| container | 目标容器类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | const void * | 源数据指针。 |
| destination | container\&& | 要复制数据的容器。 |
| startIndex | int | 源起始索引。 |
| length | int | 要复制的元素数量。 |

## Marshal::Copy(const container\&, int, void *, int) 方法

实现 public static void Copy(char[] source, int startIndex, IntPtr destination, int length)。

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, void *destination, int length)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| container | 源容器类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | const container\& | 源数据指针。 |
| startIndex | int | 源起始索引。 |
| destination | void * | 目标数据指针。 |
| length | int | 要复制的元素数量。 |

## Marshal::Copy(const container\&, int, IntPtr, int) 方法

实现 public static void Copy(char[] source, int startIndex, IntPtr destination, int length)。

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, IntPtr destination, int length)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| container | 源容器类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | const container\& | 源数据指针。 |
| startIndex | int | 源起始索引。 |
| destination | IntPtr | 目标数据指针。 |
| length | int | 要复制的元素数量。 |

## 另请参阅

* 类 [Marshal](../)
* 命名空间 [System::Runtime::InteropServices](../../)
* 库 [Aspose.Slides](../../../)