---
title: PtrToStringUni()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт управляемую строку из неуправляемой нуль-терминированной строки Unicode.
type: docs
weight: 300
url: /ru/system.runtime.interopservices/marshal/ptrtostringuni/
---
## Marshal::PtrToStringUni(IntPtr) метод

Создает управляемый [String](../../../system/string/) из неуправляемой нуль-терминированной строки Unicode.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringUni(IntPtr ptr)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| ptr | IntPtr | Указатель на неуправляемую строку. |

### Возвращаемое значение

Управляемая строка.

## Marshal::PtrToStringUni(IntPtr, int) метод

Создает управляемый [String](../../../system/string/) из неуправляемой строки Unicode.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringUni(IntPtr ptr, int length)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| ptr | IntPtr | Указатель на неуправляемую строку. |
| length | int | Длина неуправляемой строки. |

### Возвращаемое значение

Управляемая строка.

## См. также

* Класс [String](../../../system/string/)
* Класс [Marshal](../)
* Пространство имен [System::Runtime::InteropServices](../../)
* Библиотека [Aspose.Slides](../../../)