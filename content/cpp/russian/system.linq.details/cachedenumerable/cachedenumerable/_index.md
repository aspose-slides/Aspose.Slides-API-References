---
title: CachedEnumerable()
second_title: Aspose.Slides для C++: справочник API
description: 
type: docs
weight: 1
url: /ru/system.linq.details/cachedenumerable/cachedenumerable/
---
## CachedEnumerable::CachedEnumerable(System::Func\<bool\>) конструктор


```cpp
System::Linq::Details::CachedEnumerable<TItem>::CachedEnumerable(System::Func<bool> requestNext)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| requestNext | [System::Func](../../../system/func/)\<**bool**\> | обратный вызов, который вызывается, когда необходим следующий элемент. обратный вызов должен использовать метод Add для вставки следующего элемента и возвращать false, когда элементов больше нет |

## См. также

* Класс [Func](../../../system/func/)
* Класс [CachedEnumerable](../)
* Пространство имён [System::Linq::Details](../../)
* Библиотека [Aspose.Slides](../../../)