---
title: get_pointer()
second_title: Справочник API Aspose.Slides для C++
description: Получает объект, на который указывает умный указатель.
type: docs
weight: 2913
url: /ru/system/get_pointer/
---
## System::get_pointer(System::SmartPtr\<T\> const\&) функция


Получает объект, на который указывает умный указатель.

```cpp
template<class T> T * System::get_pointer(System::SmartPtr<T> const &x)
```


### Шаблонные параметры

| Parameter | Description |
| --- | --- |
| T | Pointee type. |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| x | [System::SmartPtr](../smartptr/)\<T\> const\& | Исходный умный указатель. |

### Возвращаемое значение

Необработанный указатель на объект, на который ссылается переданный умный указатель.

## См. также

* Класс [SmartPtr](../smartptr/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)