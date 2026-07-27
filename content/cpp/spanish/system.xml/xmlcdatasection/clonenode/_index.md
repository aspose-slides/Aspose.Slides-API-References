---
title: CloneNode()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un duplicado de este nodo.
type: docs
weight: 53
url: /es/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode(bool) método

Crea una duplicado de este nodo.

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| deep | **bool** | **true** para clonar recursivamente el subárbol bajo el nodo especificado; **false** para clonar solo el propio nodo. Debido a que los nodos CDATA no tienen hijos, independientemente de la configuración del parámetro, el nodo clonado siempre incluirá el contenido de datos. |

### Valor devuelto

El nodo clonado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNode](../../xmlnode/)
* Clase [XmlCDataSection](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)