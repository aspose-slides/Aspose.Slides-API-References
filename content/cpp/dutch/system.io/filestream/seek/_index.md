---
title: Seek()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de positie van de stroom in die wordt weergegeven door het huidige object.
type: docs
weight: 209
url: /nl/system.io/filestream/seek/
---
## FileStream::Seek(int64_t, SeekOrigin) methode


Stelt de positie van de stroom in die wordt weergegeven door het huidige object.

```cpp
int64_t System::IO::FileStream::Seek(int64_t offset, SeekOrigin origin) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| offset | **int64_t** | De byte-offset ten opzichte van een positie gespecificeerd door **origin**. |
| origin | [SeekOrigin](../../seekorigin/) | Specificeert de positie vanaf waar en de richting waarin de offset wordt berekend. |

### Retourwaarde

De nieuwe positie van de stroom.

## Zie ook

* Enum [SeekOrigin](../../seekorigin/)
* Klasse [FileStream](../)
* Naamruimte [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)