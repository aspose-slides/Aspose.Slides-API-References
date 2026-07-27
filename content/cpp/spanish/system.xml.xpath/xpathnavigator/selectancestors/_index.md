---
title: SelectAncestors()
second_title: Referencia de API de Aspose.Slides para C++
description: Selecciona todos los nodos ancestros del nodo actual que tengan un XPathNodeType coincidente.
type: docs
weight: 846
url: /es/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(XPathNodeType, bool) método

Selecciona todos los nodos ancestros del nodo actual que tengan un XPathNodeType coincidente.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | El XPathNodeType de los nodos ancestros. |
| matchSelf | **bool** | Para incluir el nodo de contexto en la selección, **true**; de lo contrario, **false**. |

### Valor devuelto

Un [XPathNodeIterator](../../xpathnodeiterator/) que contiene los nodos seleccionados. Los nodos devueltos están en orden inverso del documento.

## XPathNavigator::SelectAncestors(String, String, bool) método

Selecciona todos los nodos ancestros del nodo actual que tengan el nombre local y el URI de espacio de nombres especificados.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre local de los nodos ancestros. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres de los nodos ancestros. |
| matchSelf | **bool** | Para incluir el nodo de contexto en la selección, **true**; de lo contrario, **false**. |

### Valor devuelto

Un [XPathNodeIterator](../../xpathnodeiterator/) que contiene los nodos seleccionados. Los nodos devueltos están en orden inverso del documento.

## Ver también

* Enumeración [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XPathNodeIterator](../../xpathnodeiterator/)
* Clase [XPathNavigator](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)