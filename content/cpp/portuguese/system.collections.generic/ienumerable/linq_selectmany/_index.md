---
title: LINQ_SelectMany()
second_title: Referência da API Aspose.Slides para C++
description: Projeta cada elemento de uma sequência e combina as sequências resultantes em uma única sequência.
type: docs
weight: 300
url: /pt/system.collections.generic/ienumerable/linq_selectmany/
---
## IEnumerable::LINQ_SelectMany(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) method


Projeta cada elemento de uma sequência e combina as sequências resultantes em uma única sequência.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<T, SharedPtr<IEnumerable<ResultType>>> &selector)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| ResultType | O tipo do valor retornado pelo **selector**. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, [SharedPtr](../../../system/sharedptr/)\<[IEnumerable](../)\<ResultType\>\>\>\& | Uma função de transformação. |

### Valor de retorno

Um [IEnumerable](../) que contém o resultado da invocação de uma função de projeção um-para-muitos em cada elemento da sequência de entrada.

## IEnumerable::LINQ_SelectMany(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) method




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<Source, SharedPtr<IEnumerable<Result>>> &selector)
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IEnumerable](../)
* Classe [Func](../../../system/func/)
* Espaço de nomes [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)