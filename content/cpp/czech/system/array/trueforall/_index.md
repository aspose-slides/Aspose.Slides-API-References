---
title: TrueForAll()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Určuje, zda všechny prvky v zadaném poli splňují podmínky definované zadaným predikátem.
type: docs
weight: 677
url: /cs/system/array/trueforall/
---
## Array::TrueForAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) metoda

Určuje, zda všechny prvky v zadaném poli splňují podmínky definované zadaným predikátem.

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) prvky, proti nimž se mají porovnávat podmínky |
| match | [System::Predicate](../../predicate/)\<T\> | Predikát, který definuje podmínky, proti nimž se mají porovnávat prvky pole |

### Návratová hodnota

pravda, pokud všechny prvky pole arr splňují podmínky definované predikátem match, jinak nepravda

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)