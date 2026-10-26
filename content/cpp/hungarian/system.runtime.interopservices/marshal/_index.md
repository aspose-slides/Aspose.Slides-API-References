---
title: Marshal
second_title: Aspose.Slides C++ API Referencia
description: Marshal implementációt biztosít. Csak a lefordított kód kompatibilitásához, mivel a C++ oldalon nem támogatott a felügyelt kód. Ez egy statikus típus, amelynek nincs példányszolgáltatása. Soha nem szabad példányokat létrehozni belőle semmilyen módon.
type: docs
weight: 14
url: /hu/system.runtime.interopservices/marshal/
---
## Marshal osztály

Marshalling implementációt biztosít. Csak a lefordított kód kompatibilitásához, mivel a C++ oldalon nem támogatott a felügyelt kód. Ez egy statikus típus példányszolgáltatások nélkül. Soha nem szabad példányokat létrehozni belőle semmilyen módon.

```cpp
class Marshal
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| static IntPtr [AllocHGlobal](./allochglobal/)(**int32_t**) | Kioszt nem felügyelt memóriát. |
| static IntPtr [AllocHGlobal](./allochglobal/)(IntPtr) | Kioszt nem felügyelt memóriát. |
| static void [Copy](./copy/)(const IntPtr, container\&&, int, int) | Megvalósítja a public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) szemantikai viselkedését. |
| static void [Copy](./copy/)(const void *, container\&&, int, int) | Megvalósítja a public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) szemantikai viselkedését. |
| static void [Copy](./copy/)(const container\&, int, void *, int) | Megvalósítja a public static void Copy(char[] source, int startIndex, IntPtr destination, int length) metódust. |
| static void [Copy](./copy/)(const container\&, int, IntPtr, int) | Megvalósítja a public static void Copy(char[] source, int startIndex, IntPtr destination, int length) metódust. |
| static void [FreeHGlobal](./freehglobal/)(IntPtr) | Felszabadítja a nem felügyelt memóriát. |
| static TDelegate [GetDelegateForFunctionPointer](./getdelegateforfunctionpointer/)(IntPtr) | Átalakít egy nem felügyelt függvénymutatót egy megadott típusú delegátummá. |
| static **int32_t** [GetHRForException](./gethrforexception/)(const [System::Exception](../../system/exception/)\&) | A HResult-et lekéri a kivételből. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr) | Létrehoz egy felügyelt [String](../../system/string/)-t egy nem felügyelt nulla terminált UTF8 karakterláncból. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr, int) | Létrehoz egy felügyelt [String](../../system/string/)-t egy nem felügyelt UTF8 karakterláncból. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr) | Létrehoz egy felügyelt [String](../../system/string/)-t egy nem felügyelt nulla terminált karakterláncból. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr, int) | Létrehoz egy felügyelt [String](../../system/string/)-t egy nem felügyelt karakterláncból. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr) | Létrehoz egy felügyelt [String](../../system/string/)-t egy nem felügyelt nulla terminált unicode karakterláncból. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr, int) | Létrehoz egy felügyelt [String](../../system/string/)-t egy nem felügyelt unicode karakterláncból. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr) | Létrehoz egy felügyelt [String](../../system/string/)-t egy nem felügyelt nulla terminált UTF8 karakterláncból. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr, int) | Létrehoz egy felügyelt [String](../../system/string/)-t egy nem felügyelt UTF8 karakterláncból. |
| static **uint8_t** [ReadByte](./readbyte/)(IntPtr, int) | Olvas egy byte-ot a memóriából. |
| static **int16_t** [ReadInt16](./readint16/)(IntPtr, int) | Olvas egy short-ot a memóriából. |
| static **int32_t** [ReadInt32](./readint32/)(IntPtr, int) | Olvas egy int-et a memóriából. |
| static IntPtr [ReadIntPtr](./readintptr/)(IntPtr, int) | Olvas egy IntPtr-et a memóriából. |
| static IntPtr [SecureStringToGlobalAllocAnsi](./securestringtoglobalallocansi/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Átmásolja a megadott biztonságos karakterlánc tartalmát a nem felügyelt memóriába, ANSI formátumba konvertálva. |
| static IntPtr [SecureStringToGlobalAllocUnicode](./securestringtoglobalallocunicode/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Átmásolja a megadott biztonságos karakterlánc tartalmát a nem felügyelt memóriába. |
| static IntPtr [StringToHGlobalAnsi](./stringtohglobalansi/)(const [String](../../system/string/)\&) | Átmásolja a megadott karakterlánc tartalmát a nem felügyelt memóriába. |
| static IntPtr [StringToHGlobalAuto](./stringtohglobalauto/)(const [String](../../system/string/)\&) | Átmásolja a megadott karakterlánc tartalmát a nem felügyelt memóriába, szükség esetén ANSI formátumba konvertálva. |
| static IntPtr [StringToHGlobalUni](./stringtohglobaluni/)(const [String](../../system/string/)\&) | Átmásolja a megadott karakterlánc tartalmát a nem felügyelt memóriába. |
| static void [WriteByte](./writebyte/)(IntPtr, int, **uint8_t**) | Ír egy byte-ot a memóriába. |
| static void [WriteByte](./writebyte/)(IntPtr, **uint8_t**) | Ír egy byte-ot a memóriába. |
| static void [WriteInt16](./writeint16/)(IntPtr, int, **int16_t**) | Ír egy short-ot a memóriába. |
| static void [WriteInt32](./writeint32/)(IntPtr, int, **int32_t**) | Ír egy int-et a memóriába. |
| static void [WriteInt64](./writeint64/)(IntPtr, int, **int64_t**) | Ír egy long-ot a memóriába. |
| static void [WriteIntPtr](./writeintptr/)(IntPtr, int, IntPtr) | Ír egy IntPtr-et a memóriába. |
| static void [ZeroFreeGlobalAllocAnsi](./zerofreeglobalallocansi/)(IntPtr) | Felszabadítja a nem felügyelt karakterlánc mutatót, amelyet a SecureStringToGlobalAllocAnsi metódus hozott létre. |
| static void [ZeroFreeGlobalAllocUnicode](./zerofreeglobalallocunicode/)(IntPtr) | Felszabadítja a nem felügyelt karakterlánc mutatót, amelyet a SecureStringToGlobalAllocUnicode metódus hozott létre. |

## Lásd még

* Névtér [System::Runtime::InteropServices](../)
* Könyvtár [Aspose.Slides](../../)