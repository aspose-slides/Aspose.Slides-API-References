---
title: MoveTo()
second_title: Referência da API Aspose.Slides para C++
description: Quando sobrescrito em uma classe derivada, move o XPathNavigator para a mesma posição do XPathNavigator especificado.
type: docs
weight: 664
url: /pt/system.xml.xpath/xpathnavigator/moveto/
---
## XPathNavigator::MoveTo(SharedPtr\<XPathNavigator\>) método

Quando sobrescrito em uma classe derivada, move o [XPathNavigator](../) para a mesma posição do [XPathNavigator](../) especificado.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveTo(SharedPtr<XPathNavigator> other)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | O [XPathNavigator](../) posicionado no nó para o qual você deseja mover. |

### Valor de Retorno

**true** se o [XPathNavigator](../) for bem-sucedido ao mover para a mesma posição do [XPathNavigator](../) especificado; caso contrário, **false**. Se **false**, a posição do [XPathNavigator](../) permanece inalterada.

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)