---
title: SelectChildren()
second_title: Referencia de API de Aspose.Slides para C++
description: Selecciona todos los nodos hijo del nodo actual que tengan el XPathNodeType coincidente.
type: docs
weight: 833
url: /es/system.xml.xpath/xpathnavigator/selectchildren/
---
## XPathNavigator::SelectChildren(XPathNodeType) método

Selecciona todos los nodos hijo del nodo actual que tengan el XPathNodeType coincidente.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(XPathNodeType type)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | El XPathNodeType de los nodos hijo. |

### Valor de retorno

Un [XPathNodeIterator](../../xpathnodeiterator/) que contiene los nodos seleccionados.

## XPathNavigator::SelectChildren(String, String) método

Selecciona todos los nodos hijo del nodo actual que tengan el nombre local y el URI de espacio de nombres especificados.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(String name, String namespaceURI)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre local de los nodos hijo. |
| namespaceURI | [String](../../../system/string/) | El URI de espacio de nombres de los nodos hijo. |

### Valor de retorno

Un [XPathNodeIterator](../../xpathnodeiterator/) que contiene los nodos seleccionados.

## Ver también

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)