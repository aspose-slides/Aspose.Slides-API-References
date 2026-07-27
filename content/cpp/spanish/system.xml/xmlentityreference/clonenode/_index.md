---
title: CloneNode()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un duplicado de este nodo.
type: docs
weight: 92
url: /es/system.xml/xmlentityreference/clonenode/
---
## XmlEntityReference::CloneNode(bool) method

Crea un duplicado de este nodo.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntityReference::CloneNode(bool deep) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| deep | **bool** | **true** para clonar recursivamente el subárbol bajo el nodo especificado; **false** para clonar solo el nodo mismo. Para nodos [XmlEntityReference](../), este método siempre devuelve un nodo de referencia de entidad sin hijos. El texto de reemplazo se establece cuando el nodo se inserta en un padre. |

### Valor de retorno

El nodo clonado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNode](../../xmlnode/)
* Clase [XmlEntityReference](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)