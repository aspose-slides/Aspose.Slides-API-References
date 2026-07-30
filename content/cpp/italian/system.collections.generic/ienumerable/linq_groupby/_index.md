---
title: LINQ_GroupBy()
second_title: Riferimento API di Aspose.Slides per C++
description: Raggruppa gli elementi di una sequenza.
type: docs
weight: 287
url: /it/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) metodo


Raggruppa gli elementi di una sequenza.

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Key | Il tipo della chiave restituita da keyPredicate |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | Una funzione per estrarre la chiave per ogni elemento. |

### Valore restituito

Un [IEnumerable](../) che contiene una sequenza di oggetti e una chiave

## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>, System::Func\<T, Element\>) metodo


Raggruppa gli elementi di una sequenza.

```cpp
template<typename Key,typename Element> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate, System::Func<T, Element> elementSelector)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Key | Il tipo della chiave restituita da keyPredicate |
| Element | Il tipo dell'elemento restituito da elementSelector |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | Una funzione per estrarre la chiave per ogni elemento. |
| elementSelector | [System::Func](../../../system/func/)\<T, Element\> | Una funzione per estrarre il valore della chiave per ogni elemento. |

### Valore restituito

Un [IEnumerable](../) che contiene una sequenza di oggetti e una chiave

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) metodo




```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>, System::Func\<Source, Element\>) metodo




```cpp
template<typename Key,typename Element> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate, System::Func<Source, Element> elementSelector)
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [IGrouping](../../../system.linq/igrouping/)
* Class [Func](../../../system/func/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)