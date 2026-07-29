---
title: get_SchemaInfo()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar schemainformation som har tilldelats den aktuella noden som ett resultat av schemavalidering.
type: docs
weight: 196
url: /sv/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo() metod


Returnerar schemainformation som har tilldelats den aktuella noden som ett resultat av schemavalidering.

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```


### Returvärde

Ett IXmlSchemaInfo-objekt som innehåller schemainformation för den aktuella noden. [Schema](../../../system.xml.schema/) information kan sättas på element, attribut eller på textnoder med ett icke-null [XmlReader::get_ValueType](../get_valuetype/) värde. Om den aktuella noden inte är någon av ovanstående nodtyper, eller om [XmlReader](../)-instansen inte rapporterar schemainformation, returnerar denna metod **nullptr**. Om denna metod anropas från ett [XmlTextReader](../../xmltextreader/)- eller [XmlValidatingReader](../../xmlvalidatingreader/)-objekt, returnerar den alltid **nullptr**. Dessa [XmlReader](../)-implementationer exponerar inte schemainformation via get_SchemaInfo-metoden.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* Klass [XmlReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)