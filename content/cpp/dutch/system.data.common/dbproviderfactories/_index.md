---
title: DbProviderFactories
second_title: Aspose.Slides voor C++ API-referentie
description: "API om DB-providerfabrieken te verkrijgen. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de functie System::MakeObject(). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten zal veroorzaken. Wrap deze klasse altijd in een System::SmartPtr-pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 53
url: /nl/system.data.common/dbproviderfactories/
---
## DbProviderFactories klasse

API om DB-providerfabrieken te verkrijgen. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de functie [System::MakeObject()](../../system/makeobject/). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten zal veroorzaken. Wrap deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven.

```cpp
class DbProviderFactories
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[DbProviderFactory](../dbproviderfactory/)\> [GetFactory](./getfactory/)(const [String](../../system/string/)\&) | Haalt de DB provider factory op op basis van de naam. |
## Zie ook

* Naamruimte [System::Data::Common](../)
* Bibliotheek [Aspose.Slides](../../)