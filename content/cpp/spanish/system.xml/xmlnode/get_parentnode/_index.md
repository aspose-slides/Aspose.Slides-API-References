---
title: get_ParentNode()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve el padre de este nodo (para nodos que pueden tener padres).
type: docs
weight: 53
url: /es/system.xml/xmlnode/get_parentnode/
---
## XmlNode::get_ParentNode() método

Devuelve el padre de este nodo (para nodos que pueden tener padres).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::get_ParentNode() final
```

### Valor de retorno

El [XmlNode](../) que es el padre del nodo actual.

## Observaciones

Si un nodo acaba de ser creado y aún no se ha añadido al árbol, o si se ha eliminado del árbol, el padre es **nullptr**. Para todos los demás nodos, el valor devuelto depende del [XmlNode::get_NodeType](../get_nodetype/) del nodo. La siguiente tabla describe los posibles valores de retorno para el método **get_NodeType**.

| NodeType | Valor de retorno de ParentNode |
| --- | --- |
| [Attribute](../../../system/attribute/), Document, DocumentFragment, Entity, Notation | Devuelve `nullptr`; estos nodos no tienen padres. |
| CDATA | Devuelve el elemento o la referencia de entidad que contiene la sección CDATA. |
| Comment | Devuelve el elemento, la referencia de entidad, el tipo de documento o el documento que contiene el comentario. |
| DocumentType | Devuelve el nodo de documento. |
| Element | Devuelve el nodo padre del elemento. Si el elemento es el nodo raíz del árbol, el padre es el nodo de documento. |
| EntityReference | Devuelve el elemento, el atributo o la referencia de entidad que contiene la referencia de entidad. |
| ProcessingInstruction | Devuelve el documento, el elemento, el tipo de documento o la referencia de entidad que contiene la instrucción de procesamiento. |
| [Text](../../../system.text/)| Devuelve el elemento padre, el atributo o la referencia de entidad que contiene el nodo de texto. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNode](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)