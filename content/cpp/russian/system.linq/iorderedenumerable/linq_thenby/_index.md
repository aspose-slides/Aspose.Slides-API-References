---
title: LINQ_ThenBy()
second_title: Справочник API Aspose.Slides для C++
description: Выполняет последующее упорядочивание элементов в последовательности по возрастанию в соответствии с ключом.
type: docs
weight: 27
url: /ru/system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) method


Выполняет последующий порядок элементов в последовательности по возрастанию в соответствии с ключом.

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Key | Тип ключа, возвращаемого keySelector. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| keySelector | const [Func](../../../system/func/)\<T, Key\>\& | Функция для извлечения ключа из каждого элемента. |

### Возвращаемое значение

[System::Linq::IOrderedEnumerable](../) элементы которого отсортированы в соответствии с ключом.

## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) method




```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../)
* Class [Func](../../../system/func/)
* Namespace [System::Linq](../../)
* Library [Aspose.Slides](../../../)