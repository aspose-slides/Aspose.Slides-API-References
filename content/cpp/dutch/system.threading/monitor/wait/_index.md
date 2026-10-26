---
title: Wait()
second_title: Aspose.Slides voor C++ API-referentie
description: Geeft de vergrendeling van een object vrij en blokkeert de huidige thread totdat het de vergrendeling opnieuw verkrijgt. Als het opgegeven time-out interval verloopt, wordt de thread in de ready queue geplaatst. Optioneel verlaat het synchronisatiedomein voor de gesynchroniseerde context vóór het wachten en verkrijgt het domein daarna opnieuw. Niet geïmplementeerd.
type: docs
weight: 53
url: /nl/system.threading/monitor/wait/
---
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t, bool) methode

Geeft het vergrendeling op een object vrij en blokkeert de huidige thread totdat het de vergrendeling opnieuw verkrijgt. Als het opgegeven time-outinterval verstrijkt, wordt de thread in de ready queue geplaatst. Optioneel verlaat het synchronisatiedomein voor de gesynchroniseerde context vóór het wachten en verkrijgt het domein daarna opnieuw. Niet geïmplementeerd.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan, bool) methode

Geeft het vergrendeling op een object vrij en blokkeert de huidige thread totdat het de vergrendeling opnieuw verkrijgt. Als het opgegeven time-outinterval verstrijkt, wordt de thread in de ready queue geplaatst. Optioneel verlaat het synchronisatiedomein voor de gesynchroniseerde context vóór het wachten en verkrijgt het domein daarna opnieuw. Niet geïmplementeerd.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t) methode

Geeft het vergrendeling op een object vrij en blokkeert de huidige thread totdat het de vergrendeling opnieuw verkrijgt. Als het opgegeven time-outinterval verstrijkt, wordt de thread in de ready queue geplaatst. Niet geïmplementeerd.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan) methode

Geeft het vergrendeling op een object vrij en blokkeert de huidige thread totdat het de vergrendeling opnieuw verkrijgt. Als het opgegeven time-outinterval verstrijkt, wordt de thread in de ready queue geplaatst. Niet geïmplementeerd.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&) methode

Geeft het vergrendeling op een object vrij en blokkeert de huidige thread totdat het de vergrendeling opnieuw verkrijgt. Niet geïmplementeerd.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj)
```
## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [Monitor](../)
* Klasse [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)