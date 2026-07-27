---
title: InsertBefore()
second_title: Referência da API Aspose.Slides for C++
description: Retorna um objeto XmlWriter usado para criar um novo nó irmão antes do nó atualmente selecionado.
type: docs
weight: 911
url: /pt/system.xml.xpath/xpathnavigator/insertbefore/
---
## XPathNavigator::InsertBefore() método


Retorna um objeto [XmlWriter](../../../system.xml/xmlwriter/) usado para criar um novo nó irmão antes do nó atualmente selecionado.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertBefore()
```


### Valor de Retorno

Um objeto [XmlWriter](../../../system.xml/xmlwriter/) usado para criar um novo nó irmão antes do nó atualmente selecionado.

## XPathNavigator::InsertBefore(String) método


Cria um novo nó irmão antes do nó atualmente selecionado usando a string XML especificada.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(String newSibling)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | A string de dados XML para o novo nó irmão. |

## XPathNavigator::InsertBefore(SharedPtr\<XmlReader\>) método


Cria um novo nó irmão antes do nó atualmente selecionado usando o conteúdo XML do objeto [XmlReader](../../../system.xml/xmlreader/) especificado.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XmlReader> newSibling)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Um objeto [XmlReader](../../../system.xml/xmlreader/) posicionado nos dados XML para o novo nó irmão. |

## XPathNavigator::InsertBefore(SharedPtr\<XPathNavigator\>) método


Cria um novo nó irmão antes do nó atualmente selecionado usando os nós no [XPathNavigator](../) especificado.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XPathNavigator> newSibling)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Um objeto [XPathNavigator](../) posicionado no nó a ser adicionado como novo nó irmão. |

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlWriter](../../../system.xml/xmlwriter/)
* Classe [XPathNavigator](../)
* Classe [String](../../../system/string/)
* Classe [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)