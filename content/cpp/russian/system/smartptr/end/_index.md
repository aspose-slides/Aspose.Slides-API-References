---
title: end()
second_title: Справочник API Aspose.Slides для C++
description: Доступ к методу end() подлежащей коллекции. Компилируется только если SmartPtr_ является типом специализации с методом end().
type: docs
weight: 391
url: /ru/system/smartptr/end/
---
## SmartPtr::end() метод


Доступ к методу [end()](./) подлежащей коллекции. Компилируется только если SmartPtr_ является типом специализации с методом [end()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::end() -> decltype(std::declval<Q>().end())
```


### Возвращаемое значение

итератор к концу коллекции

## SmartPtr::end() const метод


Доступ к методу [end()](./) подлежащей коллекции. Компилируется только если SmartPtr_ является типом специализации с методом [end()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::end() const -> decltype(std::declval<const Q>().end())
```


### Возвращаемое значение

итератор к концу коллекции

## См. также

* Класс [SmartPtr](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)