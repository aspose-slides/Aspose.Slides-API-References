---
title: LINQ_Min()
second_title: Aspose.Slides para Referência da API C++
description: Invoca uma função de transformação em cada elemento de uma sequência genérica e retorna o valor resultante mínimo.
type: docs
weight: 339
url: /pt/system.collections.generic/ienumerable/linq_min/
---
## IEnumerable::LINQ_Min(const Func\<T, ResultType\>\&) method

Invoca uma função de transformação em cada elemento de uma sequência genérica e retorna o valor resultante mínimo.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<T, ResultType> &selector)
```

### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| ResultType | O tipo do valor retornado pelo seletor. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Uma função de transformação a ser aplicada a cada elemento. |

### Valor de retorno

O valor mínimo na sequência.

## IEnumerable::LINQ_Min(const Func\<Source, ResultType\>\&) method

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<Source, ResultType> &selector)
```

## Veja também

* Classe [Func](../../../system/func/)
* Classe [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)