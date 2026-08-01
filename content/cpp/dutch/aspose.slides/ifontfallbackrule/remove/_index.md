---
title: Remove()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert de eerste verschijning van een specifiek FallBack-lettertype uit de lijst.
type: docs
weight: 79
url: /nl/aspose.slides/ifontfallbackrule/remove/
---
## IFontFallBackRule::Remove(System::String) method

Verwijdert de eerste verschijning van een specifiek FallBack-lettertype uit de lijst.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::Remove(System::String fontName)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | De naam van het lettertype dat verwijderd moet worden uit de lijst. |
## Opmerkingen

```cpp
// Maak een regel die een lijst met lettertypen bevat.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Verwijderen van Tahoma uit de lijst
newRule->Remove(u"Tahoma");
```

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [IFontFallBackRule](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)