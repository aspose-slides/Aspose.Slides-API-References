---
title: Marshal
second_title: Aspose.Slides for C++ API 參考文件
description: 提供編組實作。僅為與已翻譯程式碼相容而設，因為 C++ 端不支援受管理程式碼。這是一個不含實例服務的靜態型別。您絕不應以任何方式建立其實例。
type: docs
weight: 14
url: /zh-hant/system.runtime.interopservices/marshal/
---
## Marshal 類別

提供編組實作。僅為與轉譯程式碼相容而設，因為 C++ 端不支援受管理程式碼。這是一個不含實例服務的靜態型別。您不應以任何方式建立其實例。

```cpp
class Marshal
```

## 方法

| 方法 | 說明 |
| --- | --- |
| static IntPtr [AllocHGlobal](./allochglobal/)(**int32_t**) | 配置非託管記憶體。 |
| static IntPtr [AllocHGlobal](./allochglobal/)(IntPtr) | 配置非託管記憶體。 |
| static void [Copy](./copy/)(const IntPtr, container\&&, int, int) | 實作 public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) 語意。 |
| static void [Copy](./copy/)(const void *, container\&&, int, int) | 實作 public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) 語意。 |
| static void [Copy](./copy/)(const container\&, int, void *, int) | 實作 public static void Copy(char[] source, int startIndex, IntPtr destination, int length)。 |
| static void [Copy](./copy/)(const container\&, int, IntPtr, int) | 實作 public static void Copy(char[] source, int startIndex, IntPtr destination, int length)。 |
| static void [FreeHGlobal](./freehglobal/)(IntPtr) | 釋放非託管記憶體。 |
| static TDelegate [GetDelegateForFunctionPointer](./getdelegateforfunctionpointer/)(IntPtr) | 將非託管函式指標轉換為指定類型的委派。 |
| static **int32_t** [GetHRForException](./gethrforexception/)(const [System::Exception](../../system/exception/)\&) | 從例外取得 HResult。 |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr) | 從非託管零結束的 UTF8-字串建立受管理的 [String](../../system/string/)。 |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr, int) | 從非託管 UTF8-字串建立受管理的 [String](../../system/string/)。 |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr) | 從非託管零結束的字串建立受管理的 [String](../../system/string/)。 |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr, int) | 從非託管字串建立受管理的 [String](../../system/string/)。 |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr) | 從非託管零結束的 Unicode 字串建立受管理的 [String](../../system/string/)。 |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr, int) | 從非託管 Unicode 字串建立受管理的 [String](../../system/string/)。 |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr) | 從非託管零結束的 UTF8-字串建立受管理的 [String](../../system/string/)。 |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr, int) | 從非託管 UTF8-字串建立受管理的 [String](../../system/string/)。 |
| static **uint8_t** [ReadByte](./readbyte/)(IntPtr, int) | 從記憶體讀取位元組。 |
| static **int16_t** [ReadInt16](./readint16/)(IntPtr, int) | 從記憶體讀取 short。 |
| static **int32_t** [ReadInt32](./readint32/)(IntPtr, int) | 從記憶體讀取 int。 |
| static IntPtr [ReadIntPtr](./readintptr/)(IntPtr, int) | 從記憶體讀取 IntPtr。 |
| static IntPtr [SecureStringToGlobalAllocAnsi](./securestringtoglobalallocansi/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | 將指定的安全字串內容複製到非託管記憶體，並轉換為 ANSI 格式。 |
| static IntPtr [SecureStringToGlobalAllocUnicode](./securestringtoglobalallocunicode/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | 將指定的安全字串內容複製到非託管記憶體。 |
| static IntPtr [StringToHGlobalAnsi](./stringtohglobalansi/)(const [String](../../system/string/)\&) | 將指定字串的內容複製到非託管記憶體。 |
| static IntPtr [StringToHGlobalAuto](./stringtohglobalauto/)(const [String](../../system/string/)\&) | 將指定字串的內容複製到非託管記憶體，必要時轉換為 ANSI 格式。 |
| static IntPtr [StringToHGlobalUni](./stringtohglobaluni/)(const [String](../../system/string/)\&) | 將指定字串的內容複製到非託管記憶體。 |
| static void [WriteByte](./writebyte/)(IntPtr, int, **uint8_t**) | 將位元組寫入記憶體。 |
| static void [WriteByte](./writebyte/)(IntPtr, **uint8_t**) | 將位元組寫入記憶體。 |
| static void [WriteInt16](./writeint16/)(IntPtr, int, **int16_t**) | 將 short 寫入記憶體。 |
| static void [WriteInt32](./writeint32/)(IntPtr, int, **int32_t**) | 將 int 寫入記憶體。 |
| static void [WriteInt64](./writeint64/)(IntPtr, int, **int64_t**) | 將 long 寫入記憶體。 |
| static void [WriteIntPtr](./writeintptr/)(IntPtr, int, IntPtr) | 將 IntPtr 寫入記憶體。 |
| static void [ZeroFreeGlobalAllocAnsi](./zerofreeglobalallocansi/)(IntPtr) | 釋放使用 SecureStringToGlobalAllocAnsi 方法分配的非託管字串指標。 |
| static void [ZeroFreeGlobalAllocUnicode](./zerofreeglobalallocunicode/)(IntPtr) | 釋放使用 SecureStringToGlobalAllocUnicode 方法分配的非託管字串指標。 |

## 另請參閱

* 命名空間 [System::Runtime::InteropServices](../)
* 程式庫 [Aspose.Slides](../../)