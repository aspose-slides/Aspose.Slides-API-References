---
title: TimeSpan()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett TimeSpan-objekt som representerar ett noll tidsintervall.
type: docs
weight: 1
url: /sv/system/timespan/timespan/
---
## TimeSpan::TimeSpan() konstruktor


Skapar ett [TimeSpan](../)-objekt som representerar ett noll tidsintervall.

```cpp
constexpr System::TimeSpan::TimeSpan()
```

## TimeSpan::TimeSpan(int64_t) konstruktor


Skapar en instans av klassen [TimeSpan](../) som representerar det angivna tidsintervallet.

```cpp
constexpr System::TimeSpan::TimeSpan(int64_t ticks)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ticks | **int64_t** | Tidsintervallet som ska representeras av den konstruerade instansen, uttryckt som antalet 100-nanosekundintervaller. |

## TimeSpan::TimeSpan(int, int, int) konstruktor


Skapar en instans av klassen [TimeSpan](../) som representerar tidsintervallet som är lika med summan av det angivna antalet timmar, minuter och sekunder.

```cpp
System::TimeSpan::TimeSpan(int hours, int minutes, int seconds)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hours | int | Antalet timmar i timmedelen av tidsintervallet som ska representeras av den konstruerade instansen |
| minutes | int | Antalet minuter i minutedelen av tidsintervallet som ska representeras av den konstruerade instansen |
| seconds | int | Antalet sekunder i sekunddelen av tidsintervallet som ska representeras av den konstruerade instansen |

## TimeSpan::TimeSpan(int, int, int, int, int) konstruktor


Skapar en instans av klassen [TimeSpan](../) som representerar tidsintervallet som är lika med summan av det angivna antalet timmar, minuter, sekunder och millisekunder.

```cpp
System::TimeSpan::TimeSpan(int days, int hours, int minutes, int seconds, int milliseconds=0)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| days | int | Antalet dagar i dagdelen av tidsintervallet som ska representeras av den konstruerade instansen |
| hours | int | Antalet timmar i timmedelen av tidsintervallet som ska representeras av den konstruerade instansen |
| minutes | int | Antalet minuter i minutedelen av tidsintervallet som ska representeras av den konstruerade instansen |
| seconds | int | Antalet sekunder i sekunddelen av tidsintervallet som ska representeras av den konstruerade instansen |
| milliseconds | int | Antalet millisekunder i millisekunddelen av tidsintervallet som ska representeras av den konstruerade instansen |

## TimeSpan::TimeSpan(const TimeSpan\&) konstruktor


Skapar ett [TimeSpan](../)-objekt som representerar tidsintervallet som är lika med tidsintervallet som representeras av det angivna [TimeSpan](../)-objektet.

```cpp
constexpr System::TimeSpan::TimeSpan(const TimeSpan &)=default
```

## Se även

* Klass [TimeSpan](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)