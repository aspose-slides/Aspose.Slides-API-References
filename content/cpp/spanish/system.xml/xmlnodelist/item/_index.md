---
title: Item()
second_title: Referencia de la API de Aspose.Slides para C++
description: Recupera un nodo en el índice especificado.
type: docs
weight: 14
url: /es/system.xml/xmlnodelist/item/
---
## XmlNodeList::Item(int32_t) método


Recupera un nodo en el índice especificado.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::Item(int32_t index)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero de la lista de nodos. |

### Valor devuelto

El [XmlNode](../../xmlnode/) con el índice especificado en la colección. Si **index** es mayor o igual que la cantidad de nodos en la lista, esto devuelve **nullptr**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNode](../../xmlnode/)
* Clase [XmlNodeList](../)
* Espacio de nombres [System::Xml](../../)
* Library [Aspose.Slides](../../../)