---
title: Seek()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt die Position des vom aktuellen Objekt dargestellten Streams fest.
type: docs
weight: 105
url: /de/system.io/memorystream/seek/
---
## MemoryStream::Seek(int64_t, SeekOrigin) method


Legt die Position des vom aktuellen Objekt dargestellten Streams fest.

```cpp
int64_t System::IO::MemoryStream::Seek(int64_t offset, SeekOrigin origin) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| offset | **int64_t** | Der Byte-Offset relativ zu einer durch **origin** angegebenen Position |
| origin | [SeekOrigin](../../seekorigin/) | Gibt die Position an, von der aus und in welche Richtung der Offset berechnet wird |

### Rückgabewert

Die neue Position des Streams

## Siehe auch

* Enum [SeekOrigin](../../seekorigin/)
* Klasse [MemoryStream](../)
* Namensraum [System::IO](../../)
* Library [Aspose.Slides](../../../)