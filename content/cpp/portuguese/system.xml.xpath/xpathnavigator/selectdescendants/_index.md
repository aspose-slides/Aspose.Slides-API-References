---
title: SelectDescendants()
second_title: Referência da API Aspose.Slides para C++
description: Seleciona todos os nós descendentes do nó atual que possuem um XPathNodeType correspondente.
type: docs
weight: 859
url: /pt/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(XPathNodeType, bool) método


Seleciona todos os nós descendentes do nó atual que possuam um XPathNodeType correspondente.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | O XPathNodeType dos nós descendentes. |
| matchSelf | **bool** | **true** para incluir o nó de contexto na seleção; caso contrário, **false**. |

### Valor de retorno

Um [XPathNodeIterator](../../xpathnodeiterator/) que contém os nós selecionados.

## XPathNavigator::SelectDescendants(String, String, bool) método


Seleciona todos os nós descendentes do nó atual com o nome local e o URI do namespace especificados.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome local dos nós descendentes. |
| namespaceURI | [String](../../../system/string/) | O URI do namespace dos nós descendentes. |
| matchSelf | **bool** | **true** para incluir o nó de contexto na seleção; caso contrário, **false**. |

### Valor de retorno

Um [XPathNodeIterator](../../xpathnodeiterator/) que contém os nós selecionados.

## Veja também

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)