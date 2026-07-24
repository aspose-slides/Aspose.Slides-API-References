---
title: Remove()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt das angegebene XML Schema-Definitionssprache (XSD)-Schema aus dem XmlSchemaSet.
type: docs
weight: 170
url: /de/system.xml.schema/xmlschemaset/remove/
---
## XmlSchemaSet::Remove(const SharedPtr\<XmlSchema\>\&) Methode

Entfernt das angegebene XML [Schema](../../)-Definitionssprache (XSD)-Schema aus dem [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Remove(const SharedPtr<XmlSchema> &schema)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Das [XmlSchema](../../xmlschema/)-Objekt, das aus dem [XmlSchemaSet](../) entfernt werden soll. |

### Rückgabewert

Das [XmlSchema](../../xmlschema/)-Objekt, das aus dem [XmlSchemaSet](../) entfernt wurde, oder **nullptr**, falls das Schema im [XmlSchemaSet](../) nicht gefunden wurde.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlSchema](../../xmlschema/)
* Klasse [XmlSchemaSet](../)
* Namensraum [System::Xml::Schema](../../)
* Bibliothek [Aspose.Slides](../../../)