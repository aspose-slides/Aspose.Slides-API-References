---
title: MoveToFirstNamespace()
second_title: Referencia de API de Aspose.Slides para C++
description: Cuando se sobrescribe en una clase derivada, mueve el XPathNavigator al primer nodo de espacio de nombres que coincide con el XPathNamespaceScope especificado.
type: docs
weight: 560
url: /es/system.xml.xpath/xpathnavigator/movetofirstnamespace/
---
## XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope) método

Cuando se sobrescribe en una clase derivada, mueve el [XPathNavigator](../) al primer nodo de espacio de nombres que coincide con el XPathNamespaceScope especificado.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope namespaceScope)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | Un valor XPathNamespaceScope que describe el ámbito del espacio de nombres. |

### Valor de retorno

**true** si el [XPathNavigator](../) se mueve con éxito al primer nodo de espacio de nombres; de lo contrario, **false**. Si **false**, la posición del [XPathNavigator](../) no cambia.

## XPathNavigator::MoveToFirstNamespace() método

Mueve el [XPathNavigator](../) al primer nodo de espacio de nombres del nodo actual.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace()
```

### Valor de retorno

**true** si el [XPathNavigator](../) se mueve con éxito al primer nodo de espacio de nombres; de lo contrario, **false**. Si **false**, la posición del [XPathNavigator](../) no cambia.

## Ver también

* Enumeración [XPathNamespaceScope](../../xpathnamespacescope/)
* Clase [XPathNavigator](../)
* Espacio de nombres [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)