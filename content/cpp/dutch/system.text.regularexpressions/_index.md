---
title: "System::Text::RegularExpressions"
second_title: Aspose.Slides voor C++ API-referentie
description: 
type: docs
weight: 989
url: /nl/system.text.regularexpressions/
---
## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [Capture](./capture/) | Resultaat van een enkele subexpressie-matching. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik die pointer om deze als argument aan functies door te geven. |
| [CaptureCollection](./capturecollection/) | Lijst van captures uitgevoerd door een enkele capture-groep. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik die pointer om deze als argument aan functies door te geven. |
| [Group](./group/) | Resultaat van een match uitgevoerd door een enkele capture-groep. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik die pointer om deze als argument aan functies door te geven. |
| [GroupCollection](./groupcollection/) | Lijst van capture-groepen in één match. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik die pointer om deze als argument aan functies door te geven. |
| [GroupCollectionPtr](./groupcollectionptr/) | [Group](./group/) collectie-pointer. Dit type is een pointer om de verwijdering van andere objecten te beheren. Het moet op de stack worden toegewezen en aan functies worden doorgegeven, hetzij per waarde, hetzij per const-referentie. |
| [Match](./match/) | [Single](../system/single/) match van regexp over string. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik die pointer om deze als argument aan functies door te geven. |
| [MatchCollection](./matchcollection/) | Collectie van matches uitgevoerd door herhaaldelijk een regexp toe te passen op een string. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik die pointer om deze als argument aan functies door te geven. |
| [Regex](./regex/) | Reguliere expressie die C#-achtige syntaxis volgt. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik die pointer om deze als argument aan functies door te geven. |

## Functies

| Functie | Beschrijving |
| --- | --- |
|  [ASPOSECPP_3RD_PARTY_UNCOPYBALE_TYPE_HOLDER](./asposecpp_3rd_party_uncopybale_type_holder/)(Detail::MatchHolder, MatchHolder, sizeof(Detail::DummyMatchHolder), Detail::DummyMatchHolder, MatchHolderAlias) | Wrapper om de MatchHolder-klasse vast te houden zonder deze op te nemen, evenals PCRE2. |

## Enumeraties

| Enum | Beschrijving |
| --- | --- |
| [RegexOptions](./regexoptions/) | [Regex](./regex/) opties. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [UStringPtr](./ustringptr/) | Gedeelde UnicodeString om kopiëren te voorkomen. |
| [CapturePtr](./captureptr/) | Pointer naar enkel capture-object. |
| [CaptureCollectionPtr](./capturecollectionptr/) | Pointer naar capture-collectie. |
| [GroupPtr](./groupptr/) | Pointer naar groep. |
| [RegexPtr](./regexptr/) | [Regex](./regex/) pointer. |
| [MatchPtr](./matchptr/) | [Match](./match/) pointer. |
| [MatchCollectionPtr](./matchcollectionptr/) | [Match](./match/) collectie-pointer. |
| [MatchEvaluator](./matchevaluator/) | Delegate-type om een match te evalueren. |