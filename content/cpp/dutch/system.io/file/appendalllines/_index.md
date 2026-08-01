---
title: AppendAllLines()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt strings uit de opgegeven verzameling strings toe aan het opgegeven bestand met de opgegeven codering door elke string in een nieuwe regel te schrijven. Als het opgegeven bestand niet bestaat, wordt het aangemaakt. Het bestand wordt gesloten nadat alle strings zijn geschreven.
type: docs
weight: 1
url: /nl/system.io/file/appendalllines/
---
## File::AppendAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) methode

Voegt strings uit de opgegeven verzameling strings toe aan het opgegeven bestand met de opgegeven codering door elke string in een nieuwe regel te schrijven. Als het opgegeven bestand niet bestaat, wordt het aangemaakt. Het bestand wordt gesloten nadat alle strings zijn geschreven.

```cpp
static void System::IO::File::AppendAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Het pad van het bestand waaraan de strings moeten worden toegevoegd |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | De strings die naar het bestand moeten worden geschreven |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | De te gebruiken tekencodering |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Klasse [String](../../../system/string/)
* Klasse [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klasse [File](../)
* Naamruimte [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)