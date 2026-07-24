---
title: Reprocess()
second_title: Aspose.Slides für C++ API-Referenz
description: Verarbeitet ein XML Schema Definition Language (XSD)-Schema, das bereits im XmlSchemaSet existiert.
type: docs
weight: 222
url: /de/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess(SharedPtr\<XmlSchema\>) Methode


Verarbeitet ein XML [Schema](../../)-Definitionsschema (XSD), das bereits im [XmlSchemaSet](../) existiert.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| schema | [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\> | Das Schema, das erneut verarbeitet werden soll. |

### Rückgabewert

Ein [XmlSchema](../../xmlschema/)-Objekt, wenn das Schema ein gültiges Schema ist. Wenn das Schema nicht gültig ist und ein ValidationEventHandler angegeben ist, wird **nullptr** zurückgegeben und das entsprechende Validierungsereignis ausgelöst. Andernfalls wird eine XmlSchemaException ausgelöst.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlSchema](../../xmlschema/)
* Klasse [XmlSchemaSet](../)
* Namensraum [System::Xml::Schema](../../)
* Bibliothek [Aspose.Slides](../../../)