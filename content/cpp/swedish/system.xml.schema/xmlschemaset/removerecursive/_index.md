---
title: RemoveRecursive()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort det angivna XML Schema definition language (XSD) schemat och alla scheman som det importerar från XmlSchemaSet.
type: docs
weight: 183
url: /sv/system.xml.schema/xmlschemaset/removerecursive/
---
## XmlSchemaSet::RemoveRecursive(const SharedPtr\<XmlSchema\>\&) metod


Tar bort det angivna XML [Schema](../../) definition language (XSD) schemat och alla scheman som det importerar från [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::RemoveRecursive(const SharedPtr<XmlSchema> &schemaToRemove)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| schemaToRemove | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Det [XmlSchema](../../xmlschema/)-objektet som ska tas bort från [XmlSchemaSet](../). |

### Returvärde

**true** if the [XmlSchema](../../xmlschema/) object and all its imports were successfully removed; otherwise, **false**.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlSchema](../../xmlschema/)
* Klass [XmlSchemaSet](../)
* Namnrymd [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)