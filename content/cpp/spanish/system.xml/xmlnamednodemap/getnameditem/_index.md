---
title: GetNamedItem()
second_title: Referencia de API de Aspose.Slides para C++
description: Recupera un XmlNode especificado por nombre.
type: docs
weight: 14
url: /es/system.xml/xmlnamednodemap/getnameditem/
---
## XmlNamedNodeMap::GetNamedItem(String) method

Recupera un [XmlNode](../../xmlnode/) especificado por nombre.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String name)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre calificado del nodo a recuperar. Se compara con el valor [XmlNode::get_Name](../../xmlnode/get_name/) del nodo coincidente. |

### Valor devuelto

Un [XmlNode](../../xmlnode/) con el nombre especificado o **nullptr** si no se encuentra un nodo coincidente.

## XmlNamedNodeMap::GetNamedItem(String, String) method

Recupera un nodo con los valores [XmlNode::get_LocalName](../../xmlnode/get_localname/) y [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) coincidentes.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String localName, String namespaceURI)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | [String](../../../system/string/) | El nombre local del nodo a recuperar. |
| namespaceURI | [String](../../../system/string/) | El Identificador Uniforme de Recursos (URI) del espacio de nombres del nodo a recuperar. |

### Valor devuelto

Un [XmlNode](../../xmlnode/) con el nombre local y el URI del espacio de nombres coincidentes o **nullptr** si no se encuentra un nodo coincidente.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNode](../../xmlnode/)
* Clase [String](../../../system/string/)
* Clase [XmlNamedNodeMap](../)
* Espacio de nombres [System::Xml](../../)
* Library [Aspose.Slides](../../../)