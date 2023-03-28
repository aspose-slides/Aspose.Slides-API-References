---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Adds the schema located by the given URL into the schema collection.
type: docs
weight: 40
url: /cpp/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const [String](../../../system/string/)\&, const [String](../../../system/string/)\&) method


Adds the schema located by the given URL into the schema collection.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | The namespace URI associated with the schema. For XML Schemas, this will typically be the **targetNamespace**. |
| uri | const [String](../../../system/string/)\& | The URL that specifies the schema to load. |

### Return Value

The [XmlSchema](../../xmlschema/) added to the schema collection; **nullptr** if the schema being added is an XDR schema or if there are compilation errors in the schema.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)
## XmlSchemaCollection::Add(const [String](../../../system/string/)\&, const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\&) method


Adds the schema contained in the [XmlReader](../../../system.xml/xmlreader/) to the schema collection.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | The namespace URI associated with the schema. For XML Schemas, this will typically be the **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) containing the schema to add. |

### Return Value

The [XmlSchema](../../xmlschema/) added to the schema collection; **nullptr** if the schema being added is an XDR schema or if there are compilation errors in the schema.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)
## XmlSchemaCollection::Add(const [String](../../../system/string/)\&, const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\&) method


Adds the schema contained in the [XmlReader](../../../system.xml/xmlreader/) to the schema collection. The specified [XmlResolver](../../../system.xml/xmlresolver/) is used to resolve any external resources.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | The namespace URI associated with the schema. For XML Schemas, this will typically be the **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) containing the schema to add. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve namespaces referenced in **include** and **import** elements or **x-schema** attribute (XDR schemas). If this is **nullptr**, external references are not resolved. |

### Return Value

The [XmlSchema](../../xmlschema/) added to the schema collection; **nullptr** if the schema being added is an XDR schema or if there are compilation errors in the schema.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)
## XmlSchemaCollection::Add(const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\&) method


Adds the [XmlSchema](../../xmlschema/) to the collection.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | The [XmlSchema](../../xmlschema/) to add to the collection. |

### Return Value

The [XmlSchema](../../xmlschema/) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)
## XmlSchemaCollection::Add(const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\&, const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\&) method


Adds the [XmlSchema](../../xmlschema/) to the collection. The specified [XmlResolver](../../../system.xml/xmlresolver/) is used to resolve any external references.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | The [XmlSchema](../../xmlschema/) to add to the collection. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve namespaces referenced in **include** and **import** elements. If this is **nullptr**, external references are not resolved. |

### Return Value

The [XmlSchema](../../xmlschema/) added to the schema collection.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)
## XmlSchemaCollection::Add(const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaCollection](../)\>\&) method


Adds all the namespaces defined in the given collection (including their associated schemas) to this collection.

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaCollection](../)\>\& | The [XmlSchemaCollection](../) you want to add to this collection. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaCollection](../)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)
