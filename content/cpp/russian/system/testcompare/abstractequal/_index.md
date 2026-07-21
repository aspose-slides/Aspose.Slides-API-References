---
title: AbstractEqual()
second_title: Справочник API Aspose.Slides для C++
description: Сравнивает две коллекции неизвестного типа.
type: docs
weight: 14
url: /ru/system/testcompare/abstractequal/
---
## TestCompare::AbstractEqual(SCG::ICollection\<T\> *const, SCG::ICollection\<T\> *const) метод


Сравнивает две коллекции неизвестного типа.

```cpp
template<typename T> static bool System::TestCompare::AbstractEqual(SCG::ICollection<T> *const collA, SCG::ICollection<T> *const collB)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элемента коллекции. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| collA | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | Левая коллекция. |
| collB | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | Правая коллекция. |

### Возвращаемое значение

true, если коллекции совпадают (например, обе равны null), или если размеры совпадают и элементы совпадают, false в противном случае.

## См. также

* Класс [ICollection](../../../system.collections.generic/icollection/)
* Структура [TestCompare](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)