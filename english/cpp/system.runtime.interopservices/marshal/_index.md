---
title: Marshal
second_title: Aspose.Slides for C++ API Reference
description: Provides marshalling implementation. For compatibility with translated code only, as no managed code is supported on C++ side. This is a static type with no instance services. You should never create instances of it by any means.
type: docs
weight: 14
url: /cpp/system.runtime.interopservices/marshal/
---
## Marshal class


Provides marshalling implementation. For compatibility with translated code only, as no managed code is supported on C++ side. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Marshal
```

## Methods

| Method | Description |
| --- | --- |
| static IntPtr [AllocHGlobal](./allochglobal/)(**int32_t**) | Allocates unmanaged memory. |
| static IntPtr [AllocHGlobal](./allochglobal/)(IntPtr) | Allocates unmanaged memory. |
| static void [Copy](./copy/)(const IntPtr, container\&&, int, int) | Implements public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) semantics. |
| static void [Copy](./copy/)(const void *, container\&&, int, int) | Implements public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) semantics. |
| static void [Copy](./copy/)(const container\&, int, void *, int) | Implements public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [Copy](./copy/)(const container\&, int, IntPtr, int) | Implements public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [FreeHGlobal](./freehglobal/)(IntPtr) | Frees unmanaged memory. |
| static **int32_t** [GetHRForException](./gethrforexception/)(const [System::Exception](../../system/exception/)\&) | Gets HResult from exception. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr) | Creates a managed [String](../../system/string/) from an unmanaged zero-terminated UTF8-string. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr, int) | Creates a managed [String](../../system/string/) from an unmanaged UTF8-string. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr) | Creates a managed [String](../../system/string/) from an unmanaged zero-terminated string. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr, int) | Creates a managed [String](../../system/string/) from an unmanaged string. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr) | Creates a managed [String](../../system/string/) from an unmanaged zero-terminated unicode string. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr, int) | Creates a managed [String](../../system/string/) from an unmanaged unicode string. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr) | Creates a managed [String](../../system/string/) from an unmanaged zero-terminated UTF8-string. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr, int) | Creates a managed [String](../../system/string/) from an unmanaged UTF8-string. |
| static **uint8_t** [ReadByte](./readbyte/)(IntPtr, int) | Reads byte from memory. |
| static **int16_t** [ReadInt16](./readint16/)(IntPtr, int) | Reads short from memory. |
| static **int32_t** [ReadInt32](./readint32/)(IntPtr, int) | Reads int from memory. |
| static IntPtr [SecureStringToGlobalAllocAnsi](./securestringtoglobalallocansi/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Copies contents of specified secure string into unmanaged memory, converting into ANSI format. |
| static IntPtr [SecureStringToGlobalAllocUnicode](./securestringtoglobalallocunicode/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Copies contents of specified secure string into unmanaged memory. |
| static IntPtr [StringToHGlobalAnsi](./stringtohglobalansi/)(const [String](../../system/string/)\&) | Copies the contents of a specified string into unmanaged memory. |
| static IntPtr [StringToHGlobalAuto](./stringtohglobalauto/)(const [String](../../system/string/)\&) | Copies the contents of a specified string into unmanaged memory, converting to ANSI format if required. |
| static IntPtr [StringToHGlobalUni](./stringtohglobaluni/)(const [String](../../system/string/)\&) | Copies the contents of a specified string into unmanaged memory. |
| static void [WriteByte](./writebyte/)(IntPtr, int, **uint8_t**) | Writes byte to memory. |
| static void [WriteByte](./writebyte/)(IntPtr, **uint8_t**) | Writes byte to memory. |
| static void [WriteInt16](./writeint16/)(IntPtr, int, **int16_t**) | Writes short to memory. |
| static void [WriteInt32](./writeint32/)(IntPtr, int, **int32_t**) | Writes int to memory. |
| static void [WriteInt64](./writeint64/)(IntPtr, int, **int64_t**) | Writes long to memory. |
| static void [ZeroFreeGlobalAllocAnsi](./zerofreeglobalallocansi/)(IntPtr) | Frees unmanaged string pointer that was allocated using the SecureStringToGlobalAllocAnsi method. |
| static void [ZeroFreeGlobalAllocUnicode](./zerofreeglobalallocunicode/)(IntPtr) | Frees unmanaged string pointer that was allocated using the SecureStringToGlobalAllocUnicode method. |
## See Also

* Namespace [System::Runtime::InteropServices](../)
* Library [Aspose.Slides](../../)
