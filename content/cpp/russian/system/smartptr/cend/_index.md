---
title: cend()
second_title: Aspose.Slides для C++ справочник API
description: Аксессор для метода cend() внутренней коллекции. Компилируется только, если SmartPtr_ является типом специализации с методом cend().
type: docs
weight: 417
url: /ru/system/smartptr/cend/
---
## SmartPtr::cend() const method

Аксессор для метода [cend()](./) внутренней коллекции. Компилируется только, если SmartPtr_ является типом специализации с методом [cend()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::cend() const -> decltype(std::declval<const Q>().cend())
```

### Возвращаемое значение

итератор до конца коллекции

## См. также

* Класс [SmartPtr](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)