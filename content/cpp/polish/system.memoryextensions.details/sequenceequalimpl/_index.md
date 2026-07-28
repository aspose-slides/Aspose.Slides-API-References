---
title: SequenceEqualImpl()
second_title: Aspose.Slides dla odniesienia API C++
description: Sprawdza, czy dwa odcinki są równe, rozpoczynając od określonych pozycji.
type: docs
weight: 27
url: /pl/system.memoryextensions.details/sequenceequalimpl/
---
## System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan\<T\>\&, const int32_t, int32_t, const ReadOnlySpan\<T\>\&) funkcja


Sprawdza, czy dwa odcinki są równe, zaczynając od określonych pozycji.

```cpp
template<typename T> bool System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan<T> &first, const int32_t start, int32_t length, const ReadOnlySpan<T> &second)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w odcinkach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Pierwszy odcinek |
| start | const **int32_t** | Indeks początkowy w pierwszym odcinku |
| length | **int32_t** | Liczba elementów do porównania |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Drugi odcinek |

### Wartość zwracana

true, jeśli określone zakresy są równe, false w przeciwnym razie

## Zobacz także

* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Przestrzeń nazw [System::MemoryExtensions::Details](../)
* Biblioteka [Aspose.Slides](../../)