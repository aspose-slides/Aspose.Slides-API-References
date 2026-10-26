---
title: AppendChild()
second_title: Aspose.Slides para C++ Referência da API
description: Retorna um objeto XmlWriter usado para criar um ou mais novos nós filhos ao final da lista de nós filhos do nó atual.
type: docs
weight: 885
url: /pt/system.xml.xpath/xpathnavigator/appendchild/
---
## XPathNavigator::AppendChild() método

Retorna um objeto [XmlWriter](../../../system.xml/xmlwriter/) usado para criar um ou mais novos nós filhos ao final da lista de nós filhos do nó atual.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::AppendChild()
```

### Valor de retorno

Um objeto [XmlWriter](../../../system.xml/xmlwriter/) usado para criar novos nós filhos ao final da lista de nós filhos do nó atual.

## XPathNavigator::AppendChild(String) método

Cria um novo nó filho ao final da lista de nós filhos do nó atual usando a string de dados XML especificada.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(String newChild)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | A string de dados XML para o novo nó filho. |

## XPathNavigator::AppendChild(SharedPtr\<XmlReader\>) método

Cria um novo nó filho ao final da lista de nós filhos do nó atual usando o conteúdo XML do objeto [XmlReader](../../../system.xml/xmlreader/) especificado.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XmlReader> newChild)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Um objeto [XmlReader](../../../system.xml/xmlreader/) posicionado nos dados XML para o novo nó filho. |

## XPathNavigator::AppendChild(SharedPtr\<XPathNavigator\>) método

Cria um novo nó filho ao final da lista de nós filhos do nó atual usando os nós no [XPathNavigator](../) especificado.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XPathNavigator> newChild)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Um objeto [XPathNavigator](../) posicionado no nó a ser adicionado como novo nó filho. |

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [XmlWriter](../../../system.xml/xmlwriter/)
* classe [XPathNavigator](../)
* classe [String](../../../system/string/)
* classe [XmlReader](../../../system.xml/xmlreader/)
* namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)