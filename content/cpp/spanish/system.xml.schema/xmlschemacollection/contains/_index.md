---
title: Contains()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve un valor que indica si el targetNamespace del XmlSchema especificado está en la colección.
type: docs
weight: 66
url: /es/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) método


Devuelve un valor que indica si el **targetNamespace** del [XmlSchema](../../xmlschema/) especificado está en la colección.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | El objeto [XmlSchema](../../xmlschema/). |

### Valor devuelto

**true** si hay un esquema en la colección con el mismo **targetNamespace**; de lo contrario, **false**.

## XmlSchemaCollection::Contains(const String\&) método


Devuelve un valor que indica si un esquema con el espacio de nombres especificado está en la colección.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | El URI del espacio de nombres asociado con el esquema. Para los XML Schemas, normalmente será el espacio de nombres de destino. |

### Valor devuelto

**true** si un esquema con el espacio de nombres especificado está en la colección; de lo contrario, **false**.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlSchema](../../xmlschema/)
* Clase [XmlSchemaCollection](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)