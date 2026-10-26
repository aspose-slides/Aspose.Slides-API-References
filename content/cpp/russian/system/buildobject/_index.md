---
title: BuildObject()
second_title: Aspose.Slides для C++: справочник API
description: Создать объект с разделяемым владением.
type: docs
weight: 2224
url: /ru/system/buildobject/
---
## System::BuildObject(Args\&&...) функция


Создать объект с разделяемым владением.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T, SharedPtr<T>> System::BuildObject(Args &&... args)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип объекта для создания |
| Args | Типы аргументов для конструктора объекта |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| args | Args\&&... | Аргументы, передаваемые конструктору объекта |

### Возвращаемое значение

ObjectBuilder, настроенный для создания shared pointer

## Замечания



Создает SharedPtr<T> и возвращает построитель для него 
[Object](../object/) создание должно быть завершено вызовом [Get()](../get/) 

## См. также

* Тип [SharedPtr](../sharedptr/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)