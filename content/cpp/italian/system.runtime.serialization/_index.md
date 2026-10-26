---
title: "System::Runtime::Serialization"
second_title: Riferimento API Aspose.Slides per C++
description: 
type: docs
weight: 794
url: /it/system.runtime.serialization/
---
## Classi

| Classe | Descrizione |
| --- | --- |
| [Details_SerializationException](./details_serializationexception/) |  |
| [FormatterConverter](./formatterconverter/) | Rappresenta un'implementazione di base dell'interfaccia [System::Runtime::Serialization::IFormatterConverter](./iformatterconverter/). |
| [IFormatterConverter](./iformatterconverter/) | Fornisce la connessione tra un'istanza di [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) e la classe fornita dal formattatore più adatta a analizzare i dati all'interno del [System::Runtime::Serialization::SerializationInfo](./serializationinfo/). |
| [ISerializable](./iserializable/) | Interfaccia di oggetto che può essere serializzato. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fallimenti di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarla alle funzioni come argomento. |
| [SerializationInfo](./serializationinfo/) | Contiene un insieme di campi con nome che rappresentano l'oggetto serializzato. Non implementato. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fallimenti di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarla alle funzioni come argomento. |
| [StreamingContext](./streamingcontext/) | Classe fittizia per consentire la compilazione delle classi tradotte che utilizzano StreamingContext. Non gestire le istanze di questa classe con [SmartPtr](../system/smartptr/), devono essere allocate solo sullo stack. |

## Typedef

| Typedef | Descrizione |
| --- | --- |
| [SerializationException](./serializationexception/) |  |