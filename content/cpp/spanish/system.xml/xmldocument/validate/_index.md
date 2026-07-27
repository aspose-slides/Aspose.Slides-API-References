---
title: Validate()
second_title: Referencia de la API de Aspose.Slides for C++
description: "Valida el XmlDocument contra los esquemas del Lenguaje de Definición de Esquema XML (XSD) contenidos en la lista XmlDocument::get_Schemas."
type: docs
weight: 573
url: /es/system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) método


Valida el [XmlDocument](../) contra los esquemas del Lenguaje de Definición XML [Schema](../../../system.xml.schema/) (XSD) contenidos en la lista [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | El objeto [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) que recibe información sobre advertencias y errores de validación de esquemas. |

## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) método


Valida el objeto [XmlNode](../../xmlnode/) especificado contra los esquemas del Lenguaje de Definición XML [Schema](../../../system.xml.schema/) (XSD) en la lista [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | El objeto [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) que recibe información sobre advertencias y errores de validación de esquemas. |
| nodeToValidate | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | El objeto [XmlNode](../../xmlnode/) creado a partir de un [XmlDocument](../) para validar. |

## Ver también

* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlDocument](../)
* Clase [XmlNode](../../xmlnode/)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)