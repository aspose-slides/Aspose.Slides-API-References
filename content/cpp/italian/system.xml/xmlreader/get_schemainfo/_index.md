---
title: get_SchemaInfo()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce le informazioni dello schema assegnate al nodo corrente come risultato della validazione dello schema.
type: docs
weight: 196
url: /it/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo() metodo

Restituisce le informazioni dello schema che sono state assegnate al nodo corrente come risultato della convalida dello schema.

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```

### Valore restituito

Un oggetto IXmlSchemaInfo che contiene le informazioni dello schema per il nodo corrente. [Schema](../../../system.xml.schema/) le informazioni possono essere impostate su elementi, attributi o sui nodi di testo con un valore [XmlReader::get_ValueType](../get_valuetype/) non nullo. Se il nodo corrente non è uno dei tipi di nodo sopra elencati, o se l'istanza [XmlReader](../) non fornisce informazioni sullo schema, questo metodo restituisce **nullptr**. Se questo metodo viene chiamato da un oggetto [XmlTextReader](../../xmltextreader/) o da un oggetto [XmlValidatingReader](../../xmlvalidatingreader/), questo metodo restituisce sempre **nullptr**. Queste implementazioni [XmlReader](../) non espongono le informazioni dello schema attraverso il metodo get_SchemaInfo.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* Classe [XmlReader](../)
* Namespace [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)