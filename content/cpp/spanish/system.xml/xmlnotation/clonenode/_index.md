---
title: CloneNode()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una copia de este nodo. Los nodos de notación no pueden ser clonados. Llamar a este método en un objeto XmlNotation lanza una excepción.
type: docs
weight: 118
url: /es/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode(bool) método


Crea una copia de este nodo. Los nodos de notación no pueden ser clonados. Llamar a este método en un objeto [XmlNotation](../) lanza una excepción.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| deep | **bool** | **true** para clonar recursivamente el subárbol bajo el nodo especificado; **false** para clonar solo el nodo en sí. |

### Valor devuelto

Una copia [XmlNode](../../xmlnode/) del nodo desde el cual se llama al método.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNode](../../xmlnode/)
* Clase [XmlNotation](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)