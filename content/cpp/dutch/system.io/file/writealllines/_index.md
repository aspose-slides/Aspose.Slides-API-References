---
title: WriteAllLines()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw tekstbestand aan of overschrijft het bestaande en schrijft alle strings uit de opgegeven enumerable collectie van strings naar het bestand, elke string op een nieuwe regel, met de opgegeven codering.
type: docs
weight: 456
url: /nl/system.io/file/writealllines/
---
## File::WriteAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) methode

Maakt een nieuw tekstbestand aan of overschrijft het bestaande en schrijft alle strings uit de opgegeven enumerable collectie van strings naar het bestand, elke string op een nieuwe regel, met de opgegeven codering.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Het bestand om te maken of te overschrijven |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | Een enumerable collectie van strings |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | De karaktercodering die gebruikt moet worden |

## File::WriteAllLines(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) methode

Maakt een nieuw tekstbestand aan of overschrijft het bestaande en schrijft alle strings uit de opgegeven array van strings naar het bestand, elke string op een nieuwe regel, met de opgegeven codering.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Het bestand om te maken of te overschrijven |
| contents | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Een stringarray |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | De karaktercodering die gebruikt moet worden |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klasse [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)