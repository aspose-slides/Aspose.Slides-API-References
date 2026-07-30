---
title: Find()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vyhledá první prvek v určeném poli, který splňuje podmínky zadaného predikátu.
type: docs
weight: 651
url: /cs/system/array/find/
---
## Array::Find(System::ArrayPtr\<T\>, System::Predicate\<T\>) metoda

Vyhledá první prvek ve specifikovaném poli, který splňuje podmínky zadaného predikátu.

```cpp
static T System::Array<T>::Find(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) pro hledání prvku v |
| match | [System::Predicate](../../predicate/)\<T\> | Predikát, který definuje podmínky pro porovnání prvků pole |

### Návratová hodnota

Kopie prvního prvku v poli, který splňuje podmínky definované predikátem, jinak výchozí hodnota typu T

## Viz také

* Definice typu [ArrayPtr](../../arrayptr/)
* Definice typu [Predicate](../../predicate/)
* Třída [Array](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)