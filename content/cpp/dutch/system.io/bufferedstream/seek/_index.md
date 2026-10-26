---
title: Seek()
second_title: Aspose.Slides voor C++ API Referentie
description: Stelt de positie van de stroom in die wordt gerepresenteerd door het huidige object.
type: docs
weight: 79
url: /nl/system.io/bufferedstream/seek/
---
## BufferedStream::Seek(int64_t, SeekOrigin) methode


Stelt de positie van de stroom in die wordt vertegenwoordigd door het huidige object.

```cpp
virtual int64_t System::IO::BufferedStream::Seek(int64_t offset, SeekOrigin origin) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| offset | **int64_t** | De byte-offset ten opzichte van een positie gespecificeerd door **origin** |
| origin | [SeekOrigin](../../seekorigin/) | Specificeert de positie van waaruit en de richting waarnaar de offset wordt berekend |

### Retourwaarde

De nieuwe positie van de stroom

## Zie ook

* Enum [SeekOrigin](../../seekorigin/)
* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)