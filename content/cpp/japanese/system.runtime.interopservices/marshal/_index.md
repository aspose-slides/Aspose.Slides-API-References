---
title: Marshal
second_title: Aspose.Slides for C++ API リファレンス
description: マーシャリングの実装を提供します。C++ 側ではマネージドコードがサポートされていないため、翻訳されたコードとの互換性のためだけに使用します。これはインスタンスサービスを持たない静的型です。いかなる方法でもインスタンスを作成してはなりません。
type: docs
weight: 14
url: /ja/system.runtime.interopservices/marshal/
---
## Marshal クラス

Provides marshalling implementation. For compatibility with translated code only, as no managed code is supported on C++ side. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Marshal
```

## Methods

| メソッド | 説明 |
| --- | --- |
| static IntPtr [AllocHGlobal](./allochglobal/)(**int32_t**) | アンマネージド メモリを割り当てます。 |
| static IntPtr [AllocHGlobal](./allochglobal/)(IntPtr) | アンマネージド メモリを割り当てます。 |
| static void [Copy](./copy/)(const IntPtr, container\&&, int, int) | public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) の意味を実装します。 |
| static void [Copy](./copy/)(const void *, container\&&, int, int) | public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) の意味を実装します。 |
| static void [Copy](./copy/)(const container\&, int, void *, int) | public static void Copy(char[] source, int startIndex, IntPtr destination, int length) を実装します。 |
| static void [Copy](./copy/)(const container\&, int, IntPtr, int) | public static void Copy(char[] source, int startIndex, IntPtr destination, int length) を実装します。 |
| static void [FreeHGlobal](./freehglobal/)(IntPtr) | アンマネージド メモリを解放します。 |
| static TDelegate [GetDelegateForFunctionPointer](./getdelegateforfunctionpointer/)(IntPtr) | アンマネージド 関数ポインタを指定された型のデリゲートに変換します。 |
| static **int32_t** [GetHRForException](./gethrforexception/)(const [System::Exception](../../system/exception/)\&) | 例外から HResult を取得します。 |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr) | アンマネージドの NULL 終端 UTF8 文字列から管理対象の [String](../../system/string/) を作成します。 |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr, int) | アンマネージド UTF8 文字列から管理対象の [String](../../system/string/) を作成します。 |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr) | アンマネージドの NULL 終端文字列から管理対象の [String](../../system/string/) を作成します。 |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr, int) | アンマネージド文字列から管理対象の [String](../../system/string/) を作成します。 |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr) | アンマネージドの NULL 終端 Unicode 文字列から管理対象の [String](../../system/string/) を作成します。 |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr, int) | アンマネージド Unicode 文字列から管理対象の [String](../../system/string/) を作成します。 |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr) | アンマネージドの NULL 終端 UTF8 文字列から管理対象の [String](../../system/string/) を作成します。 |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr, int) | アンマネージド UTF8 文字列から管理対象の [String](../../system/string/) を作成します。 |
| static **uint8_t** [ReadByte](./readbyte/)(IntPtr, int) | メモリからバイトを読み取ります。 |
| static **int16_t** [ReadInt16](./readint16/)(IntPtr, int) | メモリから short を読み取ります。 |
| static **int32_t** [ReadInt32](./readint32/)(IntPtr, int) | メモリから int を読み取ります。 |
| static IntPtr [ReadIntPtr](./readintptr/)(IntPtr, int) | メモリから IntPtr を読み取ります。 |
| static IntPtr [SecureStringToGlobalAllocAnsi](./securestringtoglobalallocansi/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | 指定された SecureString の内容をアンマネージド メモリにコピーし、ANSI 形式に変換します。 |
| static IntPtr [SecureStringToGlobalAllocUnicode](./securestringtoglobalallocunicode/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | 指定された SecureString の内容をアンマネージド メモリにコピーします。 |
| static IntPtr [StringToHGlobalAnsi](./stringtohglobalansi/)(const [String](../../system/string/)\&) | 指定された文字列の内容をアンマネージド メモリにコピーします。 |
| static IntPtr [StringToHGlobalAuto](./stringtohglobalauto/)(const [String](../../system/string/)\&) | 指定された文字列の内容をアンマネージド メモリにコピーし、必要に応じて ANSI 形式に変換します。 |
| static IntPtr [StringToHGlobalUni](./stringtohglobaluni/)(const [String](../../system/string/)\&) | 指定された文字列の内容をアンマネージド メモリにコピーします。 |
| static void [WriteByte](./writebyte/)(IntPtr, int, **uint8_t**) | メモリにバイトを書き込みます。 |
| static void [WriteByte](./writebyte/)(IntPtr, **uint8_t**) | メモリにバイトを書き込みます。 |
| static void [WriteInt16](./writeint16/)(IntPtr, int, **int16_t**) | メモリに short を書き込みます。 |
| static void [WriteInt32](./writeint32/)(IntPtr, int, **int32_t**) | メモリに int を書き込みます。 |
| static void [WriteInt64](./writeint64/)(IntPtr, int, **int64_t**) | メモリに long を書き込みます。 |
| static void [WriteIntPtr](./writeintptr/)(IntPtr, int, IntPtr) | メモリに IntPtr を書き込みます。 |
| static void [ZeroFreeGlobalAllocAnsi](./zerofreeglobalallocansi/)(IntPtr) | SecureStringToGlobalAllocAnsi メソッドで割り当てられたアンマネージド文字列ポインタを解放します。 |
| static void [ZeroFreeGlobalAllocUnicode](./zerofreeglobalallocunicode/)(IntPtr) | SecureStringToGlobalAllocUnicode メソッドで割り当てられたアンマネージド文字列ポインタを解放します。 |

## 参照

* 名前空間 [System::Runtime::InteropServices](../)
* ライブラリ [Aspose.Slides](../../)