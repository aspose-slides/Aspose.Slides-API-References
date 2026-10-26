---
title: SetSynchronizationContext()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Ustawia kontekst synchronizacji dla bieżącego wątku.
type: docs
weight: 53
url: /pl/system.threading/synchronizationcontext/setsynchronizationcontext/
---
## SynchronizationContext::SetSynchronizationContext(const SharedPtr\<SynchronizationContext\>\&) method

Ustawia kontekst synchronizacji dla bieżącego wątku.

```cpp
static void System::Threading::SynchronizationContext::SetSynchronizationContext(const SharedPtr<SynchronizationContext> &syncContext)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| syncContext | const [SharedPtr](../../../system/sharedptr/)\<[SynchronizationContext](../)\>\& | Kontekst synchronizacji, który ma zostać ustawiony dla bieżącego wątku. |

## Uwagi

Przekazanie nullptr wyczyści kontekst synchronizacji dla bieżącego wątku.

## Zobacz też

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [SynchronizationContext](../)
* Przestrzeń nazw [System::Threading](../../)
* Biblioteka [Aspose.Slides](../../../)