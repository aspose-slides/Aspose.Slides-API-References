---
title: SetAttributeNode()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega el XmlAttribute especificado.
type: docs
weight: 261
url: /es/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) método


Agrega el [XmlAttribute](../../xmlattribute/) especificado.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | El nodo [XmlAttribute](../../xmlattribute/) que se agregará a la colección de atributos de este elemento. |

### Valor devuelto

Si el atributo reemplaza a un atributo existente con el mismo nombre, se devuelve el [XmlAttribute](../../xmlattribute/) antiguo; de lo contrario, se devuelve **nullptr**.

## XmlElement::SetAttributeNode(String, String) método


Agrega el [XmlAttribute](../../xmlattribute/) especificado.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | [String](../../../system/string/) | El nombre local del atributo. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del atributo. |

### Valor devuelto

El [XmlAttribute](../../xmlattribute/) a agregar.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlAttribute](../../xmlattribute/)
* Clase [XmlElement](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)