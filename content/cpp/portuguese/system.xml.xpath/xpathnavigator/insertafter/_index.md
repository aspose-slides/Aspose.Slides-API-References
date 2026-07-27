---
title: InsertAfter()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um objeto XmlWriter usado para criar um novo nó irmão após o nó atualmente selecionado.
type: docs
weight: 898
url: /pt/system.xml.xpath/xpathnavigator/insertafter/
---
## XPathNavigator::InsertAfter() método

Retorna um objeto [XmlWriter](../../../system.xml/xmlwriter/) usado para criar um novo nó irmão após o nó atualmente selecionado.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertAfter()
```

### Valor de Retorno

Um objeto [XmlWriter](../../../system.xml/xmlwriter/) usado para criar um novo nó irmão após o nó atualmente selecionado.

## XPathNavigator::InsertAfter(String) método

Cria um novo nó irmão após o nó atualmente selecionado usando a string XML especificada.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(String newSibling)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | A string de dados XML para o novo nó irmão. |

## XPathNavigator::InsertAfter(SharedPtr\<XmlReader\>) método

Cria um novo nó irmão após o nó atualmente selecionado usando o conteúdo XML do objeto [XmlReader](../../../system.xml/xmlreader/) especificado.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XmlReader> newSibling)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Um objeto [XmlReader](../../../system.xml/xmlreader/) posicionado nos dados XML para o novo nó irmão. |

## XPathNavigator::InsertAfter(SharedPtr\<XPathNavigator\>) método

Cria um novo nó irmão após o nó atualmente selecionado usando os nós no objeto [XPathNavigator](../) especificado.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XPathNavigator> newSibling)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Um objeto [XPathNavigator](../) posicionado no nó a ser adicionado como o novo nó irmão. |

## Ver Também

* Definição de Tipo [SharedPtr](../../../system/sharedptr/)
* Classe [XmlWriter](../../../system.xml/xmlwriter/)
* Classe [XPathNavigator](../)
* Classe [String](../../../system/string/)
* Classe [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)