---
title: ConvertToUtf32()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert het opgegeven UTF-16 surrogatenpaar naar een UTF-32 code-eenheid.
type: docs
weight: 287
url: /nl/system/char/converttoutf32/
---
## Char::ConvertToUtf32(char_t, char_t) methode

Converteert het opgegeven UTF-16 surrogatenpaar naar een UTF-32 code-eenheid.

```cpp
static int System::Char::ConvertToUtf32(char_t highSurrogate, char_t lowSurrogate)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| highSurrogate | char_t | De hoge surrogaat van het UTF-16 surrogatenpaar dat moet worden geconverteerd |
| lowSurrogate | char_t | De lage surrogaat van het UTF-16 surrogatenpaar dat moet worden geconverteerd |

### Retourwaarde

Een UTF-32 code-eenheid die voortvloeit uit de conversie

## Char::ConvertToUtf32(const String\&, int) methode

Converteert de waarde van een UTF-16 gecodeerd teken of surrogatenpaar op een opgegeven positie in een string naar een UTF-32 code-eenheid.

```cpp
static int System::Char::ConvertToUtf32(const String &s, int index)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | const [String](../../string/)\& | Een string die een teken of surrogatenpaar bevat |
| index | int | De indexpositie van het teken of surrogatenpaar in de opgegeven string |

### Retourwaarde

Een UTF-32 code-eenheid die voortvloeit uit de conversie

## Zie ook

* Klasse [Char](../)
* Klasse [String](../../string/)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)