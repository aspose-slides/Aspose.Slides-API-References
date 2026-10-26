---
title: LINQ_ThenBy()
second_title: Aspose.Slides för C++ API-referens
description: Utför en efterföljande sortering av elementen i en sekvens i stigande ordning enligt en nyckel.
type: docs
weight: 27
url: /sv/system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) method


Utför en efterföljande sortering av elementen i en sekvens i stigande ordning enligt en nyckel.

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Key | Typen av nyckeln som returneras av keySelector. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| keySelector | const [Func](../../../system/func/)\<T, Key\>\& | En funktion för att extrahera en nyckel från varje element. |

### Returvärde

[System::Linq::IOrderedEnumerable](../) vars element är sorterade enligt en nyckel.

## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) method




```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IOrderedEnumerable](../)
* Klass [Func](../../../system/func/)
* Namnrymd [System::Linq](../../)
* Bibliotek [Aspose.Slides](../../../)