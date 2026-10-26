---
title: TryGetBuffer()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Zwraca tablicę bajtów bez znaku, z której został utworzony ten strumień.
type: docs
weight: 170
url: /pl/system.io/memorystream/trygetbuffer/
---
## MemoryStream::TryGetBuffer(ArraySegment\<uint8_t\>\&) metoda

Zwraca tablicę bajtów bez znaku, z której został utworzony ten strumień.

```cpp
bool System::IO::MemoryStream::TryGetBuffer(ArraySegment<uint8_t> &buffer)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\& | tablica bajtów - parametr wyjściowy. Gdy ta metoda zwraca true, segment tablicy bajtów, z której utworzono ten strumień; gdy ta metoda zwraca false, ten parametr jest ustawiany na domyślną wartość. |

### Wartość zwracana

True, jeśli konwersja się powiodła.

## Zobacz także

* Klasa [ArraySegment](../../../system/arraysegment/)
* Klasa [MemoryStream](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)