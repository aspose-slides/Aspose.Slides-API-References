---
title: InsertAfter()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve un objeto XmlWriter utilizado para crear un nuevo nodo hermano después del nodo seleccionado actualmente.
type: docs
weight: 898
url: /es/system.xml.xpath/xpathnavigator/insertafter/
---
## XPathNavigator::InsertAfter() método

Devuelve un objeto [XmlWriter](../../../system.xml/xmlwriter/) utilizado para crear un nuevo nodo hermano después del nodo seleccionado actualmente.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertAfter()
```

### Valor devuelto

Un objeto [XmlWriter](../../../system.xml/xmlwriter/) utilizado para crear un nuevo nodo hermano después del nodo seleccionado actualmente.

## XPathNavigator::InsertAfter(String) método

Crea un nuevo nodo hermano después del nodo seleccionado actualmente usando la cadena XML especificada.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(String newSibling)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | La cadena de datos XML para el nuevo nodo hermano. |

## XPathNavigator::InsertAfter(SharedPtr\<XmlReader\>) método

Crea un nuevo nodo hermano después del nodo seleccionado actualmente usando el contenido XML del objeto [XmlReader](../../../system.xml/xmlreader/) especificado.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XmlReader> newSibling)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Un objeto [XmlReader](../../../system.xml/xmlreader/) posicionado en los datos XML para el nuevo nodo hermano. |

## XPathNavigator::InsertAfter(SharedPtr\<XPathNavigator\>) método

Crea un nuevo nodo hermano después del nodo seleccionado actualmente usando los nodos del objeto [XPathNavigator](../) especificado.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XPathNavigator> newSibling)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Un objeto [XPathNavigator](../) posicionado en el nodo que se añadirá como nuevo nodo hermano. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlWriter](../../../system.xml/xmlwriter/)
* Clase [XPathNavigator](../)
* Clase [String](../../../system/string/)
* Clase [XmlReader](../../../system.xml/xmlreader/)
* Espacio de nombres [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)