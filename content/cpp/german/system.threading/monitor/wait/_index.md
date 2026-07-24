---
title: Wait()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Sperre für ein Objekt frei und blockiert den aktuellen Thread, bis er die Sperre erneut erlangt. Wenn das angegebene Zeitintervall abläuft, wird der Thread in die Ready-Queue eingereiht. Optional verlässt er den Synchronisationsbereich für den synchronisierten Kontext vor dem Warten und erlangt den Bereich danach wieder. Nicht implementiert.
type: docs
weight: 53
url: /de/system.threading/monitor/wait/
---
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t, bool) Methode

Gibt die Sperre für ein Objekt frei und blockiert den aktuellen Thread, bis er die Sperre erneut erlangt. Wenn das angegebene Zeitintervall abläuft, wird der Thread in die Ready-Queue eingereiht. Optional verlässt er den Synchronisationsbereich für den synchronisierten Kontext vor dem Warten und erlangt den Bereich danach wieder. Nicht implementiert.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan, bool) Methode

Gibt die Sperre für ein Objekt frei und blockiert den aktuellen Thread, bis er die Sperre erneut erlangt. Wenn das angegebene Zeitintervall abläuft, wird der Thread in die Ready-Queue eingereiht. Optional verlässt er den Synchronisationsbereich für den synchronisierten Kontext vor dem Warten und erlangt den Bereich danach wieder. Nicht implementiert.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t) Methode

Gibt die Sperre für ein Objekt frei und blockiert den aktuellen Thread, bis er die Sperre erneut erlangt. Wenn das angegebene Zeitintervall abläuft, wird der Thread in die Ready-Queue eingereiht. Nicht implementiert.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan) Methode

Gibt die Sperre für ein Objekt frei und blockiert den aktuellen Thread, bis er die Sperre erneut erlangt. Wenn das angegebene Zeitintervall abläuft, wird der Thread in die Ready-Queue eingereiht. Nicht implementiert.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&) Methode

Gibt die Sperre für ein Objekt frei und blockiert den aktuellen Thread, bis er die Sperre erneut erlangt. Nicht implementiert.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj)
```
## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [Monitor](../)
* Klasse [TimeSpan](../../../system/timespan/)
* Namensraum [System::Threading](../../)
* Library [Aspose.Slides](../../../)