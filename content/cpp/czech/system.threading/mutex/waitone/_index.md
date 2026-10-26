---
title: WaitOne()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Uzamkne mutex. Provede neomezené čekání, pokud je to nutné.
type: docs
weight: 53
url: /cs/system.threading/mutex/waitone/
---
## Mutex::WaitOne() metoda

Uzamkne mutex. Provede neomezené čekání, pokud je to nutné.

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```

### Návratová hodnota

Vždy vrací true, protože se nevrátí, dokud není mutex uzamčen.

## Mutex::WaitOne(int) metoda

Uzamkne mutex. Provede čekání, pokud je to nutné.

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| millisecondsTimeout | int | Časový limit čekání v milisekundách. |

### Návratová hodnota

Vrací true, pokud byl mutex uzamčen, nebo false, pokud uplynul časový limit.

## Mutex::WaitOne(TimeSpan) metoda

Uzamkne mutex. Provede čekání, pokud je to nutné.

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/) představuje počet milisekund k čekání, nebo [System::TimeSpan](../../../system/timespan/) představuje -1 milisekund pro neomezené čekání. |

### Návratová hodnota

Vrací true, pokud byl mutex uzamčen, nebo false, pokud uplynul časový limit.

## Viz také

* Třída [Mutex](../)
* Třída [TimeSpan](../../../system/timespan/)
* Jmenný prostor [System::Threading](../../)
* Knihovna [Aspose.Slides](../../../)