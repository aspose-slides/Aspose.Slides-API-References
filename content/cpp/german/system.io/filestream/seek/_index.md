---
title: Seek()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt die Position des durch das aktuelle Objekt dargestellten Streams fest.
type: docs
weight: 209
url: /de/system.io/filestream/seek/
---
## FileStream::Seek(int64_t, SeekOrigin) Methode

Legt die Position des Streams fest, die durch das aktuelle Objekt repräsentiert wird.

```cpp
int64_t System::IO::FileStream::Seek(int64_t offset, SeekOrigin origin) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| offset | **int64_t** | Der Byte-Offset relativ zu einer Position, die durch **origin** angegeben wird. |
| origin | [SeekOrigin](../../seekorigin/) | Gibt die Position an, von der aus und die Richtung, zu der der Offset berechnet wird. |

### Rückgabewert

Die neue Position des Streams.

## Siehe auch

* Enum [SeekOrigin](../../seekorigin/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)