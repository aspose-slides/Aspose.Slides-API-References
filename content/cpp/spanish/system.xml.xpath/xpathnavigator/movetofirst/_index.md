---
title: MoveToFirst()
second_title: Referencia de API de Aspose.Slides para C++
description: Mueve el XPathNavigator al primer nodo hermano del nodo actual.
type: docs
weight: 612
url: /es/system.xml.xpath/xpathnavigator/movetofirst/
---
## XPathNavigator::MoveToFirst() método

Mueve el [XPathNavigator](../) al primer nodo hermano del nodo actual.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirst()
```

### Valor devuelto

**true** si el [XPathNavigator](../) se mueve con éxito al primer nodo hermano del nodo actual; **false** si no hay un primer hermano, o si el [XPathNavigator](../) está actualmente posicionado en un nodo de atributo. Si el [XPathNavigator](../) ya está posicionado en el primer hermano, [XPathNavigator](../) devolverá **true** y no moverá su posición. Si [XPathNavigator::MoveToFirst](./) devuelve **false** porque no hay un primer hermano, o si [XPathNavigator](../) está actualmente posicionado en un atributo, la posición del [XPathNavigator](../) no cambia.

## Ver también

* Clase [XPathNavigator](../)
* Espacio de nombres [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)