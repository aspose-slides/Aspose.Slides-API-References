---
title: Marshal
second_title: Aspose.Slides pro C++ API Reference
description: Poskytuje implementaci marshalling. Pouze pro kompatibilitu s přeloženým kódem, protože na straně C++ není podporován žádný spravovaný kód. Jedná se o statický typ bez instančních služeb. Nikdy byste jej neměli vytvářet žádnými prostředky.
type: docs
weight: 14
url: /cs/system.runtime.interopservices/marshal/
---
## Marshal třída

Poskytuje implementaci marshalling. Pouze pro kompatibilitu s přeloženým kódem, protože na straně C++ není podporován žádný spravovaný kód. Jedná se o statický typ bez instančních služeb. Nikdy byste jej neměli vytvářet žádnými prostředky.

```cpp
class Marshal
```

## Metody

| Metoda | Popis |
| --- | --- |
| static IntPtr [AllocHGlobal](./allochglobal/)(**int32_t**) | Alokuje neřízenou paměť. |
| static IntPtr [AllocHGlobal](./allochglobal/)(IntPtr) | Alokuje neřízenou paměť. |
| static void [Copy](./copy/)(const IntPtr, container\&&, int, int) | Implementuje sémantiku public static void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static void [Copy](./copy/)(const void *, container\&&, int, int) | Implementuje sémantiku public static void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static void [Copy](./copy/)(const container\&, int, void *, int) | Implementuje public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [Copy](./copy/)(const container\&, int, IntPtr, int) | Implementuje public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [FreeHGlobal](./freehglobal/)(IntPtr) | Uvolní neřízenou paměť. |
| static TDelegate [GetDelegateForFunctionPointer](./getdelegateforfunctionpointer/)(IntPtr) | Převádí neřízený ukazatel na funkci na delegáta zadaného typu. |
| static **int32_t** [GetHRForException](./gethrforexception/)(const [System::Exception](../../system/exception/)\&) | Získá HResult z výjimky. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr) | Vytvoří spravovaný [String](../../system/string/) z neřízeného nulou ukončeného řetězce UTF8. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr, int) | Vytvoří spravovaný [String](../../system/string/) z neřízeného řetězce UTF8. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr) | Vytvoří spravovaný [String](../../system/string/) z neřízeného nulou ukončeného řetězce. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr, int) | Vytvoří spravovaný [String](../../system/string/) z neřízeného řetězce. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr) | Vytvoří spravovaný [String](../../system/string/) z neřízeného nulou ukončeného unicode řetězce. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr, int) | Vytvoří spravovaný [String](../../system/string/) z neřízeného unicode řetězce. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr) | Vytvoří spravovaný [String](../../system/string/) z neřízeného nulou ukončeného řetězce UTF8. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr, int) | Vytvoří spravovaný [String](../../system/string/) z neřízeného řetězce UTF8. |
| static **uint8_t** [ReadByte](./readbyte/)(IntPtr, int) | Čte bajt z paměti. |
| static **int16_t** [ReadInt16](./readint16/)(IntPtr, int) | Čte short z paměti. |
| static **int32_t** [ReadInt32](./readint32/)(IntPtr, int) | Čte int z paměti. |
| static IntPtr [ReadIntPtr](./readintptr/)(IntPtr, int) | Čte IntPtr z paměti. |
| static IntPtr [SecureStringToGlobalAllocAnsi](./securestringtoglobalallocansi/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Zkopíruje obsah zadaného zabezpečeného řetězce do neřízené paměti a převádí do formátu ANSI. |
| static IntPtr [SecureStringToGlobalAllocUnicode](./securestringtoglobalallocunicode/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Zkopíruje obsah zadaného zabezpečeného řetězce do neřízené paměti. |
| static IntPtr [StringToHGlobalAnsi](./stringtohglobalansi/)(const [String](../../system/string/)\&) | Zkopíruje obsah zadaného řetězce do neřízené paměti. |
| static IntPtr [StringToHGlobalAuto](./stringtohglobalauto/)(const [String](../../system/string/)\&) | Zkopíruje obsah zadaného řetězce do neřízené paměti a převádí do formátu ANSI, pokud je to požadováno. |
| static IntPtr [StringToHGlobalUni](./stringtohglobaluni/)(const [String](../../system/string/)\&) | Zkopíruje obsah zadaného řetězce do neřízené paměti. |
| static void [WriteByte](./writebyte/)(IntPtr, int, **uint8_t**) | Zapíše bajt do paměti. |
| static void [WriteByte](./writebyte/)(IntPtr, **uint8_t**) | Zapíše bajt do paměti. |
| static void [WriteInt16](./writeint16/)(IntPtr, int, **int16_t**) | Zapíše short do paměti. |
| static void [WriteInt32](./writeint32/)(IntPtr, int, **int32_t**) | Zapíše int do paměti. |
| static void [WriteInt64](./writeint64/)(IntPtr, int, **int64_t**) | Zapíše long do paměti. |
| static void [WriteIntPtr](./writeintptr/)(IntPtr, int, IntPtr) | Zapíše IntPtr do paměti. |
| static void [ZeroFreeGlobalAllocAnsi](./zerofreeglobalallocansi/)(IntPtr) | Uvolní neřízený ukazatel na řetězec, který byl alokován pomocí metody SecureStringToGlobalAllocAnsi. |
| static void [ZeroFreeGlobalAllocUnicode](./zerofreeglobalallocunicode/)(IntPtr) | Uvolní neřízený ukazatel na řetězec, který byl alokován pomocí metody SecureStringToGlobalAllocUnicode. |

## Viz také

* jmenný prostor [System::Runtime::InteropServices](../)
* Knihovna [Aspose.Slides](../../)