---
title: Seek()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt die Position des vom aktuellen Objekt dargestellten Streams fest.
type: docs
weight: 157
url: /de/system.io/unmanagedmemorystream/seek/
---
## UnmanagedMemoryStream::Seek(int64_t, SeekOrigin) Methode

Legt die Position des vom aktuellen Objekt dargestellten Streams fest.

```cpp
virtual int64_t System::IO::UnmanagedMemoryStream::Seek(int64_t offset, SeekOrigin loc) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| offset | **int64_t** | Der Byte-Offset relativ zu einer durch **origin** angegebenen Position |
| loc | [SeekOrigin](../../seekorigin/) | Gibt die Position an, von der aus und die Richtung, in die der Offset berechnet wird |

### Rückgabewert

Die neue Position des Streams

## Siehe auch

* Enum [SeekOrigin](../../seekorigin/)
* Klasse [UnmanagedMemoryStream](../)
* Namensraum [System::IO](../../)
* Library [Aspose.Slides](../../../)