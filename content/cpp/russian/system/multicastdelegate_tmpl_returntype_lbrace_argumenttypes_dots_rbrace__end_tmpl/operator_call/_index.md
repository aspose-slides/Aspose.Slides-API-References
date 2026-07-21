---
title: operator()()
second_title: Справочник API Aspose.Slides для C++
description: Вызывает все делегаты, находящиеся в текущей коллекции делегатов. Делегаты вызываются в том же порядке, в котором они были добавлены в коллекцию. Оператор блокирует выполнение, пока делегаты исполняются.
type: docs
weight: 235
url: /ru/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/operator_call/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes...) const метод


Вызывает все делегаты, находящиеся в текущей коллекции делегатов. Делегаты вызываются в том же порядке, в котором они были добавлены в коллекцию. Оператор блокирует выполнение, пока делегаты исполняются.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes... args) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| args | ArgumentTypes... | Аргументы, передаваемые делегатам для вызова |

### Возвращаемое значение

Возвращаемое значение последнего вызываемого делегата

## См. также

* Класс [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)