---
title: SetNamedItem()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Agrega un XmlNode usando su resultado XmlNode::get_Name."
type: docs
weight: 14
url: /es/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem(SharedPtr\<XmlNode\>) método


Agrega un [XmlNode](../../xmlnode/) usando su resultado [XmlNode::get_Name](../../xmlnode/get_name/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Un nodo de atributo para almacenar en esta colección. El node será accesible posteriormente usando el nombre del node. Si ya existe un node con ese nombre en la colección, será reemplazado por el nuevo; de lo contrario, el node se añadirá al final de la colección. |

### Valor devuelto

Si el **node** reemplaza un node existente con el mismo nombre, se devuelve el node antiguo; de lo contrario, se devuelve el node añadido.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNode](../../xmlnode/)
* Clase [XmlAttributeCollection](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)