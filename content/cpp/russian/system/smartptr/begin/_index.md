---
title: begin()
second_title: Справочник API Aspose.Slides для C++
description: Аксессор для метода begin() подлежащей коллекции. Компилируется только если SmartPtr_ является типом специализации с методом begin().
type: docs
weight: 378
url: /ru/system/smartptr/begin/
---
## SmartPtr::begin() метод


Аксессор для метода [begin()](./) подлежащей коллекции. Компилируется только если SmartPtr_ является типом специализации с методом [begin()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() -> decltype(std::declval<Q>().begin())
```


### Возвращаемое значение

iterator к началу коллекции

## SmartPtr::begin() const метод


Аксессор для метода [begin()](./) подлежащей коллекции. Компилируется только если SmartPtr_ является типом специализации с методом [begin()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() const -> decltype(std::declval<const Q>().begin())
```


### Возвращаемое значение

iterator к началу коллекции

## См. также

* Класс [SmartPtr](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)