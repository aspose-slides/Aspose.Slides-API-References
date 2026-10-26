---
title: Join()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Připojí řízené vlákno. Vykoná neomezené čekání, pokud je to vyžadováno.
type: docs
weight: 196
url: /cs/system.threading/thread/join/
---
## Thread::Join() metoda


Připojí řízené vlákno. Vykoná neomezené čekání, pokud je to vyžadováno.

```cpp
void System::Threading::Thread::Join()
```

## Thread::Join(int) metoda


Připojí řízené vlákno. Vykoná omezené čekání.

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | Časový limit čekání v milisekundách. |

### Návratová hodnota

True pokud bylo vlákno úspěšně připojeno, false pokud byl překročen časový limit.

## Thread::Join(TimeSpan) metoda


Připojí řízené vlákno. Vykoná omezené čekání.

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | A [TimeSpan](../../../system/timespan/) nastavený na dobu, po kterou se má čekat na ukončení vlákna. |

### Návratová hodnota

True pokud bylo vlákno úspěšně připojeno, false pokud byl překročen časový limit.

## Viz také

* Třída [Thread](../)
* Třída [TimeSpan](../../../system/timespan/)
* Jmenný prostor [System::Threading](../../)
* Knihovna [Aspose.Slides](../../../)