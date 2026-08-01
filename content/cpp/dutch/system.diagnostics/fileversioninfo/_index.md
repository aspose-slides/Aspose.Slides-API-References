---
title: FileVersionInfo
second_title: Aspose.Slides voor C++ API-referentie
description: "Biedt informatie over de bestandversie. Objecten van deze klasse mogen alleen worden toegewezen met de System::MakeObject()-functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een System::SmartPtr-pointer en gebruik die pointer om deze als argument aan functies door te geven."
type: docs
weight: 1
url: /nl/system.diagnostics/fileversioninfo/
---
## FileVersionInfo klasse

Biedt informatie over de bestandversie. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik die pointer om het als argument aan functies door te geven.

```cpp
class FileVersionInfo
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [String](../../system/string/) [get_ProductVersion](./get_productversion/)() const | Haalt het productversieveld op. |
| static [SharedPtr](../../system/sharedptr/)\<[System::Diagnostics::FileVersionInfo](./)\> [GetVersionInfo](./getversioninfo/)(const [String](../../system/string/)\&) | Haalt bestandsversie-informatie op; niet geïmplementeerd. |
## Zie ook

* Naamruimte [System::Diagnostics](../)
* Bibliotheek [Aspose.Slides](../../)