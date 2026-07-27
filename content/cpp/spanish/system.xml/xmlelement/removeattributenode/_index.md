---
title: RemoveAttributeNode()
second_title: Referencia de la API de Aspose.Slides para C++
description: Elimina el XmlAttribute especificado.
type: docs
weight: 274
url: /es/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) método


Elimina el [XmlAttribute](../../xmlattribute/) especificado.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```


### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| oldAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | El nodo [XmlAttribute](../../xmlattribute/) a eliminar. Si el atributo eliminado tiene un valor predeterminado, se reemplaza inmediatamente. |

### Return Value

El [XmlAttribute](../../xmlattribute/) eliminado o **nullptr** si **oldAttr** no es un nodo de atributo del [XmlElement](../).

## XmlElement::RemoveAttributeNode(String, String) método


Elimina el [XmlAttribute](../../xmlattribute/) especificado por el nombre local y el URI del espacio de nombres. (Si el atributo eliminado tiene un valor predeterminado, se reemplaza inmediatamente).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```


### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | [String](../../../system/string/) | El nombre local del atributo. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del atributo. |

### Return Value

El [XmlAttribute](../../xmlattribute/) eliminado o **nullptr** si el [XmlElement](../) no tiene un nodo de atributo coincidente.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlAttribute](../../xmlattribute/)
* Clase [XmlElement](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Xml](../../)
* Library [Aspose.Slides](../../../)