---
title: ScopeGuard
second_title: Aspose.Slides dla dokumentacji API w C++
description: Klasa serwisowa, która zapewnia usługi uruchamiania określonego obiektu funkcyjnego, gdy instancja klasy wychodzi poza zakres.
type: docs
weight: 1886
url: /pl/system/scopeguard/
---
## ScopeGuard struct


Klasa serwisowa, która zapewnia usługi uruchamiania określonego obiektu funkcyjnego, gdy instancja klasy wychodzi poza zakres.

```cpp
template<typename F>class ScopeGuard
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| F | Typ obiektu funkcyjnego wywoływanego przez instancje klasy ScopedGuard |
## Metody

| Metoda | Opis |
| --- | --- |
| void [Disable](./disable/)() | Wyłącza wywołanie strażnika. |
|  [ScopeGuard](./scopeguard/)(F) | Tworzy instancję, która jest skonfigurowana do wywołania określonego obiektu funkcyjnego. |
|  [~ScopeGuard](./~scopeguard/)() | Wywołuje obiekt funkcyjny przekazany do konstruktora. |

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)