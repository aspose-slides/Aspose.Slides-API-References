---
title: PtrToStringUTF8()
second_title: Aspose.Slides for C++ API 参考
description: 从未管理的零终止 UTF8 字符串创建受管理的 String。
type: docs
weight: 313
url: /zh/system.runtime.interopservices/marshal/ptrtostringutf8/
---
## Marshal::PtrToStringUTF8(IntPtr) 方法

从未管理的零终止 UTF8 字符串创建受管理的 [String](../../../system/string/)。

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringUTF8(IntPtr ptr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ptr | IntPtr | 指向未管理字符串的指针。 |

### 返回值

受管理的字符串。

## Marshal::PtrToStringUTF8(IntPtr, int) 方法

从未管理的 UTF8 字符串创建受管理的 [String](../../../system/string/)。

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringUTF8(IntPtr ptr, int length)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ptr | IntPtr | 指向未管理字符串的指针。 |
| length | int | 未管理字符串的长度。 |

### 返回值

受管理的字符串。

## 参见

* 类 [String](../../../system/string/)
* 类 [Marshal](../)
* 命名空间 [System::Runtime::InteropServices](../../)
* Library [Aspose.Slides](../../../)