---
title: PtrToStringAnsi()
second_title: Aspose.Slides for C++ API 参考
description: 从未托管的零终止 UTF8 字符串创建受托管的 String。
type: docs
weight: 274
url: /zh/system.runtime.interopservices/marshal/ptrtostringansi/
---
## Marshal::PtrToStringAnsi(IntPtr) 方法

从未托管的零终止 UTF8 字符串创建受托管的 [String](../../../system/string/)。

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAnsi(IntPtr ptr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ptr | IntPtr | 指向未托管字符串的指针。 |

### 返回值

受托管的字符串。

## Marshal::PtrToStringAnsi(IntPtr, int) 方法

从未托管的 UTF8 字符串创建受托管的 [String](../../../system/string/)。

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAnsi(IntPtr ptr, int length)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ptr | IntPtr | 指向未托管字符串的指针。 |
| length | int | 未托管字符串的长度。 |

### 返回值

受托管的字符串。

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [Marshal](../)
* 命名空间 [System::Runtime::InteropServices](../../)
* 库 [Aspose.Slides](../../../)