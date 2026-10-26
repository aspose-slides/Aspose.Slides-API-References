---
title: Wait()
second_title: Aspose.Slides for C++ API referencia
description: Felszabadítja a zárolást egy objektumon, és blokkolja az aktuális szálat, amíg újra meg nem szerzi a zárolást. Ha a megadott időkorlát lejár, a szál a készenléti sorba kerül. Opcionálisan kilép a szinkronizációs doménből a szinkronizált kontextusban a várakozás előtt, és a várakozás után újra megszerezheti a domént. Nincs megvalósítva.
type: docs
weight: 53
url: /hu/system.threading/monitor/wait/
---
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t, bool) metódus


Felszabadítja a zárolást egy objektumon, és blokkolja az aktuális szálat, amíg újra nem szerzi meg a zárolást. Ha a megadott időkorlát lejár, a szál a készenléti sorba kerül. Opcionálisan kilép a szinkronizációs doménből a szinkronizált kontextusban a várakozás előtt, és a várakozás után újra megszerezheti a domént. Nincs megvalósítva.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool exitContext)
```


## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan, bool) metódus


Felszabadítja a zárolást egy objektumon, és blokkolja az aktuális szálat, amíg újra nem szerzi meg a zárolást. Ha a megadott időkorlát lejár, a szál a készenléti sorba kerül. Opcionálisan kilép a szinkronizációs doménből a szinkronizált kontextusban a várakozás előtt, és a várakozás után újra megszerezheti a domént. Nincs megvalósítva.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout, bool exitContext)
```


## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t) metódus


Felszabadítja a zárolást egy objektumon, és blokkolja az aktuális szálat, amíg újra nem szerzi meg a zárolást. Ha a megadott időkorlát lejár, a szál a készenléti sorba kerül. Nincs megvalósítva.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```


## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan) metódus


Felszabadítja a zárolást egy objektumon, és blokkolja az aktuális szálat, amíg újra nem szerzi meg a zárolást. Ha a megadott időkorlát lejár, a szál a készenléti sorba kerül. Nincs megvalósítva.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout)
```


## Monitor::Wait(const SharedPtr\<Object\>\&) metódus


Felszabadítja a zárolást egy objektumon, és blokkolja az aktuális szálat, amíg újra nem szerzi meg a zárolást. Nincs megvalósítva.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj)
```


## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [Monitor](../)
* Osztály [TimeSpan](../../../system/timespan/)
* Névtere [System::Threading](../../)
* Könyvtár [Aspose.Slides](../../../)