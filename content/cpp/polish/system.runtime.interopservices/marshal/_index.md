---
title: Marshal
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Zapewnia implementację marshalingu. Wyłącznie w celu zachowania kompatybilności z przetłumaczonym kodem, ponieważ po stronie C++ nie obsługiwany jest kod zarządzany. Jest to typ statyczny bez usług instancji. Nie należy tworzyć jego instancji w żaden sposób.
type: docs
weight: 14
url: /pl/system.runtime.interopservices/marshal/
---
## Klasa Marshal

Zapewnia implementację marshalingu. Wyłącznie w celu zachowania kompatybilności z przetłumaczonym kodem, ponieważ po stronie C++ nie obsługiwany jest kod zarządzany. Jest to typ statyczny bez usług instancji. Nie należy tworzyć jego instancji w żaden sposób.

```cpp
class Marshal
```

## Metody

| Metoda | Opis |
| --- | --- |
| static IntPtr [AllocHGlobal](./allochglobal/)(**int32_t**) | Alokuje niezarządzaną pamięć. |
| static IntPtr [AllocHGlobal](./allochglobal/)(IntPtr) | Alokuje niezarządzaną pamięć. |
| static void [Copy](./copy/)(const IntPtr, container\&&, int, int) | Implementuje semantykę public static void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static void [Copy](./copy/)(const void *, container\&&, int, int) | Implementuje semantykę public static void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static void [Copy](./copy/)(const container\&, int, void *, int) | Implementuje public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [Copy](./copy/)(const container\&, int, IntPtr, int) | Implementuje public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [FreeHGlobal](./freehglobal/)(IntPtr) | Zwalnia niezarządzaną pamięć. |
| static TDelegate [GetDelegateForFunctionPointer](./getdelegateforfunctionpointer/)(IntPtr) | Konwertuje niezarządzony wskaźnik funkcji na delegata określonego typu. |
| static **int32_t** [GetHRForException](./gethrforexception/)(const [System::Exception](../../system/exception/)\&) | Pobiera HResult z wyjątku. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr) | Tworzy zarządzany [String](../../system/string/) z niezarządzanego ciągu UTF8 zakończonego zerem. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr, int) | Tworzy zarządzany [String](../../system/string/) z niezarządzanego ciągu UTF8. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr) | Tworzy zarządzany [String](../../system/string/) z niezarządzanego ciągu zakończonego zerem. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr, int) | Tworzy zarządzany [String](../../system/string/) z niezarządzanego ciągu. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr) | Tworzy zarządzany [String](../../system/string/) z niezarządzanego ciągu Unicode zakończonego zerem. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr, int) | Tworzy zarządzany [String](../../system/string/) z niezarządzanego ciągu Unicode. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr) | Tworzy zarządzany [String](../../system/string/) z niezarządzanego ciągu UTF8 zakończonego zerem. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr, int) | Tworzy zarządzany [String](../../system/string/) z niezarządzanego ciągu UTF8. |
| static **uint8_t** [ReadByte](./readbyte/)(IntPtr, int) | Odczytuje bajt z pamięci. |
| static **int16_t** [ReadInt16](./readint16/)(IntPtr, int) | Odczytuje short z pamięci. |
| static **int32_t** [ReadInt32](./readint32/)(IntPtr, int) | Odczytuje int z pamięci. |
| static IntPtr [ReadIntPtr](./readintptr/)(IntPtr, int) | Odczytuje IntPtr z pamięci. |
| static IntPtr [SecureStringToGlobalAllocAnsi](./securestringtoglobalallocansi/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Kopiuje zawartość określonego SecureString do niezarządzanej pamięci, konwertując do formatu ANSI. |
| static IntPtr [SecureStringToGlobalAllocUnicode](./securestringtoglobalallocunicode/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Kopiuje zawartość określonego SecureString do niezarządzanej pamięci. |
| static IntPtr [StringToHGlobalAnsi](./stringtohglobalansi/)(const [String](../../system/string/)\&) | Kopiuje zawartość określonego ciągu do niezarządzanej pamięci. |
| static IntPtr [StringToHGlobalAuto](./stringtohglobalauto/)(const [String](../../system/string/)\&) | Kopiuje zawartość określonego ciągu do niezarządzanej pamięci, konwertując do formatu ANSI w razie potrzeby. |
| static IntPtr [StringToHGlobalUni](./stringtohglobaluni/)(const [String](../../system/string/)\&) | Kopiuje zawartość określonego ciągu do niezarządzanej pamięci. |
| static void [WriteByte](./writebyte/)(IntPtr, int, **uint8_t**) | Zapisuje bajt do pamięci. |
| static void [WriteByte](./writebyte/)(IntPtr, **uint8_t**) | Zapisuje bajt do pamięci. |
| static void [WriteInt16](./writeint16/)(IntPtr, int, **int16_t**) | Zapisuje short do pamięci. |
| static void [WriteInt32](./writeint32/)(IntPtr, int, **int32_t**) | Zapisuje int do pamięci. |
| static void [WriteInt64](./writeint64/)(IntPtr, int, **int64_t**) | Zapisuje long do pamięci. |
| static void [WriteIntPtr](./writeintptr/)(IntPtr, int, IntPtr) | Zapisuje IntPtr do pamięci. |
| static void [ZeroFreeGlobalAllocAnsi](./zerofreeglobalallocansi/)(IntPtr) | Zwalnia niezarządzony wskaźnik string przydzielony przy użyciu metody SecureStringToGlobalAllocAnsi. |
| static void [ZeroFreeGlobalAllocUnicode](./zerofreeglobalallocunicode/)(IntPtr) | Zwalnia niezarządzony wskaźnik string przydzielony przy użyciu metody SecureStringToGlobalAllocUnicode. |

## Zobacz także

* Przestrzeń nazw [System::Runtime::InteropServices](../)
* Biblioteka [Aspose.Slides](../../)