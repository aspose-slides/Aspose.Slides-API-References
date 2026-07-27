---
title: PrependChild()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um objeto XmlWriter usado para criar um novo nó filho no início da lista de nós filhos do nó atual.
type: docs
weight: 872
url: /pt/system.xml.xpath/xpathnavigator/prependchild/
---
## XPathNavigator::PrependChild() método

Retorna um objeto [XmlWriter](../../../system.xml/xmlwriter/) usado para criar um novo nó filho no início da lista de nós filhos do nó atual.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::PrependChild()
```

### Valor de Retorno

Um objeto [XmlWriter](../../../system.xml/xmlwriter/) usado para criar um novo nó filho no início da lista de nós filhos do nó atual.

## XPathNavigator::PrependChild(String) método

Cria um novo nó filho no início da lista de nós filhos do nó atual usando a string XML especificada.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(String newChild)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | A string de dados XML para o novo nó filho. |

## XPathNavigator::PrependChild(SharedPtr\<XmlReader\>) método

Cria um novo nó filho no início da lista de nós filhos do nó atual usando o conteúdo XML do objeto [XmlReader](../../../system.xml/xmlreader/) especificado.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XmlReader> newChild)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Um objeto [XmlReader](../../../system.xml/xmlreader/) posicionado nos dados XML para o novo nó filho. |

## XPathNavigator::PrependChild(SharedPtr\<XPathNavigator\>) método

Cria um novo nó filho no início da lista de nós filhos do nó atual usando os nós no objeto [XPathNavigator](../) especificado.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XPathNavigator> newChild)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Um objeto [XPathNavigator](../) posicionado no nó a ser adicionado como novo nó filho. |

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlWriter](../../../system.xml/xmlwriter/)
* Classe [XPathNavigator](../)
* Classe [String](../../../system/string/)
* Classe [XmlReader](../../../system.xml/xmlreader/)
* Espaço de nomes [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)