---
title: Add()
second_title: Aspose.Slides für C++ API Referenz
description: Fügt das XML Schema Definitionssprache (XSD) Schema an der angegebenen URL zum XmlSchemaSet hinzu.
type: docs
weight: 157
url: /de/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(String, const String\&) Methode


Fügt das XML [Schema](../../) Definitionssprache (XSD) Schema an der angegebenen URL zum [XmlSchemaSet](../) hinzu.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Der **targetNamespace**-Wert des Schemas oder **nullptr**, um den im Schema angegebenen **targetNamespace** zu verwenden. |
| schemaUri | const [String](../../../system/string/)\& | Die URL, die das zu ladende Schema angibt. |

### Rückgabewert

Ein [XmlSchema](../../xmlschema/)-Objekt, wenn das Schema gültig ist. Wenn das Schema nicht gültig ist und ein ValidationEventHandler angegeben wurde, wird **nullptr** zurückgegeben und das entsprechende Validierungsereignis ausgelöst. Andernfalls wird eine XmlSchemaException ausgelöst.

## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) Methode


Fügt das XML [Schema](../../) Definitionssprache (XSD) Schema, das im [XmlReader](../../../system.xml/xmlreader/) enthalten ist, zum [XmlSchemaSet](../) hinzu.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Der **targetNamespace**-Wert des Schemas oder **nullptr**, um den im Schema angegebenen **targetNamespace** zu verwenden. |
| schemaDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Das [XmlReader](../../../system.xml/xmlreader/)-Objekt. |

### Rückgabewert

Ein [XmlSchema](../../xmlschema/)-Objekt, wenn das Schema gültig ist. Wenn das Schema nicht gültig ist und ein ValidationEventHandler angegeben wurde, wird **nullptr** zurückgegeben und das entsprechende Validierungsereignis ausgelöst. Andernfalls wird eine XmlSchemaException ausgelöst.

## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) Methode


Fügt alle XML [Schema](../../) Definitionssprache (XSD) Schemas im angegebenen [XmlSchemaSet](../) zum [XmlSchemaSet](../) hinzu.

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../)\>\& | Das [XmlSchemaSet](../)-Objekt. |

## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) Methode


Fügt das gegebene [XmlSchema](../../xmlschema/) zum [XmlSchemaSet](../) hinzu.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Das [XmlSchema](../../xmlschema/)-Objekt, das zum [XmlSchemaSet](../) hinzugefügt werden soll. |

### Rückgabewert

Ein [XmlSchema](../../xmlschema/)-Objekt, wenn das Schema gültig ist. Wenn das Schema nicht gültig ist und ein ValidationEventHandler angegeben wurde, wird **nullptr** zurückgegeben und das entsprechende Validierungsereignis ausgelöst. Andernfalls wird eine XmlSchemaException ausgelöst.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlSchema](../../xmlschema/)
* Klasse [String](../../../system/string/)
* Klasse [XmlSchemaSet](../)
* Klasse [XmlReader](../../../system.xml/xmlreader/)
* Namensraum [System::Xml::Schema](../../)
* Bibliothek [Aspose.Slides](../../../)