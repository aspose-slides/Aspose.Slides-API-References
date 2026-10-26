---
title: ReadBlock()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest het opgegeven maximum aantal tekens van de huidige tekstlezer en schrijft de gegevens naar een buffer, beginnend bij de opgegeven index.
type: docs
weight: 53
url: /nl/system.io/textreader/readblock/
---
## TextReader::ReadBlock(ArrayPtr\<char_t\>, int, int) methode


Leest het opgegeven maximum aantal tekens van de huidige tekstlezer en schrijft de gegevens naar een buffer, beginnend bij de opgegeven index.

```cpp
virtual int System::IO::TextReader::ReadBlock(ArrayPtr<char_t> buffer, int index, int count)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Een tekenbuffer om de gelezen gegevens naar te schrijven |
| index | int | Een 0-gebaseerde index in **buffer** om te beginnen met schrijven |
| count | int | Het maximum aantal tekens om te lezen |

### Retourwaarde

Het daadwerkelijke aantal gelezen tekens

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [TextReader](../)
* Namespace [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)