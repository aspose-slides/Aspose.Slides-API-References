---
title: LINQ_FirstOrDefault()
second_title: Aspose.Slides pro C++ - Referenční příručka API
description: Vrací první prvek posloupnosti nebo výchozí hodnotu, pokud je posloupnost prázdná.
type: docs
weight: 66
url: /cs/system.collections.generic/ienumerable/linq_firstordefault/
---
## IEnumerable::LINQ_FirstOrDefault() metoda

Vrací první prvek posloupnosti nebo výchozí hodnotu, pokud je posloupnost prázdná.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault()
```

### Návratová hodnota

První prvek v posloupnosti nebo výchozí konstruovaná hodnota, pokud je posloupnost prázdná.

## IEnumerable::LINQ_FirstOrDefault(std::function\<bool(T)>) metoda

Vrací první prvek posloupnosti, který splňuje podmínku, nebo výchozí hodnotu, pokud takový prvek není nalezen.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault(std::function<bool(T)> predicate)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | Funkce pro testování každého prvku vůči podmínce. |

### Návratová hodnota

default(T) pokud je zdroj prázdný nebo pokud žádný prvek neprojde testem určeným predikátem; jinak první prvek ve zdroji, který prochází testem určeným predikátem.

## Viz také

* Třída [IEnumerable](../)
* Jmenný prostor [System::Collections::Generic](../../)
* Knihovna [Aspose.Slides](../../../)