---
title: Seek()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de positie van de stream in die door het huidige object wordt vertegenwoordigd.
type: docs
weight: 79
url: /nl/system.io/binarywriter/seek/
---
## BinaryWriter::Seek(int, System::IO::SeekOrigin) methode

Stelt de positie van de stream in die door het huidige object wordt vertegenwoordigd.

```cpp
int64_t System::IO::BinaryWriter::Seek(int offset, System::IO::SeekOrigin origin=System::IO::SeekOrigin::Begin)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| offset | int | De byte-offset ten opzichte van een positie gespecificeerd door **origin** |
| origin | [System::IO::SeekOrigin](../../seekorigin/) | Specificeert de positie waarvan en de richting waaraan de offset wordt berekend |

### Retourwaarde

De nieuwe positie van de stream

## Zie ook

* Enum [SeekOrigin](../../seekorigin/)
* Klasse [BinaryWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)