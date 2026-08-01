---
title: TryEnter()
second_title: Aspose.Slides voor C++ API-referentie
description: Probeert een exclusieve lock op het opgegeven object te verkrijgen Niet geïmplementeerd.
type: docs
weight: 27
url: /nl/system.threading/monitor/tryenter/
---
## Monitor::TryEnter(const SharedPtr\<Object\>\&) methode


Probeert een exclusieve lock op het opgegeven object te verkrijgen Niet geïmplementeerd.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj)
```


## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, bool\&) methode


Probeert een exclusieve lock op het opgegeven object te verkrijgen, en stelt atomisch een waarde in die aangeeft of de lock is genomen.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, int32_t) methode


Probeert, voor het opgegeven aantal milliseconden, een exclusieve lock op het opgegeven object te verkrijgen Niet geïmplementeerd.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```


## Monitor::TryEnter(const SharedPtr\<Object\>\&, TimeSpan) methode


Probeert, voor de opgegeven tijdsduur, een exclusieve lock op het opgegeven object te verkrijgen Niet geïmplementeerd.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, TimeSpan timeout)
```


## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, int32_t, bool\&) methode


Probeert, voor de opgegeven tijdsduur, een exclusieve lock op het opgegeven object te verkrijgen, en stelt atomisch een waarde in die aangeeft of de lock is genomen.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool &lockTaken)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) methode


Probeert, voor de opgegeven tijdsduur, een exclusieve lock op het opgegeven object te verkrijgen, en stelt atomisch een waarde in die aangeeft of de lock is genomen.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, TimeSpan timeout, bool &lockTaken)
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [Monitor](../)
* Klasse [TimeSpan](../../../system/timespan/)
* Naamruimte [System::Threading](../../)
* Bibliotheek [Aspose.Slides](../../../)