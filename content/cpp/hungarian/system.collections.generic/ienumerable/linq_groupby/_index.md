---
title: LINQ_GroupBy()
second_title: Aspose.Slides C++ API referencia
description: Csoportosítja a sorozat elemeit.
type: docs
weight: 287
url: /hu/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) metódus


Csoportosítja a sorozat elemeit.

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| Key | A keyPredicate által visszaadott kulcs típusa |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | Függvény, amely minden elemhez kinyeri a kulcsot. |

### Visszatérési érték

Egy [IEnumerable](../) amely objektumok sorozatát és egy kulcsot tartalmaz

## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>, System::Func\<T, Element\>) metódus


Csoportosítja a sorozat elemeit.

```cpp
template<typename Key,typename Element> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate, System::Func<T, Element> elementSelector)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| Key | A keyPredicate által visszaadott kulcs típusa |
| Element | Az elementSelector által visszaadott elem típusa |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | Függvény, amely minden elemhez kinyeri a kulcsot. |
| elementSelector | [System::Func](../../../system/func/)\<T, Element\> | Függvény, amely minden elemhez kinyeri az érték kulcsát. |

### Visszatérési érték

Egy [IEnumerable](../) amely objektumok sorozatát és egy kulcsot tartalmaz

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) metódus




```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>, System::Func\<Source, Element\>) metódus




```cpp
template<typename Key,typename Element> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate, System::Func<Source, Element> elementSelector)
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IEnumerable](../)
* Osztály [IGrouping](../../../system.linq/igrouping/)
* Osztály [Func](../../../system/func/)
* Névtér [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)