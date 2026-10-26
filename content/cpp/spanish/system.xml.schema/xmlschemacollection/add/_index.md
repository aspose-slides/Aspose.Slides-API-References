---
title: Add()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega el esquema ubicado en la URL proporcionada a la colección de esquemas.
type: docs
weight: 40
url: /es/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const String\&, const String\&) método


Agrega el esquema ubicado en la URL proporcionada a la colección de esquemas.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | El URI del espacio de nombres asociado con el esquema. Para los esquemas XML, normalmente será el **targetNamespace**. |
| uri | const [String](../../../system/string/)\& | La URL que especifica el esquema a cargar. |

### Valor devuelto

El [XmlSchema](../../xmlschema/) agregado a la colección de esquemas; **nullptr** si el esquema que se está agregando es un esquema XDR o si hay errores de compilación en el esquema.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&) método


Agrega el esquema contenido en el [XmlReader](../../../system.xml/xmlreader/) a la colección de esquemas.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | El URI del espacio de nombres asociado con el esquema. Para los esquemas XML, normalmente será el **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) que contiene el esquema a agregar. |

### Valor devuelto

El [XmlSchema](../../xmlschema/) agregado a la colección de esquemas; **nullptr** si el esquema que se está agregando es un esquema XDR o si hay errores de compilación en el esquema.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) método


Agrega el esquema contenido en el [XmlReader](../../../system.xml/xmlreader/) a la colección de esquemas. El [XmlResolver](../../../system.xml/xmlresolver/) especificado se utiliza para resolver cualquier recurso externo.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | El URI del espacio de nombres asociado con el esquema. Para los esquemas XML, normalmente será el **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) que contiene el esquema a agregar. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) utilizado para resolver los espacios de nombres referenciados en los elementos **include** y **import** o en el atributo **x-schema** (esquemas XDR). Si es **nullptr**, no se resuelven referencias externas. |

### Valor devuelto

El [XmlSchema](../../xmlschema/) agregado a la colección de esquemas; **nullptr** si el esquema que se está agregando es un esquema XDR o si hay errores de compilación en el esquema.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&) método


Agrega el [XmlSchema](../../xmlschema/) a la colección.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | El [XmlSchema](../../xmlschema/) a agregar a la colección. |

### Valor devuelto

El objeto [XmlSchema](../../xmlschema/).

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) método


Agrega el [XmlSchema](../../xmlschema/) a la colección. El [XmlResolver](../../../system.xml/xmlresolver/) especificado se utiliza para resolver cualquier referencia externa.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | El [XmlSchema](../../xmlschema/) a agregar a la colección. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) utilizado para resolver los espacios de nombres referenciados en los elementos **include** y **import**. Si es **nullptr**, no se resuelven referencias externas. |

### Valor devuelto

El [XmlSchema](../../xmlschema/) agregado a la colección de esquemas.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchemaCollection\>\&) método


Agrega todos los espacios de nombres definidos en la colección dada (incluidos sus esquemas asociados) a esta colección.

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaCollection](../)\>\& | El [XmlSchemaCollection](../) que desea agregar a esta colección. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlSchema](../../xmlschema/)
* Clase [String](../../../system/string/)
* Clase [XmlSchemaCollection](../)
* Clase [XmlReader](../../../system.xml/xmlreader/)
* Clase [XmlResolver](../../../system.xml/xmlresolver/)
* Espacio de nombres [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)