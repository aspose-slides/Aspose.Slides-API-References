---
title: CloneNode()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una copia duplicada de este nodo.
type: docs
weight: 157
url: /es/system.xml/xmldeclaration/clonenode/
---
## XmlDeclaration::CloneNode(bool) método

Crea una copia duplicada de este nodo.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDeclaration::CloneNode(bool deep) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| deep | **bool** | **true** para clonar recursivamente el subárbol bajo el nodo especificado; **false** para clonar solo el nodo mismo. Dado que los nodos [XmlDeclaration](../) no tienen hijos, el nodo clonado siempre incluye el valor de datos, independientemente de la configuración del parámetro. |

### Valor devuelto

El nodo clonado.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNode](../../xmlnode/)
* Clase [XmlDeclaration](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)