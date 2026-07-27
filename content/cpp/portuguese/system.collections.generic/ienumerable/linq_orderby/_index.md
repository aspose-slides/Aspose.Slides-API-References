---
title: LINQ_OrderBy()
second_title: Aspose.Slides para C++ Referência da API
description: Classifica os elementos de uma sequência em ordem crescente de acordo com os valores de chave selecionados por keySelector.
type: docs
weight: 209
url: /pt/system.collections.generic/ienumerable/linq_orderby/
---
## IEnumerable::LINQ_OrderBy(const Func\<T, Key\>\&) método

Classifica os elementos de uma sequência em ordem crescente de acordo com os valores de chave selecionados por keySelector.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<T, Key> &keySelector)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| keySelector | Uma função para extrair uma chave de um elemento. |

### Valor de retorno

Um IOrderedEnumerable cujos elementos são ordenados de acordo com uma chave

## IEnumerable::LINQ_OrderBy(const Func\<Source, Key\>\&) método

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<Source, Key> &keySelector)
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)