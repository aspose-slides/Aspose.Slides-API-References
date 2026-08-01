---
title: GetDigitValue()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de cijferwaarde op van het opgegeven teken.
type: docs
weight: 14
url: /nl/system.globalization/charunicodeinfo/getdigitvalue/
---
## CharUnicodeInfo::GetDigitValue(char16_t) methode


Haalt de numerieke waarde op van het opgegeven teken.

```cpp
static int System::Globalization::CharUnicodeInfo::GetDigitValue(char16_t ch)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ch | char16_t | Unicode-teken. |

### Retourwaarde

De numerieke waarde of -1 als het opgegeven teken geen cijfer is.

## CharUnicodeInfo::GetDigitValue(const String\&, int) methode


Haalt de numerieke waarde op van het teken op de opgegeven index in de string.

```cpp
static int System::Globalization::CharUnicodeInfo::GetDigitValue(const String &str, int index)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | De string die het Unicode-teken bevat. |
| index | int | De index van het Unicode-teken. |

### Retourwaarde

De numerieke waarde of -1 als het opgegeven teken geen cijfer is.

## Zie ook

* Klasse [CharUnicodeInfo](../)
* Klasse [String](../../../system/string/)
* Namespace [System::Globalization](../../)
* Bibliotheek [Aspose.Slides](../../../)