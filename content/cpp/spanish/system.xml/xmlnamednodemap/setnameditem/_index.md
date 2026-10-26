---
title: SetNamedItem()
second_title: Referencia de API de Aspose.Slides para C++
description: "Añade un XmlNode usando su valor XmlNode::get_Name."
type: docs
weight: 27
url: /es/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem(SharedPtr\<XmlNode\>) método

Añade un [XmlNode](../../xmlnode/) usando su valor [XmlNode::get_Name](../../xmlnode/get_name/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```

### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Un [XmlNode](../../xmlnode/) para almacenar en el [XmlNamedNodeMap](../). Si ya existe un nodo con ese nombre en el mapa, se reemplaza por el nuevo. |

### Return Value

Si el **node** reemplaza un nodo existente con el mismo nombre, se devuelve el nodo antiguo; de lo contrario, se devuelve **nullptr**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNode](../../xmlnode/)
* Clase [XmlNamedNodeMap](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)