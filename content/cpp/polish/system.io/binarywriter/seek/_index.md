---
title: Seek()
second_title: Aspose.Slides dla C++ - Referencja API
description: Ustawia pozycję strumienia reprezentowanego przez bieżący obiekt.
type: docs
weight: 79
url: /pl/system.io/binarywriter/seek/
---
## BinaryWriter::Seek(int, System::IO::SeekOrigin) metoda


Ustawia pozycję strumienia reprezentowanego przez bieżący obiekt.

```cpp
int64_t System::IO::BinaryWriter::Seek(int offset, System::IO::SeekOrigin origin=System::IO::SeekOrigin::Begin)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| offset | int | Przesunięcie bajtowe względem pozycji określonej przez **origin** |
| origin | [System::IO::SeekOrigin](../../seekorigin/) | Określa pozycję, od której oraz kierunek, w którym obliczane jest offset |

### Wartość zwracana

Nowa pozycja strumienia

## Zobacz także

* Enum [SeekOrigin](../../seekorigin/)
* Class [BinaryWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)