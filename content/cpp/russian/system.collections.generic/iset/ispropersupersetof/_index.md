---
title: IsProperSupersetOf()
second_title: Справочник API Aspose.Slides для C++
description: Проверяет, является ли текущее множество строгим надмножеством другого контейнера.
type: docs
weight: 53
url: /ru/system.collections.generic/iset/ispropersupersetof/
---
## ISet::IsProperSupersetOf(IEnumerablePtr) метод

Проверяет, является ли текущее множество строгим надмножеством другого контейнера.

```cpp
virtual bool System::Collections::Generic::ISet<T>::IsProperSupersetOf(IEnumerablePtr other)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [IEnumerablePtr](../ienumerableptr/) | Подмножество для проверки. |

### Возвращаемое значение

true, если все элементы в **other** присутствуют в множестве и множество содержит больше элементов, чем **other**, иначе false.

## См. также

* Typedef [IEnumerablePtr](../ienumerableptr/)
* Class [ISet](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)