---
title: Contains()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt einen Wert zurück, der angibt, ob das targetNamespace des angegebenen XmlSchema in der Sammlung enthalten ist.
type: docs
weight: 66
url: /de/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) method


Gibt einen Wert zurück, der angibt, ob das **targetNamespace** des angegebenen [XmlSchema](../../xmlschema/) in der Sammlung enthalten ist.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Das [XmlSchema](../../xmlschema/)-Objekt. |

### Rückgabewert

**true** falls ein Schema in der Sammlung mit demselben **targetNamespace** vorhanden ist; andernfalls **false**.

## XmlSchemaCollection::Contains(const String\&) method


Gibt einen Wert zurück, der angibt, ob ein Schema mit dem angegebenen Namensraum in der Sammlung enthalten ist.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | Der URI des Namensraums, der dem Schema zugeordnet ist. Für XML-Schemas ist dies typischerweise das Zielnamensraum. |

### Rückgabewert

**true** falls ein Schema mit dem angegebenen Namensraum in der Sammlung enthalten ist; andernfalls **false**.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlSchema](../../xmlschema/)
* Klasse [XmlSchemaCollection](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)