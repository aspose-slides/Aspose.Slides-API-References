---
title: LINQ_OrderByDescending()
second_title: Referência da API Aspose.Slides para C++
description: Ordena os elementos de uma sequência em ordem descendente de acordo com os valores de chave selecionados por keySelector.
type: docs
weight: 222
url: /pt/system.collections.generic/ienumerable/linq_orderbydescending/
---
## IEnumerable::LINQ_OrderByDescending(const Func\<T, Key\>\&) método


Ordena os elementos de uma sequência em ordem descendente de acordo com os valores de chave selecionados por keySelector.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<T, Key> &keySelector)
```


### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| keySelector | Função para extrair uma chave de um elemento. |

### Valor de retorno

Um IOrderedEnumerable cujos elementos são ordenados em ordem descendente da chave

## IEnumerable::LINQ_OrderByDescending(const Func\<Source, Key\>\&) método




```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<Source, Key> &keySelector)
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)