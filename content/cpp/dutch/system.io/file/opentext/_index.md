---
title: OpenText()
second_title: Aspose.Slides voor C++ API-referentie
description: Opent het opgegeven bestaande bestand voor het lezen van tekst met UTF-8-codering zonder delen.
type: docs
weight: 261
url: /nl/system.io/file/opentext/
---
## File::OpenText(const String\&, const EncodingPtr\&) methode

Opent het opgegeven bestaande bestand voor het lezen van tekst met UTF-8-codering zonder delen.

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Het pad van het bestand om te openen |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | De tekenencodering die gebruikt moet worden |

### Retourwaarde

Een gedeelde pointer naar een [StreamWriter](../../streamwriter/) object geassocieerd met het geopende bestand

## Zie ook

* Typedef [StreamReaderPtr](../../../system/streamreaderptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Klasse [String](../../../system/string/)
* Klasse [File](../)
* Naamruimte [System::IO](../../)
* Library [Aspose.Slides](../../../)