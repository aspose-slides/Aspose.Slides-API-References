---
title: SelectChildren()
second_title: Aspose.Slides para C++ Referência da API
description: Seleciona todos os nós filhos do nó atual que possuem o XPathNodeType correspondente.
type: docs
weight: 833
url: /pt/system.xml.xpath/xpathnavigator/selectchildren/
---
## XPathNavigator::SelectChildren(XPathNodeType) method


Seleciona todos os nós filhos do nó atual que possuem o XPathNodeType correspondente.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(XPathNodeType type)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | O XPathNodeType dos nós filhos. |

### Valor de Retorno

Um [XPathNodeIterator](../../xpathnodeiterator/) que contém os nós selecionados.

## XPathNavigator::SelectChildren(String, String) method


Seleciona todos os nós filhos do nó atual que possuem o nome local e o URI do namespace especificados.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(String name, String namespaceURI)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome local dos nós filhos. |
| namespaceURI | [String](../../../system/string/) | O URI do namespace dos nós filhos. |

### Valor de Retorno

Um [XPathNodeIterator](../../xpathnodeiterator/) que contém os nós selecionados.

## Veja Também

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)