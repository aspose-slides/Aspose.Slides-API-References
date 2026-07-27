---
title: CloneNode()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una copia duplicada de este nodo.
type: docs
weight: 79
url: /es/system.xml/xmlwhitespace/clonenode/
---
## XmlWhitespace::CloneNode(bool) método


Crea una copia de este nodo.

```cpp
SharedPtr<XmlNode> System::Xml::XmlWhitespace::CloneNode(bool deep) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| deep | **bool** | **true** para clonar recursivamente el subárbol bajo el nodo especificado; **false** para clonar solo el nodo en sí. Para los nodos de espacio en blanco, el nodo clonado siempre incluye el valor de datos, sin importar la configuración del parámetro. |

### Valor de retorno

El nodo clonado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNode](../../xmlnode/)
* Clase [XmlWhitespace](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)