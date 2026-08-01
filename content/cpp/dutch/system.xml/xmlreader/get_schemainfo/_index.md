---
title: get_SchemaInfo()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de schemainformatie die aan het huidige knooppunt is toegewezen als gevolg van schemavalidatie.
type: docs
weight: 196
url: /nl/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo() methode


Retourneert de schemainformatie die aan het huidige knooppunt is toegewezen als resultaat van schemavalidatie.

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```


### Retourwaarde

Een IXmlSchemaInfo-object dat de schemainformatie voor het huidige knooppunt bevat. [Schema](../../../system.xml.schema/) informatie kan worden ingesteld op elementen, attributen of op tekstknooppunten met een niet-null [XmlReader::get_ValueType](../get_valuetype/) waarde. Als het huidige knooppunt niet een van de bovenstaande knooppuntetypes is, of als de [XmlReader](../)-instantie geen schemainformatie rapporteert, geeft deze methode **nullptr** terug. Als deze methode wordt aangeroepen vanaf een [XmlTextReader](../../xmltextreader/) of een [XmlValidatingReader](../../xmlvalidatingreader/)-object, geeft deze methode altijd **nullptr** terug. Deze [XmlReader](../)-implementaties onthullen geen schemainformatie via de get_SchemaInfo-methode.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* Klasse [XmlReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)