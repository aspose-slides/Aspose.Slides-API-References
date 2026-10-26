---
title: MoveToNext()
second_title: Referencia de API de Aspose.Slides para C++
description: Cuando se sobrescribe en una clase derivada, mueve el XPathNavigator al nodo hermano siguiente del nodo actual.
type: docs
weight: 586
url: /es/system.xml.xpath/xpathnavigator/movetonext/
---
## XPathNavigator::MoveToNext() método

Cuando se sobrescribe en una clase derivada, mueve el [XPathNavigator](../) al nodo hermano siguiente del nodo actual.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext()=0
```

### Valor devuelto

**true** si el [XPathNavigator](../) se mueve correctamente al nodo hermano siguiente; de lo contrario **false** si no hay más hermanos o si el [XPathNavigator](../) está posicionado actualmente en un nodo de atributo. Si **false**, la posición del [XPathNavigator](../) no cambia.

## XPathNavigator::MoveToNext(String, String) método

Mueve el [XPathNavigator](../) al nodo hermano siguiente con el nombre local y el URI de espacio de nombres especificados.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(String localName, String namespaceURI)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | [String](../../../system/string/) | El nombre local del nodo hermano siguiente al que mover. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del nodo hermano siguiente al que mover. |

### Valor devuelto

**true** si el [XPathNavigator](../) se mueve correctamente al nodo hermano siguiente; **false** si no hay más hermanos, o si el [XPathNavigator](../) está posicionado actualmente en un nodo de atributo. Si **false**, la posición del [XPathNavigator](../) no cambia.

## XPathNavigator::MoveToNext(XPathNodeType) método

Mueve el [XPathNavigator](../) al nodo hermano siguiente del nodo actual que coincide con el XPathNodeType especificado.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(XPathNodeType type)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | El XPathNodeType del nodo hermano al que mover. |

### Valor devuelto

**true** si el [XPathNavigator](../) se mueve correctamente al nodo hermano siguiente; de lo contrario, **false** si no hay más hermanos o si el [XPathNavigator](../) está posicionado actualmente en un nodo de atributo. Si **false**, la posición del [XPathNavigator](../) no cambia.

## Ver también

* Enum [XPathNodeType](../../xpathnodetype/)
* Clase [XPathNavigator](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)