---
title: get_NewParent()
second_title: Referencia de API de Aspose.Slides para C++
description: "Devuelve el valor de XmlNode::get_ParentNode después de que la operación se complete."
type: docs
weight: 40
url: /es/system.xml/xmlnodechangedeventargs/get_newparent/
---
## XmlNodeChangedEventArgs::get_NewParent() method


Devuelve el valor de [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) después de que la operación se complete.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_NewParent()
```


### Valor devuelto

El valor del **ParentNode** después de que la operación se complete. Este método devuelve **nullptr** si el nodo está siendo eliminado. Para nodos de atributo, este método devuelve el valor [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNode](../../xmlnode/)
* Clase [XmlNodeChangedEventArgs](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)