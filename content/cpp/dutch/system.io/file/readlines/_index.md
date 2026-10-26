---
title: ReadLines()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest de inhoud van het opgegeven tekstbestand regel voor regel met behulp van de opgegeven tekencodering en retourneert een enumerabele collectie van strings, waarbij elke string een enkele regel van de bestandsinhoud vertegenwoordigt.
type: docs
weight: 326
url: /nl/system.io/file/readlines/
---
## File::ReadLines(const String\&, const EncodingPtr\&) methode

Leest de inhoud van het opgegeven tekstbestand regel voor regel met behulp van de opgegeven tekencodering en retourneert een enumerable collectie van strings, elk zijnde een afzonderlijke regel van de bestandsinhoud.

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Het pad van het te lezen bestand |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | De te gebruiken tekencodering |

### Retourwaarde

Een enumerable collectie van strings die de inhoud van het opgegeven bestand vertegenwoordigt

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)