---
title: RemoveAt()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert het FallBack-lettertype op de opgegeven index in de lijst.
type: docs
weight: 131
url: /nl/aspose.slides/fontfallbackrule/removeat/
---
## FontFallBackRule::RemoveAt(int32_t) methode


Verwijdert het FallBack-lettertype op de opgegeven index in de lijst.

```cpp
void Aspose::Slides::FontFallBackRule::RemoveAt(int32_t index) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index van het lettertype dat verwijderd moet worden. |
## Opmerkingen



```cpp
// Maak een regel die een lijst met lettertypen bevat.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Verwijdert Tahoma uit de lijst.
newRule->RemoveAt(2);
```


## Zie ook

* Klasse [FontFallBackRule](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)