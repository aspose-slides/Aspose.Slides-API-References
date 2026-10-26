---
title: HashSet()
second_title: Aspose.Slides для C++ — справка API
description: Информация RTTI.
type: docs
weight: 1
url: /ru/system.collections.generic/hashset/hashset/
---
## HashSet::HashSet() конструктор


Информация RTTI.

```cpp
System::Collections::Generic::HashSet<T>::HashSet()
```

## Примечания


Создаёт пустой набор. 
## HashSet::HashSet(int) конструктор


Создаёт пустой набор с указанной ёмкостью.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(int capacity)
```

## HashSet::HashSet(const SharedPtr\<IEqualityComparer\<T\>\>\&) конструктор


Создаёт пустой набор, использующий указанный сравниватель равенства.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEqualityComparer<T>> &comparer)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<T\>\>\& | [Comparer](../../comparer/) объект, ассоциируемый с hashset. |

## HashSet::HashSet(const SharedPtr\<IEnumerable\<T\>\>\&) конструктор


Создаёт hashset на основе перечислимых значений.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEnumerable<T>> &items)
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [HashSet](../)
* Класс [IEqualityComparer](../../iequalitycomparer/)
* Класс [IEnumerable](../../ienumerable/)
* Пространство имён [System::Collections::Generic](../../)
* Библиотека [Aspose.Slides](../../../)