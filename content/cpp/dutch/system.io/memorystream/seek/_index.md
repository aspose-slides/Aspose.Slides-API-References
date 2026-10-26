---
title: Seek()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de positie van de stream in die wordt weergegeven door het huidige object.
type: docs
weight: 105
url: /nl/system.io/memorystream/seek/
---
## MemoryStream::Seek(int64_t, SeekOrigin) methode

Stelt de positie van de stream in die wordt weergegeven door het huidige object.

```cpp
int64_t System::IO::MemoryStream::Seek(int64_t offset, SeekOrigin origin) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| offset | **int64_t** | De byte-offset ten opzichte van een positie die is gespecificeerd door **origin** |
| origin | [SeekOrigin](../../seekorigin/) | Specificeert de positie vanaf waar en de richting waarnaar de offset wordt berekend |

### Retourwaarde

De nieuwe positie van de stream

## Zie ook

* Enum [SeekOrigin](../../seekorigin/)
* Klasse [MemoryStream](../)
* Naamruimte [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)