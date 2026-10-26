---
title: Seek()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt die Position des Streams, der durch das aktuelle Objekt repräsentiert wird.
type: docs
weight: 79
url: /de/system.io/stream/seek/
---
## Stream::Seek(int64_t, SeekOrigin) Methode


Setzt die Position des Streams, der durch das aktuelle Objekt repräsentiert wird.

```cpp
virtual int64_t System::IO::Stream::Seek(int64_t offset, SeekOrigin origin)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| offset | **int64_t** | Der Byte-Offset relativ zu einer durch **origin** angegebenen Position |
| origin | [SeekOrigin](../../seekorigin/) | Gibt die Position an, von der aus und die Richtung, zu der der Offset berechnet wird |

### Rückgabewert

Die neue Position des Streams

## Siehe auch

* Enum [SeekOrigin](../../seekorigin/)
* Klasse [Stream](../)
* Namensraum [System::IO](../../)
* Library [Aspose.Slides](../../../)