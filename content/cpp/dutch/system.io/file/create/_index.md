---
title: Create()
second_title: Aspose.Slides voor C++ API-referentie
description: Creëert een nieuw bestand (of overschrijft een bestaand) en opent het voor lees- en schrijftoegang met de opgegeven buffersize en opties.
type: docs
weight: 53
url: /nl/system.io/file/create/
---
## File::Create(const String\&, int32_t, FileOptions) method


Creëert een nieuw bestand (of overschrijft een bestaand bestand) en opent het voor lees- en schrijftoegang met de opgegeven buffersize en opties.

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Het pad van het bestand dat moet worden aangemaakt of overschreven |
| bufferSize | **int32_t** | Het aantal bytes dat wordt gebufferd bij het lezen van en schrijven naar het bestand |
| options | [FileOptions](../../fileoptions/) | Specificeert hoe het bestand moet worden aangemaakt of overschreven |

### Retourwaarde

Een gedeelde pointer naar het [FileStream](../../filestream/)-object dat aan het opgegeven bestand is gekoppeld

## Zie ook

* Enum [FileOptions](../../fileoptions/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Klasse [String](../../../system/string/)
* Klasse [File](../)
* Naamruimte [System::IO](../../)
* Library [Aspose.Slides](../../../)