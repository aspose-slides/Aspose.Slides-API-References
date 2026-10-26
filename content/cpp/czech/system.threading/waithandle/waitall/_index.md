---
title: WaitAll()
second_title: Aspose.Slides pro C++ referenci API
description: Čeká, dokud všechny handle nebudou aktivovány.
type: docs
weight: 1
url: /cs/system.threading/waithandle/waitall/
---
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) metoda


Čeká, dokud všechny handle nebudou aktivovány.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handles to wait for. |
| millisecondsTimeout | int | [Timeout](../../timeout/) k čekání, v milisekundách; -1 znamená nekonečné čekání, 0 znamená kontrola a návrat, kladné hodnoty jsou časové limity. |

### Návratová hodnota

True pokud byly všechny handle aktivovány, false pokud byl překročen časový limit.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) metoda


Čeká, dokud všechny handle nebudou aktivovány.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handles to wait for. |
| timeout | [TimeSpan](../../../system/timespan/) | A [System::TimeSpan](../../../system/timespan/) který představuje počet milisekund k čekání, nebo [System::TimeSpan](../../../system/timespan/) který představuje -1 milisekund pro neomezené čekání. |

### Návratová hodnota

True pokud byly všechny handle aktivovány, false pokud byl překročen časový limit.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) metoda


Čeká, dokud všechny handle nebudou aktivovány.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handles to wait for. |

### Návratová hodnota

True když každý prvek v waitHandles obdržel signál; jinak metoda nikdy nevrací.

## See Also

* Definice typu [ArrayPtr](../../../system/arrayptr/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [WaitHandle](../)
* Třída [TimeSpan](../../../system/timespan/)
* Jmenný prostor [System::Threading](../../)
* Knihovna [Aspose.Slides](../../../)