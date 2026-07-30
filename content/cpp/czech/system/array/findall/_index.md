---
title: FindAll()
second_title: Aspose.Slides pro C++ API referenci
description: Vrací všechny prvky, které splňují podmínky definované zadaným predikátem.
type: docs
weight: 664
url: /cs/system/array/findall/
---
## Array::FindAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) metoda

Vrátí všechny prvky, které odpovídají podmínkám definovaným zadaným predikátem.

```cpp
static System::ArrayPtr<T> System::Array<T>::FindAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) pro vyhledávání prvků v |
| match | [System::Predicate](../../predicate/)\<T\> | Predikát, který určuje podmínky, podle kterých se mají shodovat prvky pole |

### Návratová hodnota

Objekt typu [Array](../) obsahující všechny prvky, které odpovídají podmínkám definovaným zadaným predikátem, pokud jsou nalezeny; jinak prázdný [Array](../).

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Třída [Array](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)