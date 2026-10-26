---
title: get_Current()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Pobiera kontekst synchronizacji dla bieżącego wątku.
type: docs
weight: 40
url: /pl/system.threading/synchronizationcontext/get_current/
---
## SynchronizationContext::get_Current() metoda

Pobiera kontekst synchronizacji dla bieżącego wątku.

```cpp
static const SharedPtr<SynchronizationContext> & System::Threading::SynchronizationContext::get_Current()
```

### Wartość zwracana

SharedPtr<SynchronizationContext> Wskaźnik współdzielony do kontekstu synchronizacji bieżącego wątku.

## Uwagi

Zwraca null, jeśli dla bieżącego wątku nie został ustawiony żaden kontekst synchronizacji.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [SynchronizationContext](../)
* Przestrzeń nazw [System::Threading](../../)
* Biblioteka [Aspose.Slides](../../../)