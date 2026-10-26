---
title: Seek()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt die Position des vom aktuellen Objekt repräsentierten Streams fest.
type: docs
weight: 183
url: /de/system.net.sockets/networkstream/seek/
---
## NetworkStream::Seek(int64_t, IO::SeekOrigin) Methode

Legt die Position des vom aktuellen Objekt repräsentierten Streams fest.

```cpp
int64_t System::Net::Sockets::NetworkStream::Seek(int64_t offset, IO::SeekOrigin origin) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| offset | **int64_t** | Der Byte-Offset relativ zu einer durch **origin** angegebenen Position |
| origin | [IO::SeekOrigin](../../../system.io/seekorigin/) | Gibt die Position an, von der aus und die Richtung, in die der Offset berechnet wird |

### Rückgabewert

Die neue Position des Streams

## Siehe auch

* Enum [SeekOrigin](../../../system.io/seekorigin/)
* Klasse [NetworkStream](../)
* Namensraum [System::Net::Sockets](../../)
* Bibliothek [Aspose.Slides](../../../)