---
title: RemoveNamedItem()
second_title: Aspose.Slides for C++ Referencia de API
description: Elimina el nodo del XmlNamedNodeMap.
type: docs
weight: 40
url: /es/system.xml/xmlnamednodemap/removenameditem/
---
## XmlNamedNodeMap::RemoveNamedItem(String) método


Elimina el nodo de [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String name)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre calificado del nodo a eliminar. El nombre se compara con el valor [XmlNode::get_Name](../../xmlnode/get_name/) del nodo coincidente. |

### Valor devuelto

El [XmlNode](../../xmlnode/) eliminado de este [XmlNamedNodeMap](../) o **nullptr** si no se encontró un nodo coincidente.

## XmlNamedNodeMap::RemoveNamedItem(String, String) método


Elimina un nodo con los valores [XmlNode::get_LocalName](../../xmlnode/get_localname/) y [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) coincidentes.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String localName, String namespaceURI)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | [String](../../../system/string/) | El nombre local del nodo a eliminar. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del nodo a eliminar. |

### Valor devuelto

El [XmlNode](../../xmlnode/) eliminado o **nullptr** si no se encontró un nodo coincidente.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNode](../../xmlnode/)
* Clase [String](../../../system/string/)
* Clase [XmlNamedNodeMap](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)