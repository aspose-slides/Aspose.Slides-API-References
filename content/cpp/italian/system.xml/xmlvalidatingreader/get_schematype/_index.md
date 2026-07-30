---
title: get_SchemaType()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce un oggetto di tipo schema.
type: docs
weight: 287
url: /it/system.xml/xmlvalidatingreader/get_schematype/
---
## XmlValidatingReader::get_SchemaType() method

Restituisce un oggetto di tipo schema.

```cpp
SharedPtr<Object> System::Xml::XmlValidatingReader::get_SchemaType()
```

### Valore restituito

XmlSchemaDatatype, XmlSchemaSimpleType o XmlSchemaComplexType a seconda che il valore del nodo sia un tipo integrato di XML [Schema](../../../system.xml.schema/) definition language (XSD) o un simpleType o complexType definito dall'utente; **nullptr** se il nodo corrente non ha un tipo schema.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)