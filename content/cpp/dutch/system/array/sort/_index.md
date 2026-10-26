---
title: Sort()
second_title: Aspose.Slides voor C++ API-referentie
description: Sorteert elementen in de opgegeven array met de standaard comparer.
type: docs
weight: 742
url: /nl/system/array/sort/
---
## Array::Sort(const ArrayPtr\<Type\>\&) method


Sorteert elementen in de opgegeven array met de standaard comparer.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Doelarray |
|  |  |  |

## Array::Sort(const ArrayPtr\<Type\>\&, int, int) method


Sorteert een bereik van elementen in de opgegeven array met de standaard comparer.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Doelarray |
| startIndex | int | De index die het begin van het te sorteren bereik van elementen aangeeft |
| count | int | De grootte van het te sorteren bereik van elementen |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) method


Sorteert elementen in de opgegeven array met de opgegeven comparer.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Doelarray |
| comparator | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<T\>\>\& | IComparer<T>-object gebruikt om elementen van de array te vergelijken |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) method


NIET GEÏMPLENTEERD.

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```


## Array::Sort(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) method


Sorteert elementen in de opgegeven array met de opgegeven vergelijking.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const System::Comparison<T> &comparison)
```

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) method


Sorteert twee arrays, de een met sleutels en de andere met overeenkomstige items, op basis van de waarden van de array met sleutels, waarvan de elementen worden vergeleken met operator<.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TKey | Het type van de elementen in de **keys** array |
| TValue | het type van de elementen in de **items** array |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) die de sleutelwaarden bevat |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) die items bevat die zijn gekoppeld aan de sleutelwaarden in **keys** array |

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) method


Sorteert twee arrays, de een met sleutels en de andere met overeenkomstige items, op basis van de waarden van de array met sleutels, waarvan de elementen worden vergeleken met de standaard comparer.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TKey | Het type van de elementen in de **keys** array |
| TValue | het type van de elementen in de **items** array |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) die de sleutelwaarden bevat |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) die items bevat die zijn gemapt op de sleutelwaarden in **keys** array |
| index | int | De index die het begin van het te sorteren bereik aangeeft |
| length | int | Het aantal elementen in het te sorteren bereik |

## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Methode [Type](../../object/type/)
* Klasse [Array](../)
* Klasse [IComparer](../../../system.collections.generic/icomparer/)
* Klasse [Comparison](../../comparison/)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)