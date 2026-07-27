---
title: LINQ_Average()
second_title: Referência da API Aspose.Slides para C++
description: Calcula a média de uma sequência de valores numéricos.
type: docs
weight: 365
url: /pt/system.collections.generic/ienumerable/linq_average/
---
## IEnumerable::LINQ_Average() método

Calcula a média de uma sequência de valores numéricos.

```cpp
Source System::Collections::Generic::IEnumerable<Source>::LINQ_Average()
```

### Valor de Retorno

A média dos valores na sequência.

## IEnumerable::LINQ_Average(const Func\<T, ResultType\>\&) método

Calcula a média de uma sequência de valores que são obtidos ao invocar uma função de transformação em cada elemento da sequência de entrada.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<T, ResultType> &selector)
```

### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| ResultType | O tipo do valor retornado por selector. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Uma função de transformação a ser aplicada a cada elemento. |

### Valor de Retorno

A média dos valores projetados.

## IEnumerable::LINQ_Average(const Func\<Source, ResultType\>\&) método




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<Source, ResultType> &selector)
```

## Veja Também

* Classe [IEnumerable](../)
* Classe [Func](../../../system/func/)
* Espaço de nomes [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)