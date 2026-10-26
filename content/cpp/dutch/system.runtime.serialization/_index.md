---
title: "System::Runtime::Serialization"
second_title: Aspose.Slides voor C++ API-referentie
description: 
type: docs
weight: 794
url: /nl/system.runtime.serialization/
---
## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [Details_SerializationException](./details_serializationexception/) |  |
| [FormatterConverter](./formatterconverter/) | Stelt een basisimplementatie van de [System::Runtime::Serialization::IFormatterConverter](./iformatterconverter/) interface voor. |
| [IFormatterConverter](./iformatterconverter/) | Biedt de verbinding tussen een instantie van [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) en de door de formatter geleverde klasse die het meest geschikt is om de gegevens binnen de [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) te parseren. |
| [ISerializable](./iserializable/) | Interface van een object dat kan worden geserialiseerd. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten zal veroorzaken. Wrap deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik deze pointer om deze aan functies door te geven als argument. |
| [SerializationInfo](./serializationinfo/) | Bevat een verzameling benoemde velden die een geserialiseerd object vertegenwoordigen. Niet geïmplementeerd. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten zal veroorzaken. Wrap deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik deze pointer om deze aan functies door te geven als argument. |
| [StreamingContext](./streamingcontext/) | Dummy-klasse om vertaalde klassen die StreamingContext gebruiken te laten compileren. Beheer geen instanties van deze klasse via [SmartPtr](../system/smartptr/), ze moeten alleen op de stack worden toegewezen. |
## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [SerializationException](./serializationexception/) |  |