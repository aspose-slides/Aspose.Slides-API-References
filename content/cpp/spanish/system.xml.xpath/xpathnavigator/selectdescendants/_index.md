---
title: SelectDescendants()
second_title: Referencia de la API de Aspose.Slides para C++
description: Selecciona todos los nodos descendientes del nodo actual que tengan un XPathNodeType coincidente.
type: docs
weight: 859
url: /es/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(XPathNodeType, bool) método

Selecciona todos los nodos descendientes del nodo actual que tengan un XPathNodeType coincidente.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | El XPathNodeType de los nodos descendientes. |
| matchSelf | **bool** | **true** para incluir el nodo de contexto en la selección; de lo contrario, **false**. |

### Valor devuelto

Un [XPathNodeIterator](../../xpathnodeiterator/) que contiene los nodos seleccionados.

## XPathNavigator::SelectDescendants(String, String, bool) método

Selecciona todos los nodos descendientes del nodo actual con el nombre local y el URI del espacio de nombres especificados.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre local de los nodos descendientes. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres de los nodos descendientes. |
| matchSelf | **bool** | **true** para incluir el nodo de contexto en la selección; de lo contrario, **false**. |

### Valor devuelto

Un [XPathNodeIterator](../../xpathnodeiterator/) que contiene los nodos seleccionados.

## Ver también

* Enumeración [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XPathNodeIterator](../../xpathnodeiterator/)
* Clase [XPathNavigator](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)