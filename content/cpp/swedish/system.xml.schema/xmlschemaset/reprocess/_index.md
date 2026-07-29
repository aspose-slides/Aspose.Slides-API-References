---
title: Reprocess()
second_title: Aspose.Slides för C++ API-referens
description: Bearbetar om ett XML Schema definitionsspråk (XSD) schema som redan finns i XmlSchemaSet.
type: docs
weight: 222
url: /sv/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess(SharedPtr\<XmlSchema\>) metod

Bearbetar om en XML [Schema](../../) definitionsspråk (XSD) schema som redan finns i [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| schema | [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\> | Schemat som ska bearbetas om. |

### Returvärde

Ett [XmlSchema](../../xmlschema/)-objekt om schemat är ett giltigt schema. Om schemat inte är giltigt och en ValidationEventHandler specificeras, **nullptr** returneras och den lämpliga valideringshändelsen utlöses. Annars kastas ett XmlSchemaException.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)