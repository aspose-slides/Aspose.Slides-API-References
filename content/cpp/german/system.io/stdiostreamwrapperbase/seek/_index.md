---
title: Seek()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt die Position des Streams, der durch das aktuelle Objekt repräsentiert wird.
type: docs
weight: 40
url: /de/system.io/stdiostreamwrapperbase/seek/
---
## STDIOStreamWrapperBase::Seek(int64_t, SeekOrigin) Methode


Setzt die Position des von dem aktuellen Objekt repräsentierten Streams.

```cpp
virtual int64_t System::IO::STDIOStreamWrapperBase<T, typename>::Seek(int64_t offset, SeekOrigin origin) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| offset | **int64_t** | Der Byte-Offset relativ zu einer durch **origin** angegebenen Position |
| origin | [SeekOrigin](../../seekorigin/) | Gibt die Position an, von der aus und die Richtung, in die der Offset berechnet wird |

### Rückgabewert

Die neue Position des Streams

## Siehe auch

* Aufzählung [SeekOrigin](../../seekorigin/)
* Klasse [STDIOStreamWrapperBase](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)