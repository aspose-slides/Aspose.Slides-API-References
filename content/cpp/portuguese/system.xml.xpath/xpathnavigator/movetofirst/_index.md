---
title: MoveToFirst()
second_title: Referência da API Aspose.Slides para C++
description: Move o XPathNavigator para o primeiro nó irmão do nó atual.
type: docs
weight: 612
url: /pt/system.xml.xpath/xpathnavigator/movetofirst/
---
## XPathNavigator::MoveToFirst() método

Move o [XPathNavigator](../) para o primeiro nó irmão do nó atual.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirst()
```

### Valor de Retorno

**true** se o [XPathNavigator](../) for bem-sucedido ao mover para o primeiro nó irmão do nó atual; **false** se não houver primeiro nó irmão, ou se o [XPathNavigator](../) estiver posicionado atualmente em um nó de atributo. Se o [XPathNavigator](../) já estiver posicionado no primeiro nó irmão, [XPathNavigator](../) retornará **true** e não moverá sua posição. Se [XPathNavigator::MoveToFirst](./) retornar **false** porque não há primeiro nó irmão, ou se [XPathNavigator](../) estiver posicionado atualmente em um atributo, a posição do [XPathNavigator](../) permanecerá inalterada.

## Veja Também

* Classe [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)