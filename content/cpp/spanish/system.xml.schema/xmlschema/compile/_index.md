---
title: Compile()
second_title: Referencia de la API de Aspose.Slides para C++
description: Compila el modelo de objetos de esquema XML (SOM) en información de esquema para validación. Se utiliza para comprobar la estructura sintáctica y semántica del SOM construido programáticamente. La verificación de validación semántica se realiza durante la compilación.
type: docs
weight: 352
url: /es/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) método


Compila el modelo XML [Schema](../../)[Object](../../../system/object/) (SOM) en información de esquema para validación. Se utiliza para comprobar la estructura sintáctica y semántica del SOM construido programáticamente. La comprobación de validación semántica se realiza durante la compilación.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | El controlador de eventos de validación que recibe información sobre los errores de validación XML [Schema](../../). |

## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) método


Compila el modelo XML [Schema](../../)[Object](../../../system/object/) (SOM) en información de esquema para validación. Se utiliza para comprobar la estructura sintáctica y semántica del SOM construido programáticamente. La comprobación de validación semántica se realiza durante la compilación.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | El controlador de eventos de validación que recibe información sobre los errores de validación XML [Schema](../../). |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) utilizado para resolver los espacios de nombres referenciados en los elementos **include** y **import**. |

## Ver también

* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlSchema](../)
* Clase [XmlResolver](../../../system.xml/xmlresolver/)
* Espacio de nombres [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)