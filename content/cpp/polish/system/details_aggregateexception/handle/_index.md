---
title: Handle()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Wywołuje funkcję obsługi dla każdego wewnętrznego wyjątku i ponownie rzuca nieobsłużone wyjątki.
type: docs
weight: 66
url: /pl/system/details_aggregateexception/handle/
---
## Szczegóły_AggregateException::Handle(const Func\<Exception, bool\>\&) metoda

Wywołuje funkcję obsługi dla każdego wewnętrznego wyjątku i ponownie rzuca nieobsłużone wyjątki.

```cpp
void System::Details_AggregateException::Handle(const Func<Exception, bool> &predicate)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| predicate | const [Func](../../func/)\<[Exception](../../exception/), **bool**\>\& | Funkcja, która przyjmuje Exception i zwraca true, jeśli zostanie obsłużona. |

## Uwagi

Jeśli wszystkie wyjątki zostaną obsłużone, metoda zwraca się normalnie; w przeciwnym razie zostaje rzucony nowy AggregateException zawierający nieobsłużone wyjątki. 

## Zobacz także

* Definicja typu [Exception](../../exception/)
* Klasa [Func](../../func/)
* Klasa [Details_AggregateException](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)