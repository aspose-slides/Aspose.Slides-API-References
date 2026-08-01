---
title: Marshal
second_title: Aspose.Slides voor C++ API-referentie
description: Biedt een marshalling-implementatie. Alleen voor compatibiliteit met vertaalde code, aangezien er geen beheerde code wordt ondersteund aan de C++-kant. Dit is een statisch type zonder instantiediensten. U mag nooit instanties ervan maken op welke wijze dan ook.
type: docs
weight: 14
url: /nl/system.runtime.interopservices/marshal/
---
## Marshal klasse

Biedt een marshalling-implementatie. Alleen voor compatibiliteit met vertaalde code, aangezien er geen beheerde code wordt ondersteund aan de C++-kant. Dit is een statisch type zonder instantiediensten. U mag nooit instanties ervan maken op welke wijze dan ook.

```cpp
class Marshal
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static IntPtr [AllocHGlobal](./allochglobal/)(**int32_t**) | Reserveert niet-beheerd geheugen. |
| static IntPtr [AllocHGlobal](./allochglobal/)(IntPtr) | Reserveert niet-beheerd geheugen. |
| static void [Copy](./copy/)(const IntPtr, container\&&, int, int) | Implementeert de semantiek van public static void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static void [Copy](./copy/)(const void *, container\&&, int, int) | Implementeert de semantiek van public static void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static void [Copy](./copy/)(const container\&, int, void *, int) | Implementeert de semantiek van public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [Copy](./copy/)(const container\&, int, IntPtr, int) | Implementeert de semantiek van public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [FreeHGlobal](./freehglobal/)(IntPtr) | Geeft niet-beheerd geheugen vrij. |
| static TDelegate [GetDelegateForFunctionPointer](./getdelegateforfunctionpointer/)(IntPtr) | Converteert een niet-beheerde functie-pointer naar een delegate van een opgegeven type. |
| static **int32_t** [GetHRForException](./gethrforexception/)(const [System::Exception](../../system/exception/)\&) | Haalt HResult op uit de uitzondering. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr) | Creëert een beheerd [String](../../system/string/) van een niet-beheerde null-terminerende UTF8-string. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr, int) | Creëert een beheerd [String](../../system/string/) van een niet-beheerde UTF8-string. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr) | Creëert een beheerd [String](../../system/string/) van een niet-beheerde null-terminerende string. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr, int) | Creëert een beheerd [String](../../system/string/) van een niet-beheerde string. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr) | Creëert een beheerd [String](../../system/string/) van een niet-beheerde null-terminerende Unicode-string. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr, int) | Creëert een beheerd [String](../../system/string/) van een niet-beheerde Unicode-string. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr) | Creëert een beheerd [String](../../system/string/) van een niet-beheerde null-terminerende UTF8-string. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr, int) | Creëert een beheerd [String](../../system/string/) van een niet-beheerde UTF8-string. |
| static **uint8_t** [ReadByte](./readbyte/)(IntPtr, int) | Leest een byte uit het geheugen. |
| static **int16_t** [ReadInt16](./readint16/)(IntPtr, int) | Leest een short uit het geheugen. |
| static **int32_t** [ReadInt32](./readint32/)(IntPtr, int) | Leest een int uit het geheugen. |
| static IntPtr [ReadIntPtr](./readintptr/)(IntPtr, int) | Leest een IntPtr uit het geheugen. |
| static IntPtr [SecureStringToGlobalAllocAnsi](./securestringtoglobalallocansi/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Kopieert de inhoud van de opgegeven beveiligde string naar niet-beheerd geheugen, waarbij wordt geconverteerd naar ANSI-indeling. |
| static IntPtr [SecureStringToGlobalAllocUnicode](./securestringtoglobalallocunicode/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Kopieert de inhoud van de opgegeven beveiligde string naar niet-beheerd geheugen. |
| static IntPtr [StringToHGlobalAnsi](./stringtohglobalansi/)(const [String](../../system/string/)\&) | Kopieert de inhoud van een opgegeven string naar niet-beheerd geheugen. |
| static IntPtr [StringToHGlobalAuto](./stringtohglobalauto/)(const [String](../../system/string/)\&) | Kopieert de inhoud van een opgegeven string naar niet-beheerd geheugen, en converteert naar ANSI-indeling indien nodig. |
| static IntPtr [StringToHGlobalUni](./stringtohglobaluni/)(const [String](../../system/string/)\&) | Kopieert de inhoud van een opgegeven string naar niet-beheerd geheugen. |
| static void [WriteByte](./writebyte/)(IntPtr, int, **uint8_t**) | Schrijft een byte naar het geheugen. |
| static void [WriteByte](./writebyte/)(IntPtr, **uint8_t**) | Schrijft een byte naar het geheugen. |
| static void [WriteInt16](./writeint16/)(IntPtr, int, **int16_t**) | Schrijft een short naar het geheugen. |
| static void [WriteInt32](./writeint32/)(IntPtr, int, **int32_t**) | Schrijft een int naar het geheugen. |
| static void [WriteInt64](./writeint64/)(IntPtr, int, **int64_t**) | Schrijft een long naar het geheugen. |
| static void [WriteIntPtr](./writeintptr/)(IntPtr, int, IntPtr) | Schrijft een IntPtr naar het geheugen. |
| static void [ZeroFreeGlobalAllocAnsi](./zerofreeglobalallocansi/)(IntPtr) | Geeft een niet-beheerde string-pointer vrij die is toegewezen met de SecureStringToGlobalAllocAnsi-methode. |
| static void [ZeroFreeGlobalAllocUnicode](./zerofreeglobalallocunicode/)(IntPtr) | Geeft een niet-beheerde string-pointer vrij die is toegewezen met de SecureStringToGlobalAllocUnicode-methode. |

## Zie ook

* Naamruimte [System::Runtime::InteropServices](../)
* Bibliotheek [Aspose.Slides](../../)