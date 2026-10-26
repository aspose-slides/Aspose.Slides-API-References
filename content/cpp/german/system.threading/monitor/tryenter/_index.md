---
title: TryEnter()
second_title: Aspose.Slides für C++ API-Referenz
description: Versucht, einen exklusiven Lock für das angegebene Objekt zu erwerben. Nicht implementiert.
type: docs
weight: 27
url: /de/system.threading/monitor/tryenter/
---
## Monitor::TryEnter(const SharedPtr\<Object\>\&) Methode

Versucht, einen exklusiven Lock für das angegebene Objekt zu erwerben. Nicht implementiert.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj)
```


## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, bool\&) Methode

Versucht, einen exklusiven Lock für das angegebene Objekt zu erwerben und setzt atomar einen Wert, der angibt, ob der Lock genommen wurde.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, int32_t) Methode

Versucht für die angegebene Anzahl Millisekunden, einen exklusiven Lock für das angegebene Objekt zu erwerben. Nicht implementiert.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```


## Monitor::TryEnter(const SharedPtr\<Object\>\&, TimeSpan) Methode

Versucht für den angegebenen Zeitraum, einen exklusiven Lock für das angegebene Objekt zu erwerben. Nicht implementiert.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, TimeSpan timeout)
```


## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, int32_t, bool\&) Methode

Versucht für den angegebenen Zeitraum, einen exklusiven Lock für das angegebene Objekt zu erwerben und setzt atomar einen Wert, der angibt, ob der Lock genommen wurde.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool &lockTaken)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) Methode

Versucht für den angegebenen Zeitraum, einen exklusiven Lock für das angegebene Objekt zu erwerben und setzt atomar einen Wert, der angibt, ob der Lock genommen wurde.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, TimeSpan timeout, bool &lockTaken)
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [Monitor](../)
* Klasse [TimeSpan](../../../system/timespan/)
* Namensraum [System::Threading](../../)
* Library [Aspose.Slides](../../../)