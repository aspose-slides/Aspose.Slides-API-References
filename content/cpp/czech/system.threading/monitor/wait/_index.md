---
title: Wait()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Uvolní zámek na objektu a blokuje aktuální vlákno, dokud zámek znovu nezíská. Pokud uplyne zadaný časový interval, vlákno vstoupí do fronty připravených. Volitelně opustí synchronizační doménu pro synchronizovaný kontext před čekáním a po čekání doménu znovu získá. Není implementováno.
type: docs
weight: 53
url: /cs/system.threading/monitor/wait/
---
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t, bool) metoda

Uvolní zámek na objektu a blokuje aktuální vlákno, dokud zámek znovu nezíská. Pokud uplyne zadaný časový interval, vlákno vstoupí do fronty připravených. Volitelně opustí synchronizační doménu pro synchronizovaný kontext před čekáním a po čekání doménu znovu získá. Není implementováno.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan, bool) metoda

Uvolní zámek na objektu a blokuje aktuální vlákno, dokud zámek znovu nezíská. Pokud uplyne zadaný časový interval, vlákno vstoupí do fronty připravených. Volitelně opustí synchronizační doménu pro synchronizovaný kontext před čekáním a po čekání doménu znovu získá. Není implementováno.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t) metoda

Uvolní zámek na objektu a blokuje aktuální vlákno, dokud zámek znovu nezíská. Pokud uplyne zadaný časový interval, vlákno vstoupí do fronty připravených. Není implementováno.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan) metoda

Uvolní zámek na objektu a blokuje aktuální vlákno, dokud zámek znovu nezíská. Pokud uplyne zadaný časový interval, vlákno vstoupí do fronty připravených. Není implementováno.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&) metoda

Uvolní zámek na objektu a blokuje aktuální vlákno, dokud zámek znovu nezíská. Není implementováno.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj)
```
## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [Monitor](../)
* Třída [TimeSpan](../../../system/timespan/)
* Jmenný prostor [System::Threading](../../)
* Knihovna [Aspose.Slides](../../../)