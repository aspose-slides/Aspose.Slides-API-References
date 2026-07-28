---
title: NullableBoolHelper()
second_title: Aspose.Slides dla C++ – referencja API
description: Funkcja pomocnicza sprawdzająca, czy this i other nie są nullem i wywołująca lambdę w takim przypadku. Używana w implementacjach.
type: docs
weight: 105
url: /pl/system/nullable/nullableboolhelper/
---
## Nullable::NullableBoolHelper(const T1\&, const std::function\<bool()>\&, bool) const metoda

Funkcja pomocnicza sprawdzająca, czy this i **other** nie są obu nullem i wywołująca lambdę w takim przypadku. Używana w implementacjach.

```cpp
template<typename T1> bool System::Nullable<T>::NullableBoolHelper(const T1 &other, const std::function<bool()> &f, bool default_if_both_are_null=false) const
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Inny typ nullable. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | const T1\& | Inna wartość nullable do porównania. |
| f | const std::function\<**bool**()>\& | Lambda wywoływana, jeśli zarówno **this**, jak i **other** nie są nullem. |
| default_if_both_are_null | **bool** | Wartość zwracana, jeśli oba wartości są nullem. |

### Wartość zwracana

false jeśli **this** lub **other** jest nullem; **default_if_both_are_null** jeśli oba są nullem; rezultat wywołania **f** jeśli oba nie są nullem.

## Zobacz także

* Klasa [Nullable](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)