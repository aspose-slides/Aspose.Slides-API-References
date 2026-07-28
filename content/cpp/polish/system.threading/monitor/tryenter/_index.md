---
title: TryEnter()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Próbuje uzyskać wyłączną blokadę na określonym obiekcie. Nie zaimplementowano.
type: docs
weight: 27
url: /pl/system.threading/monitor/tryenter/
---
## Monitor::TryEnter(const SharedPtr\<Object\>\&) metoda

Próbuje uzyskać wyłączną blokadę na określonym obiekcie. Nie zaimplementowano.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj)
```
## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, bool\&) metoda

Próbuje uzyskać wyłączną blokadę na określonym obiekcie i atomowo ustawia wartość wskazującą, czy blokada została przyjęta.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```
## Monitor::TryEnter(const SharedPtr\<Object\>\&, int32_t) metoda

Próbuje, przez określoną liczbę milisekund, uzyskać wyłączną blokadę na określonym obiekcie. Nie zaimplementowano.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```
## Monitor::TryEnter(const SharedPtr\<Object\>\&, TimeSpan) metoda

Próbuje, przez określony czas, uzyskać wyłączną blokadę na określonym obiekcie. Nie zaimplementowano.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, TimeSpan timeout)
```
## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, int32_t, bool\&) metoda

Próbuje, przez określony czas, uzyskać wyłączną blokadę na określonym obiekcie i atomowo ustawia wartość wskazującą, czy blokada została przyjęta.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool &lockTaken)
```
## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) metoda

Próbuje, przez określony czas, uzyskać wyłączną blokadę na określonym obiekcie i atomowo ustawia wartość wskazującą, czy blokada została przyjęta.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, TimeSpan timeout, bool &lockTaken)
```
## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [Monitor](../)
* Klasa [TimeSpan](../../../system/timespan/)
* Przestrzeń nazw [System::Threading](../../)
* Biblioteka [Aspose.Slides](../../../)