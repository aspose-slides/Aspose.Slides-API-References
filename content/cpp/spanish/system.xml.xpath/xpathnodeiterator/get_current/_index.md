---
title: get_Current()
second_title: Referencia de la API de Aspose.Slides para C++
description: Cuando se sobrescribe en una clase derivada, obtiene el objeto XPathNavigator para este XPathNodeIterator, posicionado en el nodo de contexto actual.
type: docs
weight: 1
url: /es/system.xml.xpath/xpathnodeiterator/get_current/
---
## XPathNodeIterator::get_Current() método

Cuando se sobrescribe en una clase derivada, obtiene el objeto [XPathNavigator](../../xpathnavigator/) para este [XPathNodeIterator](../), posicionado en el nodo de contexto actual.

```cpp
virtual const SharedPtr<XPathNavigator> & System::Xml::XPath::XPathNodeIterator::get_Current()=0
```

### Valor de retorno

Un objeto [XPathNavigator](../../xpathnavigator/) posicionado en el nodo de contexto desde el cual se seleccionó el conjunto de nodos. El [XPathNodeIterator::MoveNext](../movenext/) método debe llamarse para mover el [XPathNodeIterator](../) al primer nodo del conjunto seleccionado.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XPathNavigator](../../xpathnavigator/)
* Clase [XPathNodeIterator](../)
* Espacio de nombres [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)