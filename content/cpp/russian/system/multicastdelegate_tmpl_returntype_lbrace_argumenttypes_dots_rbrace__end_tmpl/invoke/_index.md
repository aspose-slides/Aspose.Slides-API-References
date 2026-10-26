---
title: invoke()
second_title: Aspose.Slides для C++ справка по API
description: Вызывает все делегаты, в данный момент присутствующие в коллекции делегатов. Делегаты вызываются в том же порядке, в котором они были добавлены в коллекцию. Метод блокируется, пока делегаты выполняются.
type: docs
weight: 222
url: /ru/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/invoke/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes...) const метод


Вызывает все делегаты, в данный момент присутствующие в коллекции делегатов. Делегаты вызываются в том же порядке, в котором они были добавлены в коллекцию. Метод блокируется, пока делегаты выполняются.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes... args) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| args | ArgumentTypes... | Аргументы, передаваемые делегатам для вызова |

### Возвращаемое значение

Возвращаемое значение последнего вызванного делегата

## См. также

* Класс [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)