---
title: CloneNode()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea una copia de este nodo.
type: docs
weight: 118
url: /es/system.xml/xmldocumenttype/clonenode/
---
## XmlDocumentType::CloneNode(bool) método


Crea una copia de este nodo.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDocumentType::CloneNode(bool deep) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| deep | **bool** | **true** para clonar recursivamente el subárbol bajo el nodo especificado; **false** para clonar solo el nodo en sí. Para los nodos de tipo de documento, el nodo clonado siempre incluye el subárbol, sin importar la configuración del parámetro. |

### Valor devuelto

El nodo clonado.

## Ver también

* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNode](../../xmlnode/)
* Clase [XmlDocumentType](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)