---
title: DateTime()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy instancję reprezentującą najmniejszą możliwą wartość daty i czasu równą MinValue.
type: docs
weight: 1
url: /pl/system/datetime/datetime/
---
## DateTime::DateTime() konstruktor


Tworzy instancję reprezentującą najmniejszą możliwą wartość daty i czasu równą MinValue.

```cpp
constexpr System::DateTime::DateTime()
```

## DateTime::DateTime(int, int, int) konstruktor


Tworzy instancję reprezentującą wartość daty i czasu określoną jako konkretny rok, miesiąc i dzień.

```cpp
System::DateTime::DateTime(int year, int month, int day)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| year | int | Rok, który ma być reprezentowany przez konstruowaną instancję. |
| month | int | Miesiąc **year**, który ma być reprezentowany przez konstruowaną instancję. |
| day | int | Dzień **month**, który ma być reprezentowany przez konstruowaną instancję. |

## DateTime::DateTime(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) konstruktor


Tworzy instancję reprezentującą wartość daty i czasu określoną jako konkretny rok, miesiąc i dzień w podanym kalendarzu.

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| year | int | Rok, który ma być reprezentowany przez konstruowaną instancję. |
| month | int | Miesiąc **year**, który ma być reprezentowany przez konstruowaną instancję. |
| day | int | Dzień **month**, który ma być reprezentowany przez konstruowaną instancję. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Kalendarz używany do interpretacji określonych **year**, **month** i **day**. |

## DateTime::DateTime(int, int, int, int, int, int) konstruktor


Tworzy instancję reprezentującą wartość daty i czasu określoną jako konkretny rok, miesiąc, dzień, godzinę, minutę i sekundę.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| year | int | Rok, który ma być reprezentowany przez konstruowaną instancję. |
| month | int | Miesiąc **year**, który ma być reprezentowany przez konstruowaną instancję. |
| day | int | Dzień **month**, który ma być reprezentowany przez konstruowaną instancję. |
| hour | int | Godzina **day**, która ma być reprezentowana przez konstruowaną instancję. |
| minute | int | Minuta **hour**, która ma być reprezentowana przez konstruowaną instancję. |
| second | int | Sekunda **minute**, która ma być reprezentowana przez konstruowaną instancję. |

## DateTime::DateTime(int, int, int, int, int, int, DateTimeKind) konstruktor


Tworzy instancję reprezentującą wartość daty i czasu określoną jako konkretny rok, miesiąc, dzień, godzinę, minutę i sekundę.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| year | int | Rok, który ma być reprezentowany przez konstruowaną instancję. |
| month | int | Miesiąc **year**, który ma być reprezentowany przez konstruowaną instancję. |
| day | int | Dzień **month**, który ma być reprezentowany przez konstruowaną instancję. |
| hour | int | Godzina **day**, która ma być reprezentowana przez konstruowaną instancję. |
| minute | int | Minuta **hour**, która ma być reprezentowana przez konstruowaną instancję. |
| second | int | Sekunda **minute**, która ma być reprezentowana przez konstruowaną instancję. |
| kind | [DateTimeKind](../../datetimekind/) | Wartość wskazująca, czy podane parametry daty i czasu określają czas lokalny, UTC lub żaden z nich. |

## DateTime::DateTime(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) konstruktor


Tworzy instancję reprezentującą wartość daty i czasu określoną jako konkretny rok, miesiąc, dzień, godzinę, minutę i sekundę w podanym kalendarzu.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| year | int | Rok, który ma być reprezentowany przez konstruowaną instancję. |
| month | int | Miesiąc **year**, który ma być reprezentowany przez konstruowaną instancję. |
| day | int | Dzień **month**, który ma być reprezentowany przez konstruowaną instancję. |
| hour | int | Godzina **day**, która ma być reprezentowana przez konstruowaną instancję. |
| minute | int | Minuta **hour**, która ma być reprezentowana przez konstruowaną instancję. |
| second | int | Sekunda **minute**, która ma być reprezentowana przez konstruowaną instancję. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Kalendarz używany do interpretacji określonych **year**, **month** i **day**. |

## DateTime::DateTime(int, int, int, int, int, int, int, DateTimeKind) konstruktor


Tworzy instancję reprezentującą wartość daty i czasu określoną jako konkretny rok, miesiąc, dzień, godzinę, minutę, sekundę i milisekundę.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| year | int | Rok, który ma być reprezentowany przez konstruowaną instancję. |
| month | int | Miesiąc **year**, który ma być reprezentowany przez konstruowaną instancję. |
| day | int | Dzień **month**, który ma być reprezentowany przez konstruowaną instancję. |
| hour | int | Godzina **day**, która ma być reprezentowana przez konstruowaną instancję. |
| minute | int | Minuta **hour**, która ma być reprezentowana przez konstruowaną instancję. |
| second | int | Sekunda **minute**, która ma być reprezentowana przez konstruowaną instancję. |
| millisecond | int | Milisekunda **second**, która ma być reprezentowana przez konstruowaną instancję. |
| kind | [DateTimeKind](../../datetimekind/) | Wartość wskazująca, czy podane parametry daty i czasu określają czas lokalny, UTC lub żaden z nich. |

## DateTime::DateTime(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) konstruktor


Tworzy instancję reprezentującą wartość daty i czasu określoną jako konkretny rok, miesiąc, dzień, godzinę, minutę, sekundę i milisekundę w podanym kalendarzu.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| year | int | Rok, który ma być reprezentowany przez konstruowaną instancję. |
| month | int | Miesiąc **year**, który ma być reprezentowany przez konstruowaną instancję. |
| day | int | Dzień **month**, który ma być reprezentowany przez konstruowaną instancję. |
| hour | int | Godzina **day**, która ma być reprezentowana przez konstruowaną instancję. |
| minute | int | Minuta **hour**, która ma być reprezentowana przez konstruowaną instancję. |
| second | int | Sekunda **minute**, która ma być reprezentowana przez konstruowaną instancję. |
| millisecond | int | Milisekunda **second**, która ma być reprezentowana przez konstruowaną instancję. |
| kind | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Wartość wskazująca, czy podane parametry daty i czasu określają czas lokalny, UTC lub żaden z nich. |
| calendar | [DateTimeKind](../../datetimekind/) | Kalendarz używany do interpretacji określonych **year**, **month** i **day**. |

## DateTime::DateTime(int64_t, DateTimeKind) konstruktor


Tworzy instancję reprezentującą wartość daty i czasu określoną jako liczba ticków.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| ticks | **int64_t** | Liczba interwałów 100-ns, które upłynęły od 1 stycznia 0001 00:00:00.000 w kalendarzu gregoriańskim. |
| kind | [DateTimeKind](../../datetimekind/) | Wartość wskazująca, czy parametr **ticks** określa czas lokalny, UTC lub żaden z nich. |

## DateTime::DateTime(int64_t, DateTimeKind, bool) konstruktor


Tworzy instancję reprezentującą wartość daty i czasu określoną jako liczba ticków. DO UŻYTKU WEWNĘTRZNEGO.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| ticks | **int64_t** | Liczba interwałów 100-ns, które upłynęły od 1 stycznia 0001 00:00:00 w kalendarzu gregoriańskim. |
| kind | [DateTimeKind](../../datetimekind/) | Wartość wskazująca, czy parametr **ticks** określa czas lokalny, UTC lub żaden z nich. |
| is_ambiguous_local_dst | **bool** | Prawda, jeśli podana data i czas są niejednoznaczne i mogą być mapowane na wiele czasów UTC. |

## DateTime::DateTime(const DateTime\&) konstruktor


Konstruktor kopiujący instancję.

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| dt | const [DateTime](../)\& | Instancja klasy [DateTime](../), z której kopiowana jest reprezentowana wartość daty i czasu. |

## Zobacz także

* Enum [DateTimeKind](../../datetimekind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../)
* Class [Calendar](../../../system.globalization/calendar/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)