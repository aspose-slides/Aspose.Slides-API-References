---
title: "System::Runtime::Serialization"
second_title: Aspose.Slides für C++ API Referenz
description: 
type: docs
weight: 794
url: /de/system.runtime.serialization/
---
## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [Details_SerializationException](./details_serializationexception/) |  |
| [FormatterConverter](./formatterconverter/) | Stellt eine Basisimplementierung des [System::Runtime::Serialization::IFormatterConverter](./iformatterconverter/) Interface dar. |
| [IFormatterConverter](./iformatterconverter/) | Stellt die Verbindung zwischen einer Instanz von [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) und der vom Formatierer bereitgestellten Klasse her, die am besten geeignet ist, die Daten im [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) zu analysieren. |
| [ISerializable](./iserializable/) | Interface eines Objekts, das serialisierbar ist. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/)-Pointer ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [SerializationInfo](./serializationinfo/) | Enthält eine Menge benannter Felder, die ein serialisiertes Objekt repräsentieren. Nicht implementiert. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/)-Pointer ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [StreamingContext](./streamingcontext/) | Dummyklasse, um übersetzte Klassen, die StreamingContext verwenden, kompilierbar zu machen. Verwalten Sie keine Instanzen dieser Klasse mit [SmartPtr](../system/smartptr/), sie dürfen nur auf dem Stack alloziert werden. |

## Typdefinitionen

| Typdefinition | Beschreibung |
| --- | --- |
| [SerializationException](./serializationexception/) |  |