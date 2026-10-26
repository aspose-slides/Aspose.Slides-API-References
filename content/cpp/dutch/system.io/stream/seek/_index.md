---
title: Seek()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de positie van de stream in die wordt gerepresenteerd door het huidige object.
type: docs
weight: 79
url: /nl/system.io/stream/seek/
---
## Stream::Seek(int64_t, SeekOrigin) methode


Stelt de positie van de stream in die wordt gerepresenteerd door het huidige object.

```cpp
virtual int64_t System::IO::Stream::Seek(int64_t offset, SeekOrigin origin)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| offset | **int64_t** | De byte-offset ten opzichte van een positie gespecificeerd door **origin** |
| origin | [SeekOrigin](../../seekorigin/) | Specificeert de positie waarvan en de richting waarnaar de offset wordt berekend |

### Returnwaarde

De nieuwe positie van de stream

## Zie ook

* Enum [SeekOrigin](../../seekorigin/)
* Klasse [Stream](../)
* Naamruimte [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)