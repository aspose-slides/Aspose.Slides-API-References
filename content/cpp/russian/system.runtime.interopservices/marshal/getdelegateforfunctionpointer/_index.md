---
title: GetDelegateForFunctionPointer()
second_title: Aspose.Slides для C++ справочник API
description: Преобразует неуправляемый указатель на функцию в делегат указанного типа.
type: docs
weight: 14
url: /ru/system.runtime.interopservices/marshal/getdelegateforfunctionpointer/
---
## Marshal::GetDelegateForFunctionPointer(IntPtr) метод


Преобразует неуправляемый указатель на функцию в делегат указанного типа.

```cpp
template<typename TDelegate> static TDelegate System::Runtime::InteropServices::Marshal::GetDelegateForFunctionPointer(IntPtr ptr)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TDelegate | Тип делегата, который нужно вернуть. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| ptr | IntPtr | Неуправляемый указатель на функцию для преобразования. |

### Возвращаемое значение

Экземпляр указанного типа делегата.
## Примечания



Простейший шаблон для будущей реализации 

## См. также

* Класс [Marshal](../)
* Пространство имён [System::Runtime::InteropServices](../../)
* Библиотека [Aspose.Slides](../../../)