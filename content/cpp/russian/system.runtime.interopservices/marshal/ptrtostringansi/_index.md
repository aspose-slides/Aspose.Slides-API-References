---
title: PtrToStringAnsi()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт управляемый String из неуправляемой нуль-терминированной UTF8-строки.
type: docs
weight: 274
url: /ru/system.runtime.interopservices/marshal/ptrtostringansi/
---
## Marshal::PtrToStringAnsi(IntPtr) метод

Создаёт управляемый [String](../../../system/string/) из неуправляемой нуль-терминированной строки UTF8.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAnsi(IntPtr ptr)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| ptr | IntPtr | Указатель на неуправляемую строку. |

### Возвращаемое значение

Управляемая строка.

## Marshal::PtrToStringAnsi(IntPtr, int) метод

Создаёт управляемый [String](../../../system/string/) из неуправляемой строки UTF8.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAnsi(IntPtr ptr, int length)
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
* Пространство имён [System::Runtime::InteropServices](../../)
* Библиотека [Aspose.Slides](../../../)