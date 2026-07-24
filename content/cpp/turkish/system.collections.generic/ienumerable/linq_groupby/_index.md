---
title: LINQ_GroupBy()
second_title: Aspose.Slides için C++ API Referansı
description: Bir dizinin öğelerini gruplar.
type: docs
weight: 287
url: /tr/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) method

Bir dizinin öğelerini gruplar.

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Key | keyPredicate tarafından döndürülen anahtarın türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | Her öğe için anahtarı çıkarmak için bir işlev. |

### Dönüş Değeri

[IEnumerable](../), nesnelerden oluşan bir dizi ve bir anahtar içeren bir nesnedir.

## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>, System::Func\<T, Element\>) method

Bir dizinin öğelerini gruplar.

```cpp
template<typename Key,typename Element> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate, System::Func<T, Element> elementSelector)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Key | keyPredicate tarafından döndürülen anahtarın türü |
| Element | elementSelector tarafından döndürülen öğenin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | Her öğe için anahtarı çıkarmak için bir işlev. |
| elementSelector | [System::Func](../../../system/func/)\<T, Element\> | Her öğe için değer anahtarını çıkarmak için bir işlev. |

### Dönüş Değeri

[IEnumerable](../), nesnelerden oluşan bir dizi ve bir anahtar içeren bir nesnedir.

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) method

```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>, System::Func\<Source, Element\>) method

```cpp
template<typename Key,typename Element> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate, System::Func<Source, Element> elementSelector)
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [IGrouping](../../../system.linq/igrouping/)
* Class [Func](../../../system/func/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)