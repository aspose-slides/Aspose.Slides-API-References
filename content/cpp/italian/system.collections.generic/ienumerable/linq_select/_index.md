---
title: LINQ_Select()
second_title: Riferimento API di Aspose.Slides per C++
description: Trasforma gli elementi di una sequenza.
type: docs
weight: 248
url: /it/system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) method

Trasforma gli elementi di una sequenza.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```

### Template parameters

| Parametro | Descrizione |
| --- | --- |
| ResultType | Il tipo del valore restituito dal **selector**. |

### Arguments

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Una funzione di trasformazione. |

### Return Value

Un [IEnumerable](../) che contiene gli elementi restituiti dalla funzione **selector**.

## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) method

Trasforma ogni elemento di una sequenza in una nuova forma incorporando l'indice dell'elemento.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```

### Template parameters

| Parametro | Descrizione |
| --- | --- |
| ResultType | Il tipo del valore restituito dal **selector**. |

### Arguments

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, **int32_t**, ResultType\>\& | Una funzione di trasformazione. |

### Return Value

Un [IEnumerable](../) che contiene gli elementi restituiti dalla funzione **selector**.

## IEnumerable::LINQ_Select(const Func\<Source, Result\>\&) method




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, Result> &selector)
```

## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) method




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)