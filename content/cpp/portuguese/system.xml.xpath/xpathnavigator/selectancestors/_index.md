---
title: SelectAncestors()
second_title: Aspose.Slides para C++ Referência da API
description: Seleciona todos os nós ancestrais do nó atual que possuem um XPathNodeType correspondente.
type: docs
weight: 846
url: /pt/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(XPathNodeType, bool) método

Seleciona todos os nós ancestrais do nó atual que possuam um XPathNodeType correspondente.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | O XPathNodeType dos nós ancestrais. |
| matchSelf | **bool** | Para incluir o nó de contexto na seleção, **true**; caso contrário, **false**. |

### Valor de retorno

Um [XPathNodeIterator](../../xpathnodeiterator/) que contém os nós selecionados. Os nós retornados estão em ordem de documento inversa.

## XPathNavigator::SelectAncestors(String, String, bool) método

Seleciona todos os nós ancestrais do nó atual que possuam o nome local e o URI do namespace especificados.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome local dos nós ancestrais. |
| namespaceURI | [String](../../../system/string/) | O URI do namespace dos nós ancestrais. |
| matchSelf | **bool** | Para incluir o nó de contexto na seleção, **true**; caso contrário, **false**. |

### Valor de retorno

Um [XPathNodeIterator](../../xpathnodeiterator/) que contém os nós selecionados. Os nós retornados estão em ordem de documento inversa.

## Ver também

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XPathNodeIterator](../../xpathnodeiterator/)
* Classe [XPathNavigator](../)
* Classe [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)