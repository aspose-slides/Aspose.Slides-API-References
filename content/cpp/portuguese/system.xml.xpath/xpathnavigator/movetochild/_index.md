---
title: MoveToChild()
second_title: Referência da API Aspose.Slides for C++
description: Move o XPathNavigator para o nó filho com o nome local e o URI do namespace especificados.
type: docs
weight: 690
url: /pt/system.xml.xpath/xpathnavigator/movetochild/
---
## XPathNavigator::MoveToChild(String, String) method


Move o [XPathNavigator](../) para o nó filho com o nome local e o URI do namespace especificados.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(String localName, String namespaceURI)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | O nome local do nó filho para o qual mover. |
| namespaceURI | [String](../../../system/string/) | O URI do namespace do nó filho para o qual mover. |

### Valor de Retorno

**true** se o [XPathNavigator](../) for bem-sucedido ao mover para o nó filho; caso contrário, **false**. Se **false**, a posição do [XPathNavigator](../) permanece inalterada.

## XPathNavigator::MoveToChild(XPathNodeType) method


Move o [XPathNavigator](../) para o nó filho do XPathNodeType especificado.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(XPathNodeType type)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | O XPathNodeType do nó filho para o qual mover. |

### Valor de Retorno

**true** se o [XPathNavigator](../) for bem-sucedido ao mover para o nó filho; caso contrário, **false**. Se **false**, a posição do [XPathNavigator](../) permanece inalterada.

## Veja Também

* Enum [XPathNodeType](../../xpathnodetype/)
* Classe [String](../../../system/string/)
* Classe [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)