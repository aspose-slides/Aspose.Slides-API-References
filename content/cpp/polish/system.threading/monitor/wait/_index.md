---
title: Wait()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Zwalnia blokadę na obiekcie i blokuje bieżący wątek, aż ponownie zdobędzie blokadę. Jeśli upłynie określony interwał czasu oczekiwania, wątek przechodzi do kolejki gotowości. Opcjonalnie przed oczekiwaniem opuszcza domenę synchronizacji dla zsynchronizowanego kontekstu i po zakończeniu ponownie przejmuje tę domenę. Niezaimplementowano.
type: docs
weight: 53
url: /pl/system.threading/monitor/wait/
---
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t, bool) method

Zwalnia blokadę na obiekcie i blokuje bieżący wątek, aż ponownie zdobędzie blokadę. Jeśli upłynie określony interwał czasu oczekiwania, wątek przechodzi do kolejki gotowości. Opcjonalnie przed oczekiwaniem opuszcza domenę synchronizacji dla zsynchronizowanego kontekstu i po zakończeniu ponownie przejmuje tę domenę. Niezaimplementowano.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan, bool) method

Zwalnia blokadę na obiekcie i blokuje bieżący wątek, aż ponownie zdobędzie blokadę. Jeśli upłynie określony interwał czasu oczekiwania, wątek przechodzi do kolejki gotowości. Opcjonalnie przed oczekiwaniem opuszcza domenę synchronizacji dla zsynchronizowanego kontekstu i po zakończeniu ponownie przejmuje tę domenę. Niezaimplementowano.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t) method

Zwalnia blokadę na obiekcie i blokuje bieżący wątek, aż ponownie zdobędzie blokadę. Jeśli upłynie określony interwał czasu oczekiwania, wątek przechodzi do kolejki gotowości. Niezaimplementowano.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan) method

Zwalnia blokadę na obiekcie i blokuje bieżący wątek, aż ponownie zdobędzie blokadę. Jeśli upłynie określony interwał czasu oczekiwania, wątek przechodzi do kolejki gotowości. Niezaimplementowano.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&) method

Zwalnia blokadę na obiekcie i blokuje bieżący wątek, aż ponownie zdobędzie blokadę Niezaimplementowano.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj)
```
## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [Monitor](../)
* Klasa [TimeSpan](../../../system/timespan/)
* Przestrzeń nazw [System::Threading](../../)
* Biblioteka [Aspose.Slides](../../../)