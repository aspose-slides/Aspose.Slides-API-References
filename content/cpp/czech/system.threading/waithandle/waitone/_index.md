---
title: WaitOne()
second_title: Aspose.Slides pro C++ API Reference
description: Čeká, dokud se handle neaktivuje po neomezenou dobu.
type: docs
weight: 27
url: /cs/system.threading/waithandle/waitone/
---
## WaitHandle::WaitOne() metoda

Čeká, dokud se handle neaktivuje po neomezenou dobu.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```

### Návratová hodnota

Vždy vrátí true, protože nedojde k žádnému časovému limitu.

## WaitHandle::WaitOne(int) metoda

Čeká, dokud se handle neaktivuje.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) k čekání v milisekundách; -1 znamená neomezené čekání, 0 znamená kontrola a návrat, kladné hodnoty jsou časové limity. |

### Návratová hodnota

True pokud byl handle aktivován, false pokud byl překročen časový limit.

## WaitHandle::WaitOne(TimeSpan) metoda

Čeká, dokud se handle neaktivuje.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/) představuje počet milisekund k čekání, nebo [System::TimeSpan](../../../system/timespan/) představuje -1 milisekund pro neomezené čekání. |

### Návratová hodnota

True pokud byl handle aktivován, false pokud byl překročen časový limit.

## WaitHandle::WaitOne(int, bool) metoda

Čeká, dokud se handle neaktivuje.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) k čekání v milisekundách; -1 znamená neomezené čekání, 0 znamená kontrola a návrat, kladné hodnoty jsou časové limity. |
| exitContext | **bool** | Pokud je true, čekání by mělo uvolnit zámek na handle před tím, než na něj bude čekáno. |

### Návratová hodnota

True pokud byl handle aktivován, false pokud byl překročen časový limit.

## Viz také

* Třída [WaitHandle](../)
* Třída [TimeSpan](../../../system/timespan/)
* Jmenný prostor [System::Threading](../../)
* Knihovna [Aspose.Slides](../../../)