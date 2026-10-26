---
title: Wait()
second_title: Aspose.Slides для C++ справка API
description: Снимает блокировку с объекта и блокирует текущий поток, пока он снова не получит блокировку. Если указанный интервал ожидания истекает, поток переходит в очередь готовности. При необходимости выходит из области синхронизации для синхронизированного контекста перед ожиданием и повторно входит в область после него. Не реализовано.
type: docs
weight: 53
url: /ru/system.threading/monitor/wait/
---
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t, bool) метод

Снимает блокировку с объекта и блокирует текущий поток, пока не получит блокировку снова. Если указанный интервал ожидания истекает, поток попадает в очередь готовности. При необходимости выходит из области синхронизации для синхронизированного контекста перед ожиданием и снова входит в область после него. Не реализовано.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan, bool) метод

Снимает блокировку с объекта и блокирует текущий поток, пока не получит блокировку снова. Если указанный интервал ожидания истекает, поток попадает в очередь готовности. При необходимости выходит из области синхронизации для синхронизированного контекста перед ожиданием и снова входит в область после него. Не реализовано.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t) метод

Снимает блокировку с объекта и блокирует текущий поток, пока не получит блокировку снова. Если указанный интервал ожидания истекает, поток попадает в очередь готовности. Не реализовано.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan) метод

Снимает блокировку с объекта и блокирует текущий поток, пока не получит блокировку снова. Если указанный интервал ожидания истекает, поток попадает в очередь готовности. Не реализовано.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&) метод

Снимает блокировку с объекта и блокирует текущий поток, пока не получит блокировку снова. Не реализовано.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj)
```
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [Monitor](../)
* Класс [TimeSpan](../../../system/timespan/)
* Пространство имён [System::Threading](../../)
* Библиотека [Aspose.Slides](../../../)