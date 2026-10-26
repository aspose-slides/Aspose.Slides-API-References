---
title: IndexOf()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een index van de opgegeven regel in de collectie.
type: docs
weight: 118
url: /nl/aspose.slides/ifontfallbackrule/indexof/
---
## IFontFallBackRule::IndexOf(System::String) methode


Retourneert een index van de opgegeven regel in de collectie.

```cpp
virtual int32_t Aspose::Slides::IFontFallBackRule::IndexOf(System::String fontName)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Naam van het te vinden lettertype. |

### Retourwaarde

Index van een lettertype of -1 als het lettertype niet in de lijst wordt gevonden.
## Opmerkingen



```cpp
// Maak een regel die een lijst met lettertypen bevat.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Verkrijg index van Tahoma
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```


## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [IFontFallBackRule](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)