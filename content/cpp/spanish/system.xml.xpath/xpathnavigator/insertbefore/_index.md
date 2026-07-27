---
title: InsertBefore()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve un objeto XmlWriter utilizado para crear un nodo hermano nuevo antes del nodo actualmente seleccionado.
type: docs
weight: 911
url: /es/system.xml.xpath/xpathnavigator/insertbefore/
---
## XPathNavigator::InsertBefore() método

Devuelve un objeto [XmlWriter](../../../system.xml/xmlwriter/) utilizado para crear un nodo hermano nuevo antes del nodo actualmente seleccionado.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertBefore()
```

### Valor de retorno

Un objeto [XmlWriter](../../../system.xml/xmlwriter/) utilizado para crear un nodo hermano nuevo antes del nodo actualmente seleccionado.

## XPathNavigator::InsertBefore(String) método

Crea un nodo hermano nuevo antes del nodo actualmente seleccionado usando la cadena XML especificada.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(String newSibling)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | La cadena de datos XML para el nodo hermano nuevo. |

## XPathNavigator::InsertBefore(SharedPtr\<XmlReader\>) método

Crea un nodo hermano nuevo antes del nodo actualmente seleccionado usando el contenido XML del objeto [XmlReader](../../../system.xml/xmlreader/) especificado.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XmlReader> newSibling)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Un objeto [XmlReader](../../../system.xml/xmlreader/) posicionado en los datos XML para el nodo hermano nuevo. |

## XPathNavigator::InsertBefore(SharedPtr\<XPathNavigator\>) método

Crea un nodo hermano nuevo antes del nodo actualmente seleccionado usando los nodos en el [XPathNavigator](../) especificado.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XPathNavigator> newSibling)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Un objeto [XPathNavigator](../) posicionado en el nodo que se añadirá como nodo hermano nuevo. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlWriter](../../../system.xml/xmlwriter/)
* Clase [XPathNavigator](../)
* Clase [String](../../../system/string/)
* Clase [XmlReader](../../../system.xml/xmlreader/)
* Espacio de nombres [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)