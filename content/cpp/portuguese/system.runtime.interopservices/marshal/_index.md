---
title: Marshal
second_title: Aspose.Slides para C++ Referência da API
description: Fornece implementação de marshaling. Apenas para compatibilidade com código traduzido, pois nenhum código gerenciado é suportado no lado C++. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por qualquer meio.
type: docs
weight: 14
url: /pt/system.runtime.interopservices/marshal/
---
## classe Marshal

Fornece implementação de marshaling. Apenas para compatibilidade com código traduzido, pois nenhum código gerenciado é suportado no lado C++. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por qualquer meio.

```cpp
class Marshal
```

## Métodos

| Método | Descrição |
| --- | --- |
| static IntPtr [AllocHGlobal](./allochglobal/)(**int32_t**) | Aloca memória não gerenciada. |
| static IntPtr [AllocHGlobal](./allochglobal/)(IntPtr) | Aloca memória não gerenciada. |
| static void [Copy](./copy/)(const IntPtr, container\&&, int, int) | Implementa a semântica do método public static void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static void [Copy](./copy/)(const void *, container\&&, int, int) | Implementa a semântica do método public static void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static void [Copy](./copy/)(const container\&, int, void *, int) | Implementa a semântica do método public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [Copy](./copy/)(const container\&, int, IntPtr, int) | Implementa a semântica do método public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [FreeHGlobal](./freehglobal/)(IntPtr) | Libera memória não gerenciada. |
| static TDelegate [GetDelegateForFunctionPointer](./getdelegateforfunctionpointer/)(IntPtr) | Converte um ponteiro de função não gerenciado para um delegate do tipo especificado. |
| static **int32_t** [GetHRForException](./gethrforexception/)(const [System::Exception](../../system/exception/)\&) | Obtém HResult da exceção. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr) | Cria um [String](../../system/string/) gerenciado a partir de uma string UTF8 terminada em zero não gerenciada. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr, int) | Cria um [String](../../system/string/) gerenciado a partir de uma string UTF8 não gerenciada. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr) | Cria um [String](../../system/string/) gerenciado a partir de uma string terminada em zero não gerenciada. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr, int) | Cria um [String](../../system/string/) gerenciado a partir de uma string não gerenciada. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr) | Cria um [String](../../system/string/) gerenciado a partir de uma string Unicode terminada em zero não gerenciada. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr, int) | Cria um [String](../../system/string/) gerenciado a partir de uma string Unicode não gerenciada. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr) | Cria um [String](../../system/string/) gerenciado a partir de uma string UTF8 terminada em zero não gerenciada. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr, int) | Cria um [String](../../system/string/) gerenciado a partir de uma string UTF8 não gerenciada. |
| static **uint8_t** [ReadByte](./readbyte/)(IntPtr, int) | Lê byte da memória. |
| static **int16_t** [ReadInt16](./readint16/)(IntPtr, int) | Lê short da memória. |
| static **int32_t** [ReadInt32](./readint32/)(IntPtr, int) | Lê int da memória. |
| static IntPtr [ReadIntPtr](./readintptr/)(IntPtr, int) | Lê IntPtr da memória. |
| static IntPtr [SecureStringToGlobalAllocAnsi](./securestringtoglobalallocansi/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Copia o conteúdo da secure string especificada para memória não gerenciada, convertendo para formato ANSI. |
| static IntPtr [SecureStringToGlobalAllocUnicode](./securestringtoglobalallocunicode/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Copia o conteúdo da secure string especificada para memória não gerenciada. |
| static IntPtr [StringToHGlobalAnsi](./stringtohglobalansi/)(const [String](../../system/string/)\&) | Copia o conteúdo de uma string especificada para memória não gerenciada. |
| static IntPtr [StringToHGlobalAuto](./stringtohglobalauto/)(const [String](../../system/string/)\&) | Copia o conteúdo de uma string especificada para memória não gerenciada, convertendo para formato ANSI se necessário. |
| static IntPtr [StringToHGlobalUni](./stringtohglobaluni/)(const [String](../../system/string/)\&) | Copia o conteúdo de uma string especificada para memória não gerenciada. |
| static void [WriteByte](./writebyte/)(IntPtr, int, **uint8_t**) | Escreve byte na memória. |
| static void [WriteByte](./writebyte/)(IntPtr, **uint8_t**) | Escreve byte na memória. |
| static void [WriteInt16](./writeint16/)(IntPtr, int, **int16_t**) | Escreve short na memória. |
| static void [WriteInt32](./writeint32/)(IntPtr, int, **int32_t**) | Escreve int na memória. |
| static void [WriteInt64](./writeint64/)(IntPtr, int, **int64_t**) | Escreve long na memória. |
| static void [WriteIntPtr](./writeintptr/)(IntPtr, int, IntPtr) | Escreve IntPtr na memória. |
| static void [ZeroFreeGlobalAllocAnsi](./zerofreeglobalallocansi/)(IntPtr) | Libera ponteiro de string não gerenciada que foi alocado usando o método SecureStringToGlobalAllocAnsi. |
| static void [ZeroFreeGlobalAllocUnicode](./zerofreeglobalallocunicode/)(IntPtr) | Libera ponteiro de string não gerenciada que foi alocado usando o método SecureStringToGlobalAllocUnicode. |

## Veja Também

* Namespace [System::Runtime::InteropServices](../)
* Biblioteca [Aspose.Slides](../../)