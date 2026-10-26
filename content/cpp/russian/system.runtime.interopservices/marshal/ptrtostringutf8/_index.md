---
title: PtrToStringUTF8()
second_title: Aspose.Slides для C++ справочник API
description: Создает управляемый String из неуправляемой нуль-терминированной UTF8-строки.
type: docs
weight: 313
url: /ru/system.runtime.interopservices/marshal/ptrtostringutf8/
---
## Marshal::PtrToStringUTF8(IntPtr) метод


Создает управляемый [String](../../../system/string/) из неуправляемой нуль-терминированной UTF8-строки.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringUTF8(IntPtr ptr)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| ptr | IntPtr | Указатель на неуправляемую строку. |

### Возвращаемое значение

Управляемая строка.

## Marshal::PtrToStringUTF8(IntPtr, int) метод


Создает управляемый [String](../../../system/string/) из неуправляемой UTF8-строки.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringUTF8(IntPtr ptr, int length)
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