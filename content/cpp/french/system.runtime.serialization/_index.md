---
title: "System::Runtime::Serialization"
second_title: Référence de l'API Aspose.Slides pour C++
description: 
type: docs
weight: 794
url: /fr/system.runtime.serialization/
---
## Classes

| Class | Description |
| --- | --- |
| [Details_SerializationException](./details_serializationexception/) |  |
| [FormatterConverter](./formatterconverter/) | Représente une implémentation de base de l'interface [System::Runtime::Serialization::IFormatterConverter](./iformatterconverter/). |
| [IFormatterConverter](./iformatterconverter/) | Fournit la connexion entre une instance de [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) et la classe fournie par le formatteur la mieux adaptée pour analyser les données à l'intérieur du [System::Runtime::Serialization::SerializationInfo](./serializationinfo/). |
| [ISerializable](./iserializable/) | Interface d'un objet qui peut être sérialisé. Les objets de cette classe ne doivent être alloués qu'à l'aide de la fonction [System::MakeObject()](../system/makeobject/). Ne jamais créer d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Toujours envelopper cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utiliser ce pointeur pour le passer aux fonctions en tant qu'argument. |
| [SerializationInfo](./serializationinfo/) | Contient un ensemble de champs nommés représentant l'objet sérialisé. Non implémenté. Les objets de cette classe ne doivent être alloués qu'à l'aide de la fonction [System::MakeObject()](../system/makeobject/). Ne jamais créer d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Toujours envelopper cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utiliser ce pointeur pour le passer aux fonctions en tant qu'argument. |
| [StreamingContext](./streamingcontext/) | Classe factice pour permettre la compilation des classes traduites utilisant StreamingContext. Ne gérez pas les instances de cette classe avec [SmartPtr](../system/smartptr/), elles doivent être allouées uniquement sur la pile. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [SerializationException](./serializationexception/) |  |