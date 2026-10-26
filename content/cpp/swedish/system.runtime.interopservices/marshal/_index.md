---
title: Marshal
second_title: Aspose.Slides för C++ API-referens
description: Tillhandahåller marshal-implementation. Endast för kompatibilitet med översatt kod, eftersom ingen hanterad kod stöds på C++-sidan. Detta är en statisk typ utan instanstjänster. Du bör aldrig skapa instanser av den på något sätt.
type: docs
weight: 14
url: /sv/system.runtime.interopservices/marshal/
---
## Marshal klass

Tillhandahåller marshal-implementation. Endast för kompatibilitet med översatt kod, eftersom ingen hanterad kod stöds på C++-sidan. Detta är en statisk typ utan instanstjänster. Du bör aldrig skapa instanser av den på något sätt.

```cpp
class Marshal
```

## Metoder

| Method | Description |
| --- | --- |
| static IntPtr [AllocHGlobal](./allochglobal/)(**int32_t**) | Allokerar ohanterat minne. |
| static IntPtr [AllocHGlobal](./allochglobal/)(IntPtr) | Allokerar ohanterat minne. |
| static void [Copy](./copy/)(const IntPtr, container\&&, int, int) | Implementerar public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) semantik. |
| static void [Copy](./copy/)(const void *, container\&&, int, int) | Implementerar public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) semantik. |
| static void [Copy](./copy/)(const container\&, int, void *, int) | Implementerar public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [Copy](./copy/)(const container\&, int, IntPtr, int) | Implementerar public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [FreeHGlobal](./freehglobal/)(IntPtr) | Frigör ohanterat minne. |
| static TDelegate [GetDelegateForFunctionPointer](./getdelegateforfunctionpointer/)(IntPtr) | Konverterar en ohanterad funktionspekare till en delegat av angiven typ. |
| static **int32_t** [GetHRForException](./gethrforexception/)(const [System::Exception](../../system/exception/)\&) | Hämtar HResult från undantag. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr) | Skapar en hanterad [String](../../system/string/) från en ohanterad nollterminerad UTF8-sträng. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr, int) | Skapar en hanterad [String](../../system/string/) från en ohanterad UTF8-sträng. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr) | Skapar en hanterad [String](../../system/string/) från en ohanterad nollterminerad sträng. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr, int) | Skapar en hanterad [String](../../system/string/) från en ohanterad sträng. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr) | Skapar en hanterad [String](../../system/string/) från en ohanterad nollterminerad Unicode-sträng. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr, int) | Skapar en hanterad [String](../../system/string/) från en ohanterad Unicode-sträng. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr) | Skapar en hanterad [String](../../system/string/) från en ohanterad nollterminerad UTF8-sträng. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr, int) | Skapar en hanterad [String](../../system/string/) från en ohanterad UTF8-sträng. |
| static **uint8_t** [ReadByte](./readbyte/)(IntPtr, int) | Läser en byte från minnet. |
| static **int16_t** [ReadInt16](./readint16/)(IntPtr, int) | Läser short från minnet. |
| static **int32_t** [ReadInt32](./readint32/)(IntPtr, int) | Läser int från minnet. |
| static IntPtr [ReadIntPtr](./readintptr/)(IntPtr, int) | Läser IntPtr från minnet. |
| static IntPtr [SecureStringToGlobalAllocAnsi](./securestringtoglobalallocansi/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Kopierar innehållet i den specificerade säkra strängen till ohanterat minne och konverterar till ANSI-format. |
| static IntPtr [SecureStringToGlobalAllocUnicode](./securestringtoglobalallocunicode/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Kopierar innehållet i den specificerade säkra strängen till ohanterat minne. |
| static IntPtr [StringToHGlobalAnsi](./stringtohglobalansi/)(const [String](../../system/string/)\&) | Kopierar innehållet i en specificerad sträng till ohanterat minne. |
| static IntPtr [StringToHGlobalAuto](./stringtohglobalauto/)(const [String](../../system/string/)\&) | Kopierar innehållet i en specificerad sträng till ohanterat minne, konverterar till ANSI-format om det behövs. |
| static IntPtr [StringToHGlobalUni](./stringtohglobaluni/)(const [String](../../system/string/)\&) | Kopierar innehållet i en specificerad sträng till ohanterat minne. |
| static void [WriteByte](./writebyte/)(IntPtr, int, **uint8_t**) | Skriver byte till minnet. |
| static void [WriteByte](./writebyte/)(IntPtr, **uint8_t**) | Skriver byte till minnet. |
| static void [WriteInt16](./writeint16/)(IntPtr, int, **int16_t**) | Skriver short till minnet. |
| static void [WriteInt32](./writeint32/)(IntPtr, int, **int32_t**) | Skriver int till minnet. |
| static void [WriteInt64](./writeint64/)(IntPtr, int, **int64_t**) | Skriver long till minnet. |
| static void [WriteIntPtr](./writeintptr/)(IntPtr, int, IntPtr) | Skriver IntPtr till minnet. |
| static void [ZeroFreeGlobalAllocAnsi](./zerofreeglobalallocansi/)(IntPtr) | Frigör ohanterad strängpekare som allokerades med metoden SecureStringToGlobalAllocAnsi. |
| static void [ZeroFreeGlobalAllocUnicode](./zerofreeglobalallocunicode/)(IntPtr) | Frigör ohanterad strängpekare som allokerades med metoden SecureStringToGlobalAllocUnicode. |

## Se också

* Namnrymd [System::Runtime::InteropServices](../)
* Bibliotek [Aspose.Slides](../../)