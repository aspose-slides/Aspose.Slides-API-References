---
title: Remove()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert het eerste voorkomen van een specifiek FallBack-lettertype uit de lijst.
type: docs
weight: 118
url: /nl/aspose.slides/fontfallbackrule/remove/
---
## FontFallBackRule::Remove(System::String) methode

Verwijdert het eerste voorkomen van een specifiek FallBack-lettertype uit de lijst.

```cpp
void Aspose::Slides::FontFallBackRule::Remove(System::String fontName) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | De naam van het lettertype om uit de lijst te verwijderen. |

## Opmerkingen

```cpp
// Maak een regel aan die een lijst met lettertypen bevat.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Verwijder Tahoma uit de lijst.
newRule->Remove(u"Tahoma");
```

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [FontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)