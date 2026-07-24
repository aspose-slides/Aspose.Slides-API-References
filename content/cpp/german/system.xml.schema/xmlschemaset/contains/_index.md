---
title: Contains()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt an, ob ein XML Schema Definition Language (XSD) Schema mit dem angegebenen Ziel-Namespace-URI im XmlSchemaSet enthalten ist.
type: docs
weight: 196
url: /de/system.xml.schema/xmlschemaset/contains/
---
## XmlSchemaSet::Contains(String) Methode

Gibt an, ob ein XML [Schema](../../) Definitionssprache (XSD) Schema mit dem angegebenen Ziel-Namespace-URI im [XmlSchemaSet](../) enthalten ist.

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(String targetNamespace)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Die **targetNamespace** Eigenschaft des Schemas. |

### Rückgabewert

**true** wenn ein Schema mit dem angegebenen Ziel-Namespace-URI im [XmlSchemaSet](../) enthalten ist; andernfalls **false**.

## XmlSchemaSet::Contains(const SharedPtr\<XmlSchema\>\&) Methode

Gibt an, ob das angegebene XML [Schema](../../) Definitionssprache (XSD) [XmlSchema](../../xmlschema/) Objekt im [XmlSchemaSet](../) enthalten ist.

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(const SharedPtr<XmlSchema> &schema)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Das [XmlSchema](../../xmlschema/) Objekt. |

### Rückgabewert

**true** wenn das [XmlSchema](../../xmlschema/) Objekt im [XmlSchemaSet](../) enthalten ist; andernfalls **false**.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [XmlSchemaSet](../)
* Klasse [XmlSchema](../../xmlschema/)
* Namensraum [System::Xml::Schema](../../)
* Bibliothek [Aspose.Slides](../../../)