---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt das durch die angegebene URL gefundene Schema zur Schemasammlung hinzu.
type: docs
weight: 40
url: /de/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const String\&, const String\&) Methode

Fügt das durch die angegebene URL gefundene Schema zur Schemasammlung hinzu.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | Der Namespace-URI, der dem Schema zugeordnet ist. Für XML-Schemas ist dies typischerweise das **targetNamespace**. |
| uri | const [String](../../../system/string/)\& | Die URL, die das zu ladende Schema angibt. |

### Rückgabewert

Das [XmlSchema](../../xmlschema/) zur Schemasammlung hinzugefügt; **nullptr** wenn das hinzuzufügende Schema ein XDR-Schema ist oder wenn Kompilierungsfehler im Schema vorliegen.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&) Methode

Fügt das im [XmlReader](../../../system.xml/xmlreader/) enthaltene Schema zur Schemasammlung hinzu.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | Der Namespace-URI, der dem Schema zugeordnet ist. Für XML-Schemas ist dies typischerweise das **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) das das hinzuzufügende Schema enthält. |

### Rückgabewert

Das [XmlSchema](../../xmlschema/) zur Schemasammlung hinzugefügt; **nullptr** wenn das hinzuzufügende Schema ein XDR-Schema ist oder wenn Kompilierungsfehler im Schema vorliegen.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) Methode

Fügt das im [XmlReader](../../../system.xml/xmlreader/) enthaltene Schema zur Schemasammlung hinzu. Der angegebene [XmlResolver](../../../system.xml/xmlresolver/) wird verwendet, um externe Ressourcen aufzulösen.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | Der Namespace-URI, der dem Schema zugeordnet ist. Für XML-Schemas ist dies typischerweise das **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) das das hinzuzufügende Schema enthält. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Der [XmlResolver](../../../system.xml/xmlresolver/) zum Auflösen von Namespaces, die in **include**- und **import**-Elementen oder im **x-schema**-Attribut (XDR-Schemas) referenziert werden. Wenn dies **nullptr** ist, werden externe Verweise nicht aufgelöst. |

### Rückgabewert

Das [XmlSchema](../../xmlschema/) zur Schemasammlung hinzugefügt; **nullptr** wenn das hinzuzufügende Schema ein XDR-Schema ist oder wenn Kompilierungsfehler im Schema vorliegen.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&) Methode

Fügt das [XmlSchema](../../xmlschema/) zur Sammlung hinzu.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Das [XmlSchema](../../xmlschema/) zum Hinzufügen zur Sammlung. |

### Rückgabewert

Das [XmlSchema](../../xmlschema/)-Objekt.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) Methode

Fügt das [XmlSchema](../../xmlschema/) zur Sammlung hinzu. Der angegebene [XmlResolver](../../../system.xml/xmlresolver/) wird verwendet, um externe Verweise aufzulösen.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Der [XmlSchema](../../xmlschema/) zum Hinzufügen zur Sammlung. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Der [XmlResolver](../../../system.xml/xmlresolver/) zum Auflösen von Namespaces, die in **include**- und **import**-Elementen referenziert werden. Wenn dies **nullptr** ist, werden externe Verweise nicht aufgelöst. |

### Rückgabewert

Das [XmlSchema](../../xmlschema/) zur Schemasammlung hinzugefügt.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchemaCollection\>\&) Methode

Fügt alle in der angegebenen Sammlung definierten Namespaces (einschließlich ihrer zugehörigen Schemata) zu dieser Sammlung hinzu.

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaCollection](../)\>\& | Die [XmlSchemaCollection](../), die Sie zu dieser Sammlung hinzufügen möchten. |

## Siehe Auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaCollection](../)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)