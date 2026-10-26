---
title: TryGetLast()
second_title: Referencja API Aspose.Slides dla C++
description: Próbuje pobrać ostatni element kolekcji.
type: docs
weight: 261
url: /pl/system.collections.generic.details/trygetlast/
---
## System::Collections::Generic::Details::TryGetLast(IEnumerable\<T\>\&, bool\&) funkcja


Próbuje pobrać ostatni element kolekcji.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetLast(IEnumerable<T> &enumerable, bool &found)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów kolekcji. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | Kolekcja, z której ma zostać pobrany element. |
| found | **bool**\& | Parametr wyjściowy. Zwraca true, gdy kolekcja zawiera jakikolwiek element. W przeciwnym razie zwracane jest false. |

### Wartość zwracana

Zwraca ostatni element kolekcji. Domyślna wartość typu zostanie zwrócona, gdy kolekcja jest pusta.

## Zobacz także

* Klasa [IEnumerable](../../system.collections.generic/ienumerable/)
* Przestrzeń nazw [System::Collections::Generic::Details](../)
* Biblioteka [Aspose.Slides](../../)