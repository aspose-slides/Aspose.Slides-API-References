---
title: PrependChild()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve un objeto XmlWriter utilizado para crear un nuevo nodo hijo al principio de la lista de nodos hijos del nodo actual.
type: docs
weight: 872
url: /es/system.xml.xpath/xpathnavigator/prependchild/
---
## XPathNavigator::PrependChild() método


Devuelve un objeto [XmlWriter](../../../system.xml/xmlwriter/) utilizado para crear un nuevo nodo hijo al principio de la lista de nodos hijos del nodo actual.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::PrependChild()
```


### Valor devuelto

Un objeto [XmlWriter](../../../system.xml/xmlwriter/) utilizado para crear un nuevo nodo hijo al principio de la lista de nodos hijos del nodo actual.

## XPathNavigator::PrependChild(String) método


Crea un nuevo nodo hijo al principio de la lista de nodos hijos del nodo actual usando la cadena XML especificada.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(String newChild)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | La cadena de datos XML para el nuevo nodo hijo. |

## XPathNavigator::PrependChild(SharedPtr\<XmlReader\>) método


Crea un nuevo nodo hijo al principio de la lista de nodos hijos del nodo actual usando los contenidos XML del objeto [XmlReader](../../../system.xml/xmlreader/) especificado.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XmlReader> newChild)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Un objeto [XmlReader](../../../system.xml/xmlreader/) posicionado en los datos XML para el nuevo nodo hijo. |

## XPathNavigator::PrependChild(SharedPtr\<XPathNavigator\>) método


Crea un nuevo nodo hijo al principio de la lista de nodos hijos del nodo actual usando los nodos del objeto [XPathNavigator](../) especificado.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XPathNavigator> newChild)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Un objeto [XPathNavigator](../) posicionado en el nodo que se agregará como el nuevo nodo hijo. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)