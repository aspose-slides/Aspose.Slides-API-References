---
title: Marshal
second_title: Referencia de la API de Aspose.Slides para C++
description: Proporciona una implementación de marshaling. Sólo para compatibilidad con código traducido, ya que no se admite código administrado en el lado C++. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.
type: docs
weight: 14
url: /es/system.runtime.interopservices/marshal/
---
## Marshal clase

Proporciona una implementación de marshaling. Sólo para compatibilidad con código traducido, ya que no se admite código administrado en el lado C++. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.

```cpp
class Marshal
```

## Métodos

| Method | Descripción |
| --- | --- |
| static IntPtr [AllocHGlobal](./allochglobal/)(**int32_t**) | Reserva memoria no administrada. |
| static IntPtr [AllocHGlobal](./allochglobal/)(IntPtr) | Reserva memoria no administrada. |
| static void [Copy](./copy/)(const IntPtr, container\&&, int, int) | Implementa la semántica del método público estático void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static void [Copy](./copy/)(const void *, container\&&, int, int) | Implementa la semántica del método público estático void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static void [Copy](./copy/)(const container\&, int, void *, int) | Implementa la semántica del método público estático void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [Copy](./copy/)(const container\&, int, IntPtr, int) | Implementa la semántica del método público estático void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [FreeHGlobal](./freehglobal/)(IntPtr) | Libera memoria no administrada. |
| static TDelegate [GetDelegateForFunctionPointer](./getdelegateforfunctionpointer/)(IntPtr) | Convierte un puntero a función no administrado en un delegado del tipo especificado. |
| static **int32_t** [GetHRForException](./gethrforexception/)(const [System::Exception](../../system/exception/)\&) | Obtiene HResult de la excepción. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr) | Crea un [String](../../system/string/) administrado a partir de una cadena UTF8 terminada en cero no administrada. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr, int) | Crea un [String](../../system/string/) administrado a partir de una cadena UTF8 no administrada. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr) | Crea un [String](../../system/string/) administrado a partir de una cadena terminada en cero no administrada. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr, int) | Crea un [String](../../system/string/) administrado a partir de una cadena no administrada. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr) | Crea un [String](../../system/string/) administrado a partir de una cadena Unicode terminada en cero no administrada. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr, int) | Crea un [String](../../system/string/) administrado a partir de una cadena Unicode no administrada. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr) | Crea un [String](../../system/string/) administrado a partir de una cadena UTF8 terminada en cero no administrada. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr, int) | Crea un [String](../../system/string/) administrado a partir de una cadena UTF8 no administrada. |
| static **uint8_t** [ReadByte](./readbyte/)(IntPtr, int) | Lee un byte de la memoria. |
| static **int16_t** [ReadInt16](./readint16/)(IntPtr, int) | Lee un short de la memoria. |
| static **int32_t** [ReadInt32](./readint32/)(IntPtr, int) | Lee un int de la memoria. |
| static IntPtr [ReadIntPtr](./readintptr/)(IntPtr, int) | Lee un IntPtr de la memoria. |
| static IntPtr [SecureStringToGlobalAllocAnsi](./securestringtoglobalallocansi/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Copia el contenido de la cadena segura especificada en memoria no administrada, convirtiéndola al formato ANSI. |
| static IntPtr [SecureStringToGlobalAllocUnicode](./securestringtoglobalallocunicode/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Copia el contenido de la cadena segura especificada en memoria no administrada. |
| static IntPtr [StringToHGlobalAnsi](./stringtohglobalansi/)(const [String](../../system/string/)\&) | Copia el contenido de la cadena especificada en memoria no administrada. |
| static IntPtr [StringToHGlobalAuto](./stringtohglobalauto/)(const [String](../../system/string/)\&) | Copia el contenido de la cadena especificada en memoria no administrada, convirtiéndola al formato ANSI si es necesario. |
| static IntPtr [StringToHGlobalUni](./stringtohglobaluni/)(const [String](../../system/string/)\&) | Copia el contenido de la cadena especificada en memoria no administrada. |
| static void [WriteByte](./writebyte/)(IntPtr, int, **uint8_t**) | Escribe un byte en la memoria. |
| static void [WriteByte](./writebyte/)(IntPtr, **uint8_t**) | Escribe un byte en la memoria. |
| static void [WriteInt16](./writeint16/)(IntPtr, int, **int16_t**) | Escribe un short en la memoria. |
| static void [WriteInt32](./writeint32/)(IntPtr, int, **int32_t**) | Escribe un int en la memoria. |
| static void [WriteInt64](./writeint64/)(IntPtr, int, **int64_t**) | Escribe un long en la memoria. |
| static void [WriteIntPtr](./writeintptr/)(IntPtr, int, IntPtr) | Escribe un IntPtr en la memoria. |
| static void [ZeroFreeGlobalAllocAnsi](./zerofreeglobalallocansi/)(IntPtr) | Libera el puntero a cadena no administrada que fue asignado mediante el método SecureStringToGlobalAllocAnsi. |
| static void [ZeroFreeGlobalAllocUnicode](./zerofreeglobalallocunicode/)(IntPtr) | Libera el puntero a cadena no administrada que fue asignado mediante el método SecureStringToGlobalAllocUnicode. |

## Ver también

* Namespace [System::Runtime::InteropServices](../)
* Library [Aspose.Slides](../../)