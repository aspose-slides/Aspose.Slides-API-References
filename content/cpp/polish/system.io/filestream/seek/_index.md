---
title: Seek()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Ustawia pozycję strumienia reprezentowanego przez bieżący obiekt.
type: docs
weight: 209
url: /pl/system.io/filestream/seek/
---
## FileStream::Seek(int64_t, SeekOrigin) metoda

Ustawia pozycję strumienia reprezentowanego przez bieżący obiekt.

```cpp
int64_t System::IO::FileStream::Seek(int64_t offset, SeekOrigin origin) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| offset | **int64_t** | Przesunięcie bajtowe względem pozycji określonej przez **origin**. |
| origin | [SeekOrigin](../../seekorigin/) | Określa pozycję, od której oraz kierunek, w którym obliczane jest przesunięcie. |

### Wartość zwracana

Nowa pozycja strumienia.

## Zobacz także

* Enum [SeekOrigin](../../seekorigin/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)