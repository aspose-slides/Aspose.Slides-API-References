---
title: RemoveRecursive()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt das angegebene XML Schema-Definitionssprache (XSD)-Schema und alle Schemas, die es aus dem XmlSchemaSet importiert.
type: docs
weight: 183
url: /de/system.xml.schema/xmlschemaset/removerecursive/
---
## XmlSchemaSet::RemoveRecursive(const SharedPtr\<XmlSchema\>\&) Methode

Entfernt das angegebene XML [Schema](../../) Definitionssprache (XSD)-Schema und alle Schemas, die es aus dem [XmlSchemaSet](../) importiert.

```cpp
bool System::Xml::Schema::XmlSchemaSet::RemoveRecursive(const SharedPtr<XmlSchema> &schemaToRemove)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| schemaToRemove | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Das [XmlSchema](../../xmlschema/)-Objekt, das aus dem [XmlSchemaSet](../) entfernt werden soll. |

### Rückgabewert

**true**, wenn das [XmlSchema](../../xmlschema/)-Objekt und alle seine Importe erfolgreich entfernt wurden; andernfalls **false**.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlSchema](../../xmlschema/)
* Klasse [XmlSchemaSet](../)
* Namensraum [System::Xml::Schema](../../)
* Bibliothek [Aspose.Slides](../../../)