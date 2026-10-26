---
title: TryEnter()
second_title: Aspose.Slides pro C++ – reference API
description: Pokouší se získat výlučný zámek na zadaný objekt. Není implementováno.
type: docs
weight: 27
url: /cs/system.threading/monitor/tryenter/
---
## Monitor::TryEnter(const SharedPtr\<Object\>\&) metoda


Pokusí se získat výlučný zámek na zadaný objekt. Není implementováno.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj)
```


## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, bool\&) metoda


Pokusí se získat výlučný zámek na zadaný objekt a atomicky nastaví hodnotu, která udává, zda byl zámek získán.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, int32_t) metoda


Pokusí se po zadaný počet milisekund získat výlučný zámek na zadaný objekt. Není implementováno.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```


## Monitor::TryEnter(const SharedPtr\<Object\>\&, TimeSpan) metoda


Pokusí se po zadanou dobu získat výlučný zámek na zadaný objekt. Není implementováno.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, TimeSpan timeout)
```


## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, int32_t, bool\&) metoda


Pokusí se po zadanou dobu získat výlučný zámek na zadaný objekt a atomicky nastaví hodnotu, která udává, zda byl zámek získán.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool &lockTaken)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) metoda


Pokusí se po zadanou dobu získat výlučný zámek na zadaný objekt a atomicky nastaví hodnotu, která udává, zda byl zámek získán.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, TimeSpan timeout, bool &lockTaken)
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [Monitor](../)
* Třída [TimeSpan](../../../system/timespan/)
* Jmenný prostor [System::Threading](../../)
* Knihovna [Aspose.Slides](../../../)