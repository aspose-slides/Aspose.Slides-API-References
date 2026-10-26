---
title: get_Current()
second_title: Referência da API Aspose.Slides para C++
description: Quando sobrescrito em uma classe derivada, obtém o objeto XPathNavigator para este XPathNodeIterator, posicionado no nó de contexto atual.
type: docs
weight: 1
url: /pt/system.xml.xpath/xpathnodeiterator/get_current/
---
## XPathNodeIterator::get_Current() método


Quando sobrescrito em uma classe derivada, obtém o objeto [XPathNavigator](../../xpathnavigator/) para este [XPathNodeIterator](../), posicionado no nó de contexto atual.

```cpp
virtual const SharedPtr<XPathNavigator> & System::Xml::XPath::XPathNodeIterator::get_Current()=0
```


### Valor de Retorno

Um objeto [XPathNavigator](../../xpathnavigator/) posicionado no nó de contexto a partir do qual o conjunto de nós foi selecionado. O [XPathNodeIterator::MoveNext](../movenext/) método deve ser chamado para mover o [XPathNodeIterator](../) para o primeiro nó no conjunto selecionado.

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XPathNavigator](../../xpathnavigator/)
* Classe [XPathNodeIterator](../)
* Namespace [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)