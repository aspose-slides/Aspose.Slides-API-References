---
title: Marshal
second_title: Справочник API Aspose.Slides для C++
description: Предоставляет реализацию маршаллинга. Только для совместимости с транслированным кодом, поскольку управляемый код не поддерживается со стороны C++. Это статический тип без сервисов экземпляра. Вам никогда не следует создавать его экземпляры каким-либо способом.
type: docs
weight: 14
url: /ru/system.runtime.interopservices/marshal/
---
## Marshal класс

Предоставляет реализацию маршаллинга. Только для совместимости с транслированным кодом, поскольку управляемый код не поддерживается со стороны C++. Это статический тип без сервисов экземпляра. Вам никогда не следует создавать его экземпляры каким-либо способом.

```cpp
class Marshal
```

## Методы

| Метод | Описание |
| --- | --- |
| static IntPtr [AllocHGlobal](./allochglobal/)(**int32_t**) | Выделяет неуправляемую память. |
| static IntPtr [AllocHGlobal](./allochglobal/)(IntPtr) | Выделяет неуправляемую память. |
| static void [Copy](./copy/)(const IntPtr, container\&&, int, int) | Реализует семантику public static void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static void [Copy](./copy/)(const void *, container\&&, int, int) | Реализует семантику public static void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static void [Copy](./copy/)(const container\&, int, void *, int) | Реализует семантику public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [Copy](./copy/)(const container\&, int, IntPtr, int) | Реализует семантику public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [FreeHGlobal](./freehglobal/)(IntPtr) | Освобождает неуправляемую память. |
| static TDelegate [GetDelegateForFunctionPointer](./getdelegateforfunctionpointer/)(IntPtr) | Преобразует неуправляемый указатель на функцию в делегат указанного типа. |
| static **int32_t** [GetHRForException](./gethrforexception/)(const [System::Exception](../../system/exception/)\&) | Получает HResult из исключения. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr) | Создаёт управляемый [String](../../system/string/) из неуправляемой нул-терминированной UTF8-строки. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr, int) | Создаёт управляемый [String](../../system/string/) из неуправляемой UTF8-строки. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr) | Создаёт управляемый [String](../../system/string/) из неуправляемой нул-терминированной строки. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr, int) | Создаёт управляемый [String](../../system/string/) из неуправляемой строки. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr) | Создаёт управляемый [String](../../system/string/) из неуправляемой нул-терминированной Unicode-строки. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr, int) | Создаёт управляемый [String](../../system/string/) из неуправляемой Unicode-строки. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr) | Создаёт управляемый [String](../../system/string/) из неуправляемой нул-терминированной UTF8-строки. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr, int) | Создаёт управляемый [String](../../system/string/) из неуправляемой UTF8-строки. |
| static **uint8_t** [ReadByte](./readbyte/)(IntPtr, int) | Читает байт из памяти. |
| static **int16_t** [ReadInt16](./readint16/)(IntPtr, int) | Читает short из памяти. |
| static **int32_t** [ReadInt32](./readint32/)(IntPtr, int) | Читает int из памяти. |
| static IntPtr [ReadIntPtr](./readintptr/)(IntPtr, int) | Читает IntPtr из памяти. |
| static IntPtr [SecureStringToGlobalAllocAnsi](./securestringtoglobalallocansi/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Копирует содержимое указанной защищённой строки в неуправляемую память, преобразуя в формат ANSI. |
| static IntPtr [SecureStringToGlobalAllocUnicode](./securestringtoglobalallocunicode/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Копирует содержимое указанной защищённой строки в неуправляемую память. |
| static IntPtr [StringToHGlobalAnsi](./stringtohglobalansi/)(const [String](../../system/string/)\&) | Копирует содержимое указанной строки в неуправляемую память. |
| static IntPtr [StringToHGlobalAuto](./stringtohglobalauto/)(const [String](../../system/string/)\&) | Копирует содержимое указанной строки в неуправляемую память, при необходимости преобразуя в формат ANSI. |
| static IntPtr [StringToHGlobalUni](./stringtohglobaluni/)(const [String](../../system/string/)\&) | Копирует содержимое указанной строки в неуправляемую память. |
| static void [WriteByte](./writebyte/)(IntPtr, int, **uint8_t**) | Записывает байт в память. |
| static void [WriteByte](./writebyte/)(IntPtr, **uint8_t**) | Записывает байт в память. |
| static void [WriteInt16](./writeint16/)(IntPtr, int, **int16_t**) | Записывает short в память. |
| static void [WriteInt32](./writeint32/)(IntPtr, int, **int32_t**) | Записывает int в память. |
| static void [WriteInt64](./writeint64/)(IntPtr, int, **int64_t**) | Записывает long в память. |
| static void [WriteIntPtr](./writeintptr/)(IntPtr, int, IntPtr) | Записывает IntPtr в память. |
| static void [ZeroFreeGlobalAllocAnsi](./zerofreeglobalallocansi/)(IntPtr) | Освобождает неуправляемый указатель строки, выделенный методом SecureStringToGlobalAllocAnsi. |
| static void [ZeroFreeGlobalAllocUnicode](./zerofreeglobalallocunicode/)(IntPtr) | Освобождает неуправляемый указатель строки, выделенный методом SecureStringToGlobalAllocUnicode. |

## См. также

* Namespace [System::Runtime::InteropServices](../)
* Library [Aspose.Slides](../../)