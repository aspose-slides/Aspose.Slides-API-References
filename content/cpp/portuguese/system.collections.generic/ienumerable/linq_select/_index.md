---
title: LINQ_Select()
second_title: Referência da API Aspose.Slides para C++
description: Transforma elementos de uma sequência.
type: docs
weight: 248
url: /pt/system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) método

Transforma elementos de uma sequência.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| ResultType | O tipo do valor retornado pelo **selector**. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Uma função de transformação. |

### Valor de retorno

Um [IEnumerable](../) que contém elementos retornados pela função **selector**.

## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) método

Transforma cada elemento de uma sequência em uma nova forma incorporando o índice do elemento.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| ResultType | O tipo do valor retornado pelo **selector**. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, **int32_t**, ResultType\>\& | Uma função de transformação. |

### Valor de retorno

Um [IEnumerable](../) que contém elementos retornados pela função **selector**.

## IEnumerable::LINQ_Select(const Func\<Source, Result\>\&) método




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, Result> &selector)
```

## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) método




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IEnumerable](../)
* Classe [Func](../../../system/func/)
* Espaço de nomes [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)