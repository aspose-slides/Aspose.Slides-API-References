---
title: Seek()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Ustawia pozycję strumienia reprezentowanego przez bieżący obiekt.
type: docs
weight: 79
url: /pl/system.io/stream/seek/
---
## Stream::Seek(int64_t, SeekOrigin) metoda

Ustawia pozycję strumienia reprezentowanego przez bieżący obiekt.

```cpp
virtual int64_t System::IO::Stream::Seek(int64_t offset, SeekOrigin origin)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| offset | **int64_t** | Przesunięcie bajtowe względem pozycji określonej przez **origin** |
| origin | [SeekOrigin](../../seekorigin/) | Określa pozycję, od której oraz kierunek, w którym obliczane jest przesunięcie |

### Wartość zwracana

Nowa pozycja strumienia

## Zobacz także

* Enum [SeekOrigin](../../seekorigin/)
* Klasa [Stream](../)
* Przestrzeń nazw [System::IO](../../)
* Library [Aspose.Slides](../../../)