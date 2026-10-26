---
title: PtrToStringUni()
second_title: Aspose.Slides for C++ API 参考
description: 从未托管的零结尾 Unicode 字符串创建受管理的 String。
type: docs
weight: 300
url: /zh/system.runtime.interopservices/marshal/ptrtostringuni/
---
## Marshal::PtrToStringUni(IntPtr) 方法

创建一个受管理的[String](../../../system/string/)，来自未管理的零结尾 Unicode 字符串。

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringUni(IntPtr ptr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ptr | IntPtr | 指向未管理字符串的指针。 |

### 返回值

受管理的字符串。

## Marshal::PtrToStringUni(IntPtr, int) 方法

创建一个受管理的[String](../../../system/string/)，来自未管理的 Unicode 字符串。

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringUni(IntPtr ptr, int length)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ptr | IntPtr | 指向未管理字符串的指针。 |
| length | int | 未管理字符串的长度。 |

### 返回值

受管理的字符串。

## 另请参见

* 类 [String](../../../system/string/)
* 类 [Marshal](../)
* 命名空间 [System::Runtime::InteropServices](../../)
* 库 [Aspose.Slides](../../../)