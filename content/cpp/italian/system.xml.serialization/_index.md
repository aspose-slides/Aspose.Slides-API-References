---
title: "System::Xml::Serialization"
second_title: Riferimento API Aspose.Slides per C++
description: 
type: docs
weight: 1158
url: /it/system.xml.serialization/
---
## Classi

| Classe | Descrizione |
| --- | --- |
| [IXmlSerializable](./ixmlserializable/) | Fornisce formattazione personalizzata per la serializzazione e la deserializzazione XML. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai istanze di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o falle di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usare questo puntatore per passarlo alle funzioni come argomento. |
| [XmlAttributeOverrides](./xmlattributeoverrides/) | Consente di sovrascrivere gli attributi quando [XmlSerializer](./xmlserializer/) viene usato per serializzare o deserializzare un oggetto. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai istanze di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o falle di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usare questo puntatore per passarlo alle funzioni come argomento. |
| [XmlRootAttribute](./xmlrootattribute/) | Segna il bersaglio dell'attributo come elemento radice XML e controlla la sua serializzazione XML. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai istanze di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o falle di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usare questo puntatore per passarlo alle funzioni come argomento. |
| [XmlSerializationReader](./xmlserializationreader/) | Classe di servizio che migliora l'esperienza [XmlReader](../system.xml/xmlreader/). |
| [XmlSerializationWriter](./xmlserializationwriter/) | Classe di servizio che migliora l'esperienza [XmlWriter](../system.xml/xmlwriter/). |
| [XmlSerializer](./xmlserializer/) | Esegue la serializzazione e la deserializzazione di oggetti verso e da documenti XML. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai istanze di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o falle di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usare questo puntatore per passarlo alle funzioni come argomento. |
| [XmlSerializerImplementation](./xmlserializerimplementation/) | Classe interna da usare con [XmlSerializer](./xmlserializer/). |
| [XmlSerializerNamespaces](./xmlserializernamespaces/) | Contiene gli spazi dei nomi XML e i prefissi che [Serialization::XmlSerializer](./xmlserializer/) utilizza per generare nomi qualificati in un'istanza di documento XML. |