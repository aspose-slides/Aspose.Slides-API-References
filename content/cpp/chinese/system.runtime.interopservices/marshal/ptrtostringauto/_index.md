---
title: PtrToStringAuto()
second_title: Aspose.Slides C++ API 参考
description: 从未受管理的以零结尾的字符串创建受管理的 String。
type: docs
weight: 287
url: /zh/system.runtime.interopservices/marshal/ptrtostringauto/
---
## Marshal::PtrToStringAuto(IntPtr) 方法


创建一个受管理的 [String](../../../system/string/)，来源于未受管理的以零结尾的字符串。

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAuto(IntPtr ptr)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ptr | IntPtr | 指向未受管理的字符串的指针。 |

### 返回值

受管理的字符串。

## Marshal::PtrToStringAuto(IntPtr, int) 方法


创建一个受管理的 [String](../../../system/string/)，来源于未受管理的字符串。

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAuto(IntPtr ptr, int length)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ptr | IntPtr | 指向未受管理的字符串的指针。 |
| length | int | 未受管理的字符串的长度。 |

### 返回值

受管理的字符串。

## 另见

* 类 [String](../../../system/string/)
* 类 [Marshal](../)
* 命名空间 [System::Runtime::InteropServices](../../)
* 库 [Aspose.Slides](../../../)