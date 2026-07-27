---
title: AppendChild()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve un objeto XmlWriter utilizado para crear uno o más nodos hijos al final de la lista de nodos hijos del nodo actual.
type: docs
weight: 885
url: /es/system.xml.xpath/xpathnavigator/appendchild/
---
## XPathNavigator::AppendChild() method

Devuelve un objeto [XmlWriter](../../../system.xml/xmlwriter/) utilizado para crear uno o más nodos hijos al final de la lista de nodos hijos del nodo actual.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::AppendChild()
```

### Valor devuelto

Un objeto [XmlWriter](../../../system.xml/xmlwriter/) utilizado para crear nuevos nodos hijos al final de la lista de nodos hijos del nodo actual.

## XPathNavigator::AppendChild(String) method

Crea un nuevo nodo hijo al final de la lista de nodos hijos del nodo actual usando la cadena de datos XML especificada.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(String newChild)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | La cadena de datos XML para el nuevo nodo hijo. |

## XPathNavigator::AppendChild(SharedPtr\<XmlReader\>) method

Crea un nuevo nodo hijo al final de la lista de nodos hijos del nodo actual usando el contenido XML del objeto [XmlReader](../../../system.xml/xmlreader/) especificado.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XmlReader> newChild)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Un objeto [XmlReader](../../../system.xml/xmlreader/) posicionado en los datos XML para el nuevo nodo hijo. |

## XPathNavigator::AppendChild(SharedPtr\<XPathNavigator\>) method

Crea un nuevo nodo hijo al final de la lista de nodos hijos del nodo actual usando los nodos en el [XPathNavigator](../) especificado.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XPathNavigator> newChild)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Un objeto [XPathNavigator](../) posicionado en el nodo que se añadirá como nuevo nodo hijo. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlWriter](../../../system.xml/xmlwriter/)
* Clase [XPathNavigator](../)
* Clase [String](../../../system/string/)
* Clase [XmlReader](../../../system.xml/xmlreader/)
* Espacio de nombres [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)