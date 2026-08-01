---
title: ColorTranslator
second_title: Aspose.Slides voor C++ API-referentie
description: "Voert kleurvertalingen uit. Objecten van deze klasse mogen alleen worden toegewezen met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtime fouten en/of assertiefouten. Wikkel deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze aan functies als argument door te geven."
type: docs
weight: 66
url: /nl/system.drawing/colortranslator/
---
## ColorTranslator klasse

Voert kleurvertalingen uit. Objecten van deze klasse mogen alleen worden toegewezen met behulp van [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtime fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om deze als argument aan functies door te geven.

```cpp
class ColorTranslator
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static [Color](../color/) [FromHtml](./fromhtml/)(const [System::String](../../system/string/)\&) | Converteert de opgegeven HTML-kleurrepresentatie naar het gelijkwaardige [Color](../color/) object. |
| static [Color](../color/) [FromWin32](./fromwin32/)(int) | Converteert de opgegeven [Windows](../../system.windows/) kleur naar het gelijkwaardige [Color](../color/) object. |
| static [String](../../system/string/) [ToHtml](./tohtml/)(const [Color](../color/)\&) | Converteert het opgegeven [Color](../color/) object naar de tekenreeksrepresentatie van een equivalente HTML-kleur. |

## Zie ook

* Naamruimte [System::Drawing](../)
* Bibliotheek [Aspose.Slides](../../)