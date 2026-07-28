---
title: Join()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Dołącza do zarządzanego wątku. Wykonuje nieograniczone oczekiwanie, jeśli jest wymagane.
type: docs
weight: 196
url: /pl/system.threading/thread/join/
---
## Thread::Join() metoda

Dołącza do zarządzanego wątku. Wykonuje nieograniczone oczekiwanie, jeśli jest wymagane.

```cpp
void System::Threading::Thread::Join()
```

## Thread::Join(int) metoda

Dołącza do zarządzanego wątku. Wykonuje ograniczone oczekiwanie.

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| millisecondsTimeout | int | Limit czasu oczekiwania w milisekundach. |

### Wartość zwracana

True jeśli wątek został pomyślnie dołączony, false jeśli przekroczono limit czasu.

## Thread::Join(TimeSpan) metoda

Dołącza do zarządzanego wątku. Wykonuje ograniczone oczekiwanie.

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Obiekt [TimeSpan](../../../system/timespan/) określający czas, jaki należy czekać na zakończenie wątku. |

### Wartość zwracana

True jeśli wątek został pomyślnie dołączony, false jeśli przekroczono limit czasu.

## Zobacz także

* Klasa [Thread](../)
* Klasa [TimeSpan](../../../system/timespan/)
* Przestrzeń nazw [System::Threading](../../)
* Biblioteka [Aspose.Slides](../../../)