---
title: CloneNode()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una copia de este nodo.
type: docs
weight: 79
url: /es/system.xml/xmlsignificantwhitespace/clonenode/
---
## XmlSignificantWhitespace::CloneNode(bool) método


Crea una copia de este nodo.

```cpp
SharedPtr<XmlNode> System::Xml::XmlSignificantWhitespace::CloneNode(bool deep) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| deep | **bool** | **true** para clonar recursivamente el subárbol bajo el nodo especificado; **false** para clonar solo el nodo mismo. Para los nodos de espacio en blanco significativo, el nodo clonado siempre incluye el valor de datos, sin importar la configuración del parámetro. |

### Valor devuelto

El nodo clonado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNode](../../xmlnode/)
* Clase [XmlSignificantWhitespace](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)