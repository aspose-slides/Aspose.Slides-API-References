---
title: get_OldParent()
second_title: Referencia de API de Aspose.Slides para C++
description: "Devuelve el valor de XmlNode::get_ParentNode antes de que comenzara la operación."
type: docs
weight: 27
url: /es/system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent() método

Devuelve el valor de [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) antes de que comenzara la operación.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```

### Valor de retorno

El valor de **ParentNode** antes de que comenzara la operación. Este método devuelve **nullptr** si el nodo no tenía un padre. Para los nodos de atributo, este método devuelve el valor [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNode](../../xmlnode/)
* Clase [XmlNodeChangedEventArgs](../)
* Espacio de nombres [System::Xml](../../)
* Library [Aspose.Slides](../../../)