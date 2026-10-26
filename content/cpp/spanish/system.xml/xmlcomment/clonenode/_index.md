---
title: CloneNode()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea una copia de este nodo.
type: docs
weight: 40
url: /es/system.xml/xmlcomment/clonenode/
---
## XmlComment::CloneNode(bool) método


Crea una copia de este nodo.

```cpp
SharedPtr<XmlNode> System::Xml::XmlComment::CloneNode(bool deep) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| deep | **bool** | **true** para clonar recursivamente el subárbol bajo el nodo especificado; **false** para clonar solo el nodo en sí. Como los nodos de comentario no tienen hijos, el nodo clonado siempre incluye el contenido de texto, independientemente de la configuración del parámetro. |

### Valor de retorno

El nodo clonado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlComment](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)