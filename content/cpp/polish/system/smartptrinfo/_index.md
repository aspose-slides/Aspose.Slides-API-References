---
title: SmartPtrInfo
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Klasa serwisowa służąca do testowania i modyfikowania zawartości SmartPtr bez znajomości końcowego typu. Używana do zbierania śmieci i wykrywania pętlowych referencji itp. Traktuj ją jako 'pointer to pointer'. Nie możemy używać bazowego typu SmartPtr, ponieważ go nie posiada; zamiast tego używamy tej klasy 'info'.
type: docs
weight: 1249
url: /pl/system/smartptrinfo/
---
## SmartPtrInfo klasa

Klasa serwisowa służąca do testowania i modyfikowania [SmartPtr](../smartptr/)'s contents without knowing final type. Used for garbage collection and loop references detection, etc. Think of it as of 'pointer to pointer'. We can't use [SmartPtr](../smartptr/)'s basetype as it doesn't have any; instead, we use this 'info' class.

```cpp
class SmartPtrInfo
```

## Metody

| Metoda | Opis |
| --- | --- |
| const void * [getInternalPtr](./getinternalptr/)() const | Zwraca surowy obiekt, na który wskazuje wskaźnik referencyjny. |
| [Object](../object/) * [getObject](./getobject/)() const | Zwraca obiekt, na który wskazuje wskaźnik referencyjny. |
| [Object](../object/) * [getOwned](./getowned/)() const | Zwraca wskaźnik własny obiektu. |
|  [operator bool](./operator_bool/)() const | Sprawdza, czy obiekt info wskazuje na niezerowy wskaźnik. |
| **bool** [operator!](./operator_not/)() const | Sprawdza, czy obiekt info nie wskazuje na niezerowy wskaźnik. |
| [Object](../object/) * [operator->](./operator_minus_greater/)() const | Umożliwia wywoływanie metod [Object](../object/) wskazywanych przez wskaźnik referencyjny. |
| **bool** [operator<](./operator_less/)(const [SmartPtrInfo](./)\&) const | Porównuje mniejsze wartości wskaźników referencjonowanych przez dwa obiekty info. |
|  [SmartPtrInfo](./smartptrinfo/)() | Tworzy pusty [SmartPtrInfo](./) object. |
| explicit  [SmartPtrInfo](./smartptrinfo/)(const [SmartPtr](../smartptr/)\<T\>\&) | Tworzy [SmartPtrInfo](./) object with information on specific smart pointer. |

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)