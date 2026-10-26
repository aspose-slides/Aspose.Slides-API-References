---
title: Marshal
second_title: Aspose.Slides for C++ API 参考
description: 提供编组实现。仅为兼容已翻译的代码而存在，因为在 C++ 端不支持受管代码。这是一个没有实例服务的静态类型。无论何种方式都不应创建其实例。
type: docs
weight: 14
url: /zh/system.runtime.interopservices/marshal/
---
## Marshal 类

提供编组实现。仅为兼容已翻译的代码而存在，因为在 C++ 端不支持受管代码。这是一个没有实例服务的静态类型。无论何种方式都不应创建其实例。

```cpp
class Marshal
```

## 方法

| Method | Description |
| --- | --- |
| static IntPtr [AllocHGlobal](./allochglobal/)(**int32_t**) | 分配非托管内存。 |
| static IntPtr [AllocHGlobal](./allochglobal/)(IntPtr) | 分配非托管内存。 |
| static void [Copy](./copy/)(const IntPtr, container\&&, int, int) | 实现 public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) 语义。 |
| static void [Copy](./copy/)(const void *, container\&&, int, int) | 实现 public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) 语义。 |
| static void [Copy](./copy/)(const container\&, int, void *, int) | 实现 public static void Copy(char[] source, int startIndex, IntPtr destination, int length)。 |
| static void [Copy](./copy/)(const container\&, int, IntPtr, int) | 实现 public static void Copy(char[] source, int startIndex, IntPtr destination, int length)。 |
| static void [FreeHGlobal](./freehglobal/)(IntPtr) | 释放非托管内存。 |
| static TDelegate [GetDelegateForFunctionPointer](./getdelegateforfunctionpointer/)(IntPtr) | 将非托管函数指针转换为指定类型的委托。 |
| static **int32_t** [GetHRForException](./gethrforexception/)(const [System::Exception](../../system/exception/)\&) | 从异常获取 HResult。 |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr) | 创建受管 [String](../../system/string/)，来源于非托管零结尾 UTF8-string。 |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr, int) | 创建受管 [String](../../system/string/)，来源于非托管 UTF8-string。 |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr) | 创建受管 [String](../../system/string/)，来源于非托管零结尾字符串。 |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr, int) | 创建受管 [String](../../system/string/)，来源于非托管字符串。 |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr) | 创建受管 [String](../../system/string/)，来源于非托管零结尾 unicode string。 |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr, int) | 创建受管 [String](../../system/string/)，来源于非托管 unicode string。 |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr) | 创建受管 [String](../../system/string/)，来源于非托管零结尾 UTF8-string。 |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr, int) | 创建受管 [String](../../system/string/)，来源于非托管 UTF8-string。 |
| static **uint8_t** [ReadByte](./readbyte/)(IntPtr, int) | 从内存读取 byte。 |
| static **int16_t** [ReadInt16](./readint16/)(IntPtr, int) | 从内存读取 short。 |
| static **int32_t** [ReadInt32](./readint32/)(IntPtr, int) | 从内存读取 int。 |
| static IntPtr [ReadIntPtr](./readintptr/)(IntPtr, int) | 从内存读取 IntPtr。 |
| static IntPtr [SecureStringToGlobalAllocAnsi](./securestringtoglobalallocansi/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | 将指定的安全字符串内容复制到非托管内存，并转换为 ANSI 格式。 |
| static IntPtr [SecureStringToGlobalAllocUnicode](./securestringtoglobalallocunicode/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | 将指定的安全字符串内容复制到非托管内存。 |
| static IntPtr [StringToHGlobalAnsi](./stringtohglobalansi/)(const [String](../../system/string/)\&) | 将指定字符串的内容复制到非托管内存。 |
| static IntPtr [StringToHGlobalAuto](./stringtohglobalauto/)(const [String](../../system/string/)\&) | 将指定字符串的内容复制到非托管内存，如有需要转换为 ANSI 格式。 |
| static IntPtr [StringToHGlobalUni](./stringtohglobaluni/)(const [String](../../system/string/)\&) | 将指定字符串的内容复制到非托管内存。 |
| static void [WriteByte](./writebyte/)(IntPtr, int, **uint8_t**) | 向内存写入 byte。 |
| static void [WriteByte](./writebyte/)(IntPtr, **uint8_t**) | 向内存写入 byte。 |
| static void [WriteInt16](./writeint16/)(IntPtr, int, **int16_t**) | 向内存写入 short。 |
| static void [WriteInt32](./writeint32/)(IntPtr, int, **int32_t**) | 向内存写入 int。 |
| static void [WriteInt64](./writeint64/)(IntPtr, int, **int64_t**) | 向内存写入 long。 |
| static void [WriteIntPtr](./writeintptr/)(IntPtr, int, IntPtr) | 向内存写入 IntPtr。 |
| static void [ZeroFreeGlobalAllocAnsi](./zerofreeglobalallocansi/)(IntPtr) | 释放使用 SecureStringToGlobalAllocAnsi 方法分配的非托管字符串指针。 |
| static void [ZeroFreeGlobalAllocUnicode](./zerofreeglobalallocunicode/)(IntPtr) | 释放使用 SecureStringToGlobalAllocUnicode 方法分配的非托管字符串指针。 |

## 另请参见

* 命名空间 [System::Runtime::InteropServices](../)
* 库 [Aspose.Slides](../../)