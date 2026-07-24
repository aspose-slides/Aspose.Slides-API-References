---
title: Seek()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt die Position des Streams fest, der durch das aktuelle Objekt repräsentiert wird.
type: docs
weight: 79
url: /de/system.io/bufferedstream/seek/
---
## BufferedStream::Seek(int64_t, SeekOrigin) Methode

Legt die Position des Streams fest, der durch das aktuelle Objekt repräsentiert wird.

```cpp
virtual int64_t System::IO::BufferedStream::Seek(int64_t offset, SeekOrigin origin) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| offset | **int64_t** | Der Byte-Offset relativ zu einer Position, die durch **origin** angegeben ist |
| origin | [SeekOrigin](../../seekorigin/) | Gibt die Position an, von der aus und die Richtung, zu der der Offset berechnet wird |

### Rückgabewert

Die neue Position des Streams

## Siehe auch

* Enum [SeekOrigin](../../seekorigin/)
* Klasse [BufferedStream](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)