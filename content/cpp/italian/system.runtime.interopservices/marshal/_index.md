---
title: Marshal
second_title: Riferimento API di Aspose.Slides per C++
description: Fornisce l'implementazione del marshalling. Solo per compatibilità con il codice tradotto, poiché sul lato C++ non è supportato alcun codice gestito. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.
type: docs
weight: 14
url: /it/system.runtime.interopservices/marshal/
---
## Marshal classe

Fornisce l'implementazione del marshalling. Solo per compatibilità con il codice tradotto, poiché sul lato C++ non è supportato alcun codice gestito. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.

```cpp
class Marshal
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static IntPtr [AllocHGlobal](./allochglobal/)(**int32_t**) | Alloca memoria non gestita. |
| static IntPtr [AllocHGlobal](./allochglobal/)(IntPtr) | Alloca memoria non gestita. |
| static void [Copy](./copy/)(const IntPtr, container\&&, int, int) | Implementa la semantica del metodo pubblico static void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static void [Copy](./copy/)(const void *, container\&&, int, int) | Implementa la semantica del metodo pubblico static void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static void [Copy](./copy/)(const container\&, int, void *, int) | Implementa la semantica del metodo pubblico static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [Copy](./copy/)(const container\&, int, IntPtr, int) | Implementa la semantica del metodo pubblico static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [FreeHGlobal](./freehglobal/)(IntPtr) | Libera memoria non gestita. |
| static TDelegate [GetDelegateForFunctionPointer](./getdelegateforfunctionpointer/)(IntPtr) | Converte un puntatore a funzione non gestito in un delegate di tipo specificato. |
| static **int32_t** [GetHRForException](./gethrforexception/)(const [System::Exception](../../system/exception/)\&) | Ottiene HResult dall'eccezione. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr) | Crea un [String](../../system/string/) gestito da una stringa UTF8 terminata con zero non gestita. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr, int) | Crea un [String](../../system/string/) gestito da una stringa UTF8 non gestita. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr) | Crea un [String](../../system/string/) gestito da una stringa terminata con zero non gestita. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr, int) | Crea un [String](../../system/string/) gestito da una stringa non gestita. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr) | Crea un [String](../../system/string/) gestito da una stringa Unicode terminata con zero non gestita. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr, int) | Crea un [String](../../system/string/) gestito da una stringa Unicode non gestita. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr) | Crea un [String](../../system/string/) gestito da una stringa UTF8 terminata con zero non gestita. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr, int) | Crea un [String](../../system/string/) gestito da una stringa UTF8 non gestita. |
| static **uint8_t** [ReadByte](./readbyte/)(IntPtr, int) | Legge un byte dalla memoria. |
| static **int16_t** [ReadInt16](./readint16/)(IntPtr, int) | Legge un short dalla memoria. |
| static **int32_t** [ReadInt32](./readint32/)(IntPtr, int) | Legge un int dalla memoria. |
| static IntPtr [ReadIntPtr](./readintptr/)(IntPtr, int) | Legge un IntPtr dalla memoria. |
| static IntPtr [SecureStringToGlobalAllocAnsi](./securestringtoglobalallocansi/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Copia il contenuto della secure string specificata nella memoria non gestita, convertendo in formato ANSI. |
| static IntPtr [SecureStringToGlobalAllocUnicode](./securestringtoglobalallocunicode/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Copia il contenuto della secure string specificata nella memoria non gestita. |
| static IntPtr [StringToHGlobalAnsi](./stringtohglobalansi/)(const [String](../../system/string/)\&) | Copia il contenuto di una stringa specificata nella memoria non gestita. |
| static IntPtr [StringToHGlobalAuto](./stringtohglobalauto/)(const [String](../../system/string/)\&) | Copia il contenuto di una stringa specificata nella memoria non gestita, convertendo in formato ANSI se necessario. |
| static IntPtr [StringToHGlobalUni](./stringtohglobaluni/)(const [String](../../system/string/)\&) | Copia il contenuto di una stringa specificata nella memoria non gestita. |
| static void [WriteByte](./writebyte/)(IntPtr, int, **uint8_t**) | Scrive un byte nella memoria. |
| static void [WriteByte](./writebyte/)(IntPtr, **uint8_t**) | Scrive un byte nella memoria. |
| static void [WriteInt16](./writeint16/)(IntPtr, int, **int16_t**) | Scrive un short nella memoria. |
| static void [WriteInt32](./writeint32/)(IntPtr, int, **int32_t**) | Scrive un int nella memoria. |
| static void [WriteInt64](./writeint64/)(IntPtr, int, **int64_t**) | Scrive un long nella memoria. |
| static void [WriteIntPtr](./writeintptr/)(IntPtr, int, IntPtr) | Scrive un IntPtr nella memoria. |
| static void [ZeroFreeGlobalAllocAnsi](./zerofreeglobalallocansi/)(IntPtr) | Libera il puntatore a stringa non gestita allocato usando il metodo SecureStringToGlobalAllocAnsi. |
| static void [ZeroFreeGlobalAllocUnicode](./zerofreeglobalallocunicode/)(IntPtr) | Libera il puntatore a stringa non gestita allocato usando il metodo SecureStringToGlobalAllocUnicode. |

## Vedi anche

* Spazio dei nomi [System::Runtime::InteropServices](../)
* Libreria [Aspose.Slides](../../)