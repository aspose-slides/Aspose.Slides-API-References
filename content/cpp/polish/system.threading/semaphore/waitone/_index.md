---
title: WaitOne()
second_title: Referencja API Aspose.Slides dla C++
description: Blokuje semafor. Wykonuje nieograniczone oczekiwanie, jeśli to konieczne.
type: docs
weight: 40
url: /pl/system.threading/semaphore/waitone/
---
## Semaphore::WaitOne() metoda

Blokuje semafor. Wykonuje nieograniczone oczekiwanie, jeśli to konieczne.

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```

### Wartość zwracana

Zawsze zwraca true, ponieważ nie zwraca dopóki semafor nie zostanie zablokowany.

## Semaphore::WaitOne(int) metoda

Blokuje semafor. Wykonuje oczekiwanie, jeśli to konieczne.

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| millisecondsTimeout | int | Limit czasu oczekiwania w milisekundach. |

### Wartość zwracana

Zwraca true, jeśli semafor został zablokowany, lub false, jeśli przekroczono limit czasu.

## Zobacz także

* Klasa [Semaphore](../)
* Przestrzeń nazw [System::Threading](../../)
* Biblioteka [Aspose.Slides](../../../)