---
title: ReadAllLines()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest de inhoud van het opgegeven tekstbestand regel voor regel in een array van strings met behulp van de opgegeven tekencodering.
type: docs
weight: 300
url: /nl/system.io/file/readalllines/
---
## File::ReadAllLines(const String\&, const EncodingPtr\&) methode


Leest de inhoud van het opgegeven tekstbestand regel voor regel in een array van strings met behulp van de opgegeven tekencodering.

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Het pad van het bestand om te lezen |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | De te gebruiken tekencodering |

### Retourwaarde

Een string-array waarvan elk element een enkele regel van het opgegeven bestand vertegenwoordigt.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Klasse [String](../../../system/string/)
* Klasse [File](../)
* Naamruimte [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)