---
title: TryEnter()
second_title: Справочник API Aspose.Slides для C++
description: Пытается захватить эксклюзивную блокировку указанного объекта. Не реализовано.
type: docs
weight: 27
url: /ru/system.threading/monitor/tryenter/
---
## Monitor::TryEnter(const SharedPtr\<Object\>\&) метод

Пытается захватить эксклюзивную блокировку указанного объекта. Не реализовано.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, bool\&) метод

Пытается захватить эксклюзивную блокировку указанного объекта и атомарно устанавливает значение, указывающее, была ли блокировка получена.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, int32_t) метод

Пытается в течение указанного количества миллисекунд захватить эксклюзивную блокировку указанного объекта. Не реализовано.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, TimeSpan) метод

Пытается в течение указанного периода времени захватить эксклюзивную блокировку указанного объекта. Не реализовано.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, TimeSpan timeout)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, int32_t, bool\&) метод

Пытается в течение указанного периода времени захватить эксклюзивную блокировку указанного объекта и атомарно устанавливает значение, указывающее, была ли блокировка получена.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool &lockTaken)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) метод

Пытается в течение указанного периода времени захватить эксклюзивную блокировку указанного объекта и атомарно устанавливает значение, указывающее, была ли блокировка получена.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, TimeSpan timeout, bool &lockTaken)
```

## См. также

* typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [Monitor](../)
* Класс [TimeSpan](../../../system/timespan/)
* Пространство имен [System::Threading](../../)
* Библиотека [Aspose.Slides](../../../)