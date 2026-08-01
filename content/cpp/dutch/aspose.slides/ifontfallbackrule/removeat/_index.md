---
title: RemoveAt()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert het FallBack-lettertype op de opgegeven index van de lijst.
type: docs
weight: 92
url: /nl/aspose.slides/ifontfallbackrule/removeat/
---
## IFontFallBackRule::RemoveAt(int32_t) methode


Verwijdert het FallBack-lettertype op de opgegeven index van de lijst.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::RemoveAt(int32_t index)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index van het lettertype dat verwijderd moet worden. |
## Opmerkingen



```cpp
// Maak een regel die een lijst met lettertypen bevat.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Verwijderen van Tahoma uit de lijst
newRule->RemoveAt(2);
```


## Zie ook

* Klasse [IFontFallBackRule](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)