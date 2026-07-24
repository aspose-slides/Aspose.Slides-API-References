---
title: Marshal
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt die Marshalling-Implementierung bereit. Nur zur Kompatibilität mit übersetztem Code, da auf der C++-Seite kein verwalteter Code unterstützt wird. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen.
type: docs
weight: 14
url: /de/system.runtime.interopservices/marshal/
---
## Marshal Klasse

Stellt eine Marshalling-Implementierung bereit. Nur zur Kompatibilität mit übersetztem Code, da auf der C++-Seite kein verwalteter Code unterstützt wird. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen.

```cpp
class Marshal
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static IntPtr [AllocHGlobal](./allochglobal/)(**int32_t**) | Allokiert nicht verwalteten Speicher. |
| static IntPtr [AllocHGlobal](./allochglobal/)(IntPtr) | Allokiert nicht verwalteten Speicher. |
| static void [Copy](./copy/)(const IntPtr, container\&&, int, int) | Implementiert die Semantik von public static void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static void [Copy](./copy/)(const void *, container\&&, int, int) | Implementiert die Semantik von public static void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static void [Copy](./copy/)(const container\&, int, void *, int) | Implementiert public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [Copy](./copy/)(const container\&, int, IntPtr, int) | Implementiert public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [FreeHGlobal](./freehglobal/)(IntPtr) | Gibt nicht verwalteten Speicher frei. |
| static TDelegate [GetDelegateForFunctionPointer](./getdelegateforfunctionpointer/)(IntPtr) | Konvertiert einen nicht verwalteten Funktionszeiger in ein delegate des angegebenen Typs. |
| static **int32_t** [GetHRForException](./gethrforexception/)(const [System::Exception](../../system/exception/)\&) | Liest HResult aus der Ausnahme. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr) | Erstellt ein verwaltetes [String](../../system/string/) aus einem nicht verwalteten nullterminierten UTF8-String. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr, int) | Erstellt ein verwaltetes [String](../../system/string/) aus einem nicht verwalteten UTF8-String. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr) | Erstellt ein verwaltetes [String](../../system/string/) aus einem nicht verwalteten nullterminierten String. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr, int) | Erstellt ein verwaltetes [String](../../system/string/) aus einem nicht verwalteten String. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr) | Erstellt ein verwaltetes [String](../../system/string/) aus einem nicht verwalteten nullterminierten unicode String. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr, int) | Erstellt ein verwaltetes [String](../../system/string/) aus einem nicht verwalteten unicode String. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr) | Erstellt ein verwaltetes [String](../../system/string/) aus einem nicht verwalteten nullterminierten UTF8-String. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr, int) | Erstellt ein verwaltetes [String](../../system/string/) aus einem nicht verwalteten UTF8-String. |
| static **uint8_t** [ReadByte](./readbyte/)(IntPtr, int) | Liest ein Byte aus dem Speicher. |
| static **int16_t** [ReadInt16](./readint16/)(IntPtr, int) | Liest ein Short aus dem Speicher. |
| static **int32_t** [ReadInt32](./readint32/)(IntPtr, int) | Liest ein Int aus dem Speicher. |
| static IntPtr [ReadIntPtr](./readintptr/)(IntPtr, int) | Liest ein IntPtr aus dem Speicher. |
| static IntPtr [SecureStringToGlobalAllocAnsi](./securestringtoglobalallocansi/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Kopiert den Inhalt des angegebenen secure string in nicht verwalteten Speicher, konvertiert ihn in das ANSI-Format. |
| static IntPtr [SecureStringToGlobalAllocUnicode](./securestringtoglobalallocunicode/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Kopiert den Inhalt des angegebenen secure string in nicht verwalteten Speicher. |
| static IntPtr [StringToHGlobalAnsi](./stringtohglobalansi/)(const [String](../../system/string/)\&) | Kopiert den Inhalt einer angegebenen string in nicht verwalteten Speicher. |
| static IntPtr [StringToHGlobalAuto](./stringtohglobalauto/)(const [String](../../system/string/)\&) | Kopiert den Inhalt einer angegebenen string in nicht verwalteten Speicher und konvertiert ihn bei Bedarf in das ANSI-Format. |
| static IntPtr [StringToHGlobalUni](./stringtohglobaluni/)(const [String](../../system/string/)\&) | Kopiert den Inhalt einer angegebenen string in nicht verwalteten Speicher. |
| static void [WriteByte](./writebyte/)(IntPtr, int, **uint8_t**) | Schreibt ein Byte in den Speicher. |
| static void [WriteByte](./writebyte/)(IntPtr, **uint8_t**) | Schreibt ein Byte in den Speicher. |
| static void [WriteInt16](./writeint16/)(IntPtr, int, **int16_t**) | Schreibt ein Short in den Speicher. |
| static void [WriteInt32](./writeint32/)(IntPtr, int, **int32_t**) | Schreibt ein Int in den Speicher. |
| static void [WriteInt64](./writeint64/)(IntPtr, int, **int64_t**) | Schreibt ein long in den Speicher. |
| static void [WriteIntPtr](./writeintptr/)(IntPtr, int, IntPtr) | Schreibt ein IntPtr in den Speicher. |
| static void [ZeroFreeGlobalAllocAnsi](./zerofreeglobalallocansi/)(IntPtr) | Gibt einen nicht verwalteten String-Zeiger frei, der mit der SecureStringToGlobalAllocAnsi-Methode alloziert wurde. |
| static void [ZeroFreeGlobalAllocUnicode](./zerofreeglobalallocunicode/)(IntPtr) | Gibt einen nicht verwalteten String-Zeiger frei, der mit der SecureStringToGlobalAllocUnicode-Methode alloziert wurde. |

## Siehe auch

* Namensraum [System::Runtime::InteropServices](../)
* Bibliothek [Aspose.Slides](../../)