---
title: cbegin()
second_title: Справочник API Aspose.Slides для C++
description: Метод доступа к методу cbegin() базовой коллекции. Компилируется только если SmartPtr_ является типом специализации с методом cbegin().
type: docs
weight: 404
url: /ru/system/smartptr/cbegin/
---
## SmartPtr::cbegin() const метод

Метод доступа для [cbegin()](./) метода базовой коллекции. Компилируется только если SmartPtr_ является типом специализации с методом [cbegin()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::cbegin() const -> decltype(std::declval<const Q>().cbegin())
```

### Возвращаемое значение

итератор к началу коллекции

## См. также

* Класс [SmartPtr](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)