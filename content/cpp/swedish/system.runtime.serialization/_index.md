---
title: "System::Runtime::Serialization"
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 794
url: /sv/system.runtime.serialization/
---
## Klasser

| Klass | Beskrivning |
| --- | --- |
| [Details_SerializationException](./details_serializationexception/) |  |
| [FormatterConverter](./formatterconverter/) | Representerar en grundläggande implementation av [System::Runtime::Serialization::IFormatterConverter](./iformatterconverter/)-gränssnittet. |
| [IFormatterConverter](./iformatterconverter/) | Tillhandahåller anslutningen mellan en instans av [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) och den formattertillhandahållna klassen som är bäst lämpad att tolka data i [System::Runtime::Serialization::SerializationInfo](./serializationinfo/). |
| [ISerializable](./iserializable/) | Gränssnitt för objekt som kan serialiseras. Objekt av denna klass får endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller assertion-fel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [SerializationInfo](./serializationinfo/) | Håller en samling av namngivna fält som representerar ett serialiserat objekt. Ej implementerad. Objekt av denna klass får endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller assertion-fel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [StreamingContext](./streamingcontext/) | Dummy-klass för att få de med StreamingContext-användning översatta klasserna att kompilera. Hantera inte instanser av denna klass med [SmartPtr](../system/smartptr/), de måste endast allokeras på stacken. |
## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [SerializationException](./serializationexception/) |  |