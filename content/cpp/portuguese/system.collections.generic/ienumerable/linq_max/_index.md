---
title: LINQ_Max()
second_title: Referência da API Aspose.Slides for C++
description: Invoca uma função de transformação em cada elemento de uma sequência genérica e retorna o valor máximo resultante.
type: docs
weight: 352
url: /pt/system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) método

Invoca uma função de transformação em cada elemento de uma sequência genérica e retorna o valor máximo resultante.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| ResultType | O tipo do valor retornado pelo seletor. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Uma função de transformação a ser aplicada a cada elemento. |

### Valor de retorno

O valor máximo na sequência.

## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) método

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## Veja também

* Classe [Func](../../../system/func/)
* Classe [IEnumerable](../)
* Espaço de nomes [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)