---
title: Item()
second_title: Referencia de la API de Aspose.Slides para C++
description: Recupera el nodo en el índice especificado en el XmlNamedNodeMap.
type: docs
weight: 53
url: /es/system.xml/xmlnamednodemap/item/
---
## XmlNamedNodeMap::Item(int32_t) método

Recupera el nodo en el índice especificado en el [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | La posición del índice del nodo que se recupera del [XmlNamedNodeMap](../). El índice comienza en cero; por lo tanto, el índice del primer nodo es 0 y el índice del último nodo es [XmlNamedNodeMap::get_Count](../get_count/) - 1. |

### Valor devuelto

El [XmlNode](../../xmlnode/) en el índice especificado. Si **index** es menor que 0 o mayor o igual que el valor [XmlNamedNodeMap::get_Count](../get_count/), se devuelve **nullptr**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNode](../../xmlnode/)
* Clase [XmlNamedNodeMap](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)