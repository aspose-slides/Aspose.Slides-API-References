---
title: PtrToStringAuto()
second_title: Справочник API Aspose.Slides для C++
description: Создает управляемый String из неуправляемой нуль-терминированной строки.
type: docs
weight: 287
url: /ru/system.runtime.interopservices/marshal/ptrtostringauto/
---
## Marshal::PtrToStringAuto(IntPtr) метод

Создает управляемый [String](../../../system/string/) из неуправляемой нуль-терминированной строки.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAuto(IntPtr ptr)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| ptr | IntPtr | Указатель на неуправляемую строку. |

### Возвращаемое значение

Управляемая строка.

## Marshal::PtrToStringAuto(IntPtr, int) метод

Создает управляемый [String](../../../system/string/) из неуправляемой строки.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAuto(IntPtr ptr, int length)
```

### Параметры

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