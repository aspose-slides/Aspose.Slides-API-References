---
title: FindIndex()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vyhledá první prvek ve specifikovaném poli, který splňuje podmínky zadaného predikátu.
type: docs
weight: 638
url: /cs/system/array/findindex/
---
## Array::FindIndex(System::ArrayPtr\<T\>, System::Predicate\<T\>) metoda


Vyhledá první prvek ve specifikovaném poli, který splňuje podmínky zadaného predikátu.

```cpp
static int System::Array<T>::FindIndex(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) pro vyhledání prvku v |
| match | [System::Predicate](../../predicate/)\<T\> | Predikát, který definuje podmínky pro porovnání prvků pole |

### Návratová hodnota

Index prvního prvku v poli, který splňuje podmínky definované predikátem, jinak -1

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Třída [Array](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)