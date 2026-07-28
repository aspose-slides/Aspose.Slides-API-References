---
title: TryGetFirst()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Próbuje pobrać pierwszy element kolekcji.
type: docs
weight: 248
url: /pl/system.collections.generic.details/trygetfirst/
---
## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, bool\&) funkcja


Próbuje pobrać pierwszy element kolekcji.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, bool &found)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów kolekcji. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | Kolekcja, z której pobierany jest element. |
| found | **bool**\& | Parametr wyjściowy. Zwraca true, gdy kolekcja zawiera jakikolwiek element. W przeciwnym razie zwracane jest false. |

### Wartość zwracana

Zwraca pierwszy element kolekcji. Domyślna wartość typu zostanie zwrócona, gdy kolekcja jest pusta.

## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, const Func\<T, bool\>\&, bool\&) funkcja


Próbuje pobrać pierwszy element kolekcji, który spełnia podany warunek predykatu.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, const Func<T, bool> &predicate, bool &found)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów kolekcji. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | Kolekcja, z której pobierany jest element. |
| predicate | const [Func](../../system/func/)\<T, **bool**\>\& | Funkcja predykatu. |
| found | **bool**\& | Parametr wyjściowy. Zwraca true, gdy kolekcja zawiera jakikolwiek element. W przeciwnym razie zwracane jest false. |

### Wartość zwracana

Zwraca pierwszy element kolekcji. Domyślna wartość typu zostanie zwrócona, gdy nie zostanie znaleziony żaden element spełniający określony warunek funkcji predykatu.

## Zobacz także

* Klasa [IEnumerable](../../system.collections.generic/ienumerable/)
* Klasa [Func](../../system/func/)
* Przestrzeń nazw [System::Collections::Generic::Details](../)
* Biblioteka [Aspose.Slides](../../)