---
title: Add()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega el esquema del lenguaje de definición XML Schema (XSD) en la URL especificada al XmlSchemaSet.
type: docs
weight: 157
url: /es/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(String, const String\&) method


Agrega el esquema del lenguaje de definición XML [Schema](../../) (XSD) en la URL especificada al [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | El valor **targetNamespace** del esquema, o **nullptr** para usar el **targetNamespace** especificado en el esquema. |
| schemaUri | const [String](../../../system/string/)\& | La URL que especifica el esquema a cargar. |

### Valor devuelto

Un objeto [XmlSchema](../../xmlschema/) si el esquema es válido. Si el esquema no es válido y se especifica un ValidationEventHandler, entonces se devuelve **nullptr** y se genera el evento de validación correspondiente. De lo contrario, se lanza una XmlSchemaException.

## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) method


Agrega el esquema del lenguaje de definición XML [Schema](../../) (XSD) contenido en el [XmlReader](../../../system.xml/xmlreader/) al [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | El valor **targetNamespace** del esquema, o **nullptr** para usar el **targetNamespace** especificado en el esquema. |
| schemaDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | El objeto [XmlReader](../../../system.xml/xmlreader/). |

### Valor devuelto

Un objeto [XmlSchema](../../xmlschema/) si el esquema es válido. Si el esquema no es válido y se especifica un ValidationEventHandler, entonces se devuelve **nullptr** y se genera el evento de validación correspondiente. De lo contrario, se lanza una XmlSchemaException.

## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) method


Agrega todos los esquemas del lenguaje de definición XML [Schema](../../) (XSD) en el [XmlSchemaSet](../) dado al [XmlSchemaSet](../).

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../)\>\& | El objeto [XmlSchemaSet](../). |

## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) method


Agrega el [XmlSchema](../../xmlschema/) dado al [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | El objeto [XmlSchema](../../xmlschema/) a agregar al [XmlSchemaSet](../). |

### Valor devuelto

Un objeto [XmlSchema](../../xmlschema/) si el esquema es válido. Si el esquema no es válido y se especifica un ValidationEventHandler, entonces se devuelve **nullptr** y se genera el evento de validación correspondiente. De lo contrario, se lanza una XmlSchemaException.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlSchema](../../xmlschema/)
* Clase [String](../../../system/string/)
* Clase [XmlSchemaSet](../)
* Clase [XmlReader](../../../system.xml/xmlreader/)
* Espacio de nombres [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)