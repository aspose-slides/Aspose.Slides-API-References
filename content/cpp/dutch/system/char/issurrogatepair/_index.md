---
title: IsSurrogatePair()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of de twee opgegeven tekens een UTF-16 surrogate-paar vormen.
type: docs
weight: 27
url: /nl/system/char/issurrogatepair/
---
## Char::IsSurrogatePair(char_t, char_t) methode

Bepaalt of de twee opgegeven tekens een UTF-16 surrogate-paar vormen.

```cpp
static bool System::Char::IsSurrogatePair(char_t highSurrogate, char_t lowSurrogate)
```


### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| highSurrogate | char_t | Een teken dat wordt getest of het een high surrogate is |
| lowSurrogate | char_t | Een teken dat wordt getest of het een low surrogate is |

### Retourwaarde

Waar als de opgegeven tekens een surrogate-paar vormen, anders - false

## Char::IsSurrogatePair(const String\&, int) methode

Bepaalt of twee opeenvolgende tekens in de opgegeven tekenbuffer een surrogate-paar vormen.

```cpp
static bool System::Char::IsSurrogatePair(const String &str, int index)
```


### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const [String](../../string/)\& | Een tekenreeks |
| index | int | Een nul-gebaseerde index in de opgegeven buffer waarop de te testen tekenreeks begint |

### Retourwaarde

Waar als de opgegeven tekens een surrogate-paar vormen, anders - false

## Zie ook

* Klasse [Char](../)
* Klasse [String](../../string/)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)