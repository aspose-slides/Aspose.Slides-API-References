---
title: WaitAny()
second_title: Aspose.Slides pro C++ – reference API
description: Čeká, dokud některý z handle nevyvolá událost.
type: docs
weight: 14
url: /cs/system.threading/waithandle/waitany/
---
## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) metoda

Čeká na libovolný handle, dokud nevystřelí.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handle, na které se čeká. |
| millisecondsTimeout | int | [Timeout](../../timeout/) k čekání v milisekundách; -1 znamená nekonečné čekání, 0 znamená kontrola a návrat, kladné hodnoty jsou časové limity. |

### Návratová hodnota

True, pokud byl libovolný handle aktivován, false, pokud došlo k překročení časového limitu.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) metoda

Čeká na libovolný handle, dokud nevystřelí.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handle, na které se čeká. |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/), který představuje počet milisekund k čekání, nebo [System::TimeSpan](../../../system/timespan/), který představuje -1 milisekund k neomezenému čekání. |

### Návratová hodnota

True, pokud byl libovolný handle aktivován, false, pokud došlo k překročení časového limitu.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) metoda

Čeká na libovolný handle, dokud nevystřelí.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handle, na které se čeká. |

### Návratová hodnota

True, pokud každý prvek v waitHandles obdržel signál; jinak metoda nikdy nevrátí.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [WaitHandle](../)
* Třída [TimeSpan](../../../system/timespan/)
* Jmenný prostor [System::Threading](../../)
* Library [Aspose.Slides](../../../)