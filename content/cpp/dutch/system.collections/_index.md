---
title: "System::Collections"
second_title: Aspose.Slides voor C++ API-referentie
description: 
type: docs
weight: 300
url: /nl/system.collections/
---
## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [BitArray](./bitarray/) | [Array](../system/array/) van bits die via index benaderd kunnen worden. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de functie [System::MakeObject()](../system/makeobject/). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik deze pointer om deze door te geven aan functies als argument. |
| [BitArrayPtr](./bitarrayptr/) | Pointer naar [BitArray](./bitarray/). Dit type is een pointer om de verwijdering van andere objecten te beheren. Het moet op de stack worden gealloceerd en aan functies worden doorgegeven, hetzij per waarde, hetzij per const-referentie. |
| [CollectionBase](./collectionbase/) | Biedt een abstracte basisklasse voor een sterk getypeerde collectie. |
| [ICollection](./icollection/) | Definieert een niet-generieke collectie-interface. |
| [IEnumerable](./ienumerable/) | [IEnumerable](./ienumerable/) is de basisinterface voor alle niet-generieke collecties die kunnen worden genummerd. |
| [IEnumerator](./ienumerator/) | Interface van enumerator die kan worden gebruikt om door enkele elementen te itereren. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de functie [System::MakeObject()](../system/makeobject/). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik deze pointer om deze door te geven aan functies als argument. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/) | Wrapper die een niet-generieke [IEnumerator](./ienumerator/) implementatie creëert boven de generieke Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) - wrapper voor de referentietypen. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/) | Wrapper die een niet-generieke [IEnumerator](./ienumerator/) implementatie creëert boven de generieke Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) - wrapper voor de waardetypen. |
| [IEqualityComparer](./iequalitycomparer/) |  |
| [IList](./ilist/) | [IList](./ilist/) Vertegenwoordigt een niet-generieke collectie van objecten die individueel via index benaderd kunnen worden. |
| [IListImplRefType](./ilistimplreftype/) | Stub die de [System::Collections::IList](./ilist/) interface implementeert op een [System::Collections::Generic::List](../system.collections.generic/list/) object Implementatie voor referentietypen. |
| [IListImplValueType](./ilistimplvaluetype/) | Stub die de [System::Collections::IList](./ilist/) interface implementeert op een [System::Collections::Generic::List](../system.collections.generic/list/) object Implementatie voor waardetypen. |
| [IListWrapper](./ilistwrapper/) | Interface om casting van generieke naar niet-generieke collectie te ondersteunen. |
| [Invalidatable](./invalidatable/) | Klasse die het mogelijk maakt de staat van zijn afstammelingen bij te houden via [InvalidatableTracker](./invalidatabletracker/) objecten. |
| [InvalidatableTracker](./invalidatabletracker/) | Klasse die trackers van [Invalidatable](./invalidatable/) objecten implementeert. |