---
title: CloneNode()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea una copia de este nodo. Los nodos de entidad no pueden ser clonados. Llamar a este método en un objeto XmlEntity lanza una excepción.
type: docs
weight: 170
url: /es/system.xml/xmlentity/clonenode/
---
## XmlEntity::CloneNode(bool) método

Crea una copia de este nodo. Los nodos de entidad no pueden ser clonados. Llamar a este método en un [XmlEntity](../) objeto lanza una excepción.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntity::CloneNode(bool deep) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| deep | **bool** | **true** para clonar recursivamente el subárbol bajo el nodo especificado; **false** para clonar solo el nodo mismo. |

### Valor devuelto

Una copia del [XmlNode](../../xmlnode/) desde el cual se llama el método.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNode](../../xmlnode/)
* Clase [XmlEntity](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)