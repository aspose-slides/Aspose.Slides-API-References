---
title: TryEnter()
second_title: Aspose.Slides C++ API Referenciája
description: Megpróbálja megszerezni egy kizárólagos zárolást a megadott objektumon. Nem implementált.
type: docs
weight: 27
url: /hu/system.threading/monitor/tryenter/
---
## Monitor::TryEnter(const SharedPtr\<Object\>\&) metódus

Megpróbálja megszerezni egy kizárólagos zárolást a megadott objektumon. Nem implementált.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, bool\&) metódus

Megpróbálja megszerezni egy kizárólagos zárolást a megadott objektumon, és atomikusan beállít egy értéket, amely azt jelzi, hogy a zárolás megtörtént.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, int32_t) metódus

Megpróbálja a megadott számú ezredmásodpercig megszerezni egy kizárólagos zárolást a megadott objektumon. Nem implementált.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, TimeSpan) metódus

Megpróbálja a megadott időtartamra megszerezni egy kizárólagos zárolást a megadott objektumon. Nem implementált.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, TimeSpan timeout)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, int32_t, bool\&) metódus

Megpróbálja a megadott időtartamra megszerezni egy kizárólagos zárolást a megadott objektumon, és atomikusan beállít egy értéket, amely azt jelzi, hogy a zárolás megtörtént.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool &lockTaken)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) metódus

Megpróbálja a megadott időtartamra megszerezni egy kizárólagos zárolást a megadott objektumon, és atomikusan beállít egy értéket, amely azt jelzi, hogy a zárolás megtörtént.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, TimeSpan timeout, bool &lockTaken)
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [Monitor](../)
* Osztály [TimeSpan](../../../system/timespan/)
* Névtér [System::Threading](../../)
* Library [Aspose.Slides](../../../)