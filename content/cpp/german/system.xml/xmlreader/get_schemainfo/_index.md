---
title: get_SchemaInfo()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Schemainformationen zurück, die dem aktuellen Knoten infolge einer Schema-Validierung zugewiesen wurden.
type: docs
weight: 196
url: /de/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo() Methode

Gibt die Schemainformationen zurück, die dem aktuellen Knoten infolge einer Schema-Validierung zugewiesen wurden.

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```

### Rückgabewert

Ein IXmlSchemaInfo-Objekt, das die Schemainformationen für den aktuellen Knoten enthält. [Schema](../../../system.xml.schema/) Informationen können an Elementen, Attributen oder an Textknoten mit einem nicht null [XmlReader::get_ValueType](../get_valuetype/) Wert gesetzt werden. Wenn der aktuelle Knoten keiner der oben genannten Knotentypen ist oder wenn die [XmlReader](../) Instanz keine Schemainformationen meldet, gibt diese Methode **nullptr** zurück. Wenn diese Methode von einem [XmlTextReader](../../xmltextreader/)- oder einem [XmlValidatingReader](../../xmlvalidatingreader/)-Objekt aufgerufen wird, gibt diese Methode immer **nullptr** zurück. Diese [XmlReader](../)-Implementierungen geben keine Schemainformationen über die get_SchemaInfo Methode frei.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* Klasse [XmlReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)