---
title: TryEnter()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen nesne üzerinde ayrıcalıklı bir kilidi edinmeye çalışır. Uygulanmadı.
type: docs
weight: 27
url: /tr/system.threading/monitor/tryenter/
---
## Monitor::TryEnter(const SharedPtr\<Object\>\&) metod

Belirtilen nesne üzerinde ayrıcalıklı bir kilidi edinmeye çalışır. Uygulanmadı.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj)
```
## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, bool\&) metod

Belirtilen nesne üzerinde ayrıcalıklı bir kilidi edinmeye çalışır ve kilidin alınıp alınmadığını gösteren bir değeri atomik olarak ayarlar.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```
## Monitor::TryEnter(const SharedPtr\<Object\>\&, int32_t) metod

Belirtilen milisaniye sayısı kadar, belirtilen nesne üzerinde ayrıcalıklı bir kilidi edinmeye çalışır. Uygulanmadı.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```
## Monitor::TryEnter(const SharedPtr\<Object\>\&, TimeSpan) metod

Belirtilen süre boyunca, belirtilen nesne üzerinde ayrıcalıklı bir kilidi edinmeye çalışır. Uygulanmadı.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, TimeSpan timeout)
```
## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, int32_t, bool\&) metod

Belirtilen süre boyunca, belirtilen nesne üzerinde ayrıcalıklı bir kilidi edinmeye çalışır ve kilidin alınıp alınmadığını gösteren bir değeri atomik olarak ayarlar.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool &lockTaken)
```
## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) metod

Belirtilen süre boyunca, belirtilen nesne üzerinde ayrıcalıklı bir kilidi edinmeye çalışır ve kilidin alınıp alınmadığını gösteren bir değeri atomik olarak ayarlar.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, TimeSpan timeout, bool &lockTaken)
```
## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Monitor](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)