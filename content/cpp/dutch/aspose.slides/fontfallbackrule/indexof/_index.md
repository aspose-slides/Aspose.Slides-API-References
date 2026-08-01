---
title: IndexOf()
second_title: Aspose.Slides voor C++ API Referentie
description: Retourneert een index van de opgegeven regel in de collectie.
type: docs
weight: 157
url: /nl/aspose.slides/fontfallbackrule/indexof/
---
## FontFallBackRule::IndexOf(System::String) methode


Retourneert een index van de opgegeven regel in de collectie.

```cpp
int32_t Aspose::Slides::FontFallBackRule::IndexOf(System::String fontName) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Naam van het lettertype om te zoeken. |

### Returnwaarde

Index van een lettertype of -1 als het lettertype niet in de lijst wordt gevonden.
## Opmerkingen



```cpp
// Maak een regel die een lijst met lettertypen bevat.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Haal de index van Tahoma op.
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```


## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [FontFallBackRule](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)