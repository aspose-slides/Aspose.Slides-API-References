---
title: LINQ_ThenBy()
second_title: Referência da API Aspose.Slides para C++
description: Realiza uma ordenação subsequente dos elementos em uma sequência em ordem crescente de acordo com uma chave.
type: docs
weight: 27
url: /pt/system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) método

Realiza uma ordenação subsequente dos elementos em uma sequência em ordem crescente de acordo com uma chave.

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```

### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| Key | The type of the key returned by keySelector. |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| keySelector | const [Func](../../../system/func/)\<T, Key\>\& | A function to extract a key from each element. |

### Valor de retorno

[System::Linq::IOrderedEnumerable](../) whose elements are sorted according to a key.

## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) método

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IOrderedEnumerable](../)
* Classe [Func](../../../system/func/)
* Espaço de nomes [System::Linq](../../)
* Biblioteca [Aspose.Slides](../../../)