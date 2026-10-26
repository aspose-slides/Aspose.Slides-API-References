---
title: RemoveRecursive()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Odstraňuje zadané schéma XML Schema Definition Language (XSD) a všechna schémata, která importuje ze XmlSchemaSet.
type: docs
weight: 183
url: /cs/system.xml.schema/xmlschemaset/removerecursive/
---
## XmlSchemaSet::RemoveRecursive(const SharedPtr\<XmlSchema\>\&) metoda

Odstraňuje zadané XML [Schema](../../) definice jazyka (XSD) schéma a všechna schémata, která importuje ze [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::RemoveRecursive(const SharedPtr<XmlSchema> &schemaToRemove)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| schemaToRemove | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Objekt [XmlSchema](../../xmlschema/) k odstranění z [XmlSchemaSet](../). |

### Návratová hodnota

**true** pokud byl objekt [XmlSchema](../../xmlschema/) a všechny jeho importy úspěšně odstraněny; jinak **false**.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [XmlSchema](../../xmlschema/)
* třída [XmlSchemaSet](../)
* jmenný prostor [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)