---
title: PrependChild()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega el nodo especificado al principio de la lista de nodos hijos de este nodo.
type: docs
weight: 261
url: /es/system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild(SharedPtr\<XmlNode\>) método


Agrega el nodo especificado al principio de la lista de nodos hijos de este nodo.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | El [XmlNode](../../xmlnode/) a agregar. Si es un [XmlDocumentFragment](../../xmldocumentfragment/), todo el contenido del fragmento de documento se mueve a la lista de hijos de este nodo. |

### Valor devuelto

El [XmlNode](../../xmlnode/) agregado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNode](../../xmlnode/)
* Clase [XmlAttribute](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)