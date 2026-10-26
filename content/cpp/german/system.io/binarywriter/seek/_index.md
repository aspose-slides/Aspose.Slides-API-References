---
title: Seek()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt die Position des Streams, der vom aktuellen Objekt dargestellt wird.
type: docs
weight: 79
url: /de/system.io/binarywriter/seek/
---
## BinaryWriter::Seek(int, System::IO::SeekOrigin) Methode

Setzt die Position des Streams, der vom aktuellen Objekt dargestellt wird.

```cpp
int64_t System::IO::BinaryWriter::Seek(int offset, System::IO::SeekOrigin origin=System::IO::SeekOrigin::Begin)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| offset | int | Der Byte-Versatz relativ zu einer Position, die durch **origin** angegeben ist |
| origin | [System::IO::SeekOrigin](../../seekorigin/) | Gibt die Position an, von der aus und die Richtung, in die der Versatz berechnet wird |

### Rückgabewert

Die neue Position des Streams

## Siehe auch

* Enum [SeekOrigin](../../seekorigin/)
* Klasse [BinaryWriter](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)