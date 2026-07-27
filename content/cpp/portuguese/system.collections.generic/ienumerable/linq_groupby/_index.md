---
title: LINQ_GroupBy()
second_title: Referência da API Aspose.Slides para C++
description: Agrupa os elementos de uma sequência.
type: docs
weight: 287
url: /pt/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) método

Agrupa os elementos de uma sequência.

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Key | O tipo da chave retornada por keyPredicate |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | Uma função para extrair a chave de cada elemento. |

### Valor de retorno

Um [IEnumerable](../) que contém uma sequência de objetos e uma chave

## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>, System::Func\<T, Element\>) método

Agrupa os elementos de uma sequência.

```cpp
template<typename Key,typename Element> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate, System::Func<T, Element> elementSelector)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Key | O tipo da chave retornada por keyPredicate |
| Element | O tipo do elemento retornado por elementSelector |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | Uma função para extrair a chave de cada elemento. |
| elementSelector | [System::Func](../../../system/func/)\<T, Element\> | Uma função para extrair o valor da chave de cada elemento. |

### Valor de retorno

Um [IEnumerable](../) que contém uma sequência de objetos e uma chave

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) método




```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>, System::Func\<Source, Element\>) método




```cpp
template<typename Key,typename Element> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate, System::Func<Source, Element> elementSelector)
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IEnumerable](../)
* Classe [IGrouping](../../../system.linq/igrouping/)
* Classe [Func](../../../system/func/)
* Namespace [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)