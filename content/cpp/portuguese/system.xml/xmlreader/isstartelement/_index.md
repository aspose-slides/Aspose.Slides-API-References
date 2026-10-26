---
title: IsStartElement()
second_title: Referência da API Aspose.Slides para C++
description: "Chama XmlReader::MoveToContent e verifica se o nó de conteúdo atual é uma tag de início ou uma tag de elemento vazio."
type: docs
weight: 885
url: /pt/system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() método


Chama [XmlReader::MoveToContent](../movetocontent/) e verifica se o nó de conteúdo atual é uma tag de início ou uma tag de elemento vazio.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```


### Valor de Retorno

**true** se [XmlReader::MoveToContent](../movetocontent/) encontrar uma tag de início ou uma tag de elemento vazio; **false** se for encontrado um tipo de nó diferente de [XmlNodeType::Element](../../xmlnodetype/).

## XmlReader::IsStartElement(String) método


Chama [XmlReader::MoveToContent](../movetocontent/) e verifica se o nó de conteúdo atual é uma tag de início ou uma tag de elemento vazio e se o valor [XmlReader::get_Name](../get_name/) do elemento encontrado corresponde ao argumento fornecido.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | A string comparada com o valor **Name** do elemento encontrado. |

### Valor de Retorno

**true** se o nó resultante for um elemento e o valor **Name** corresponder à string especificada. **false** se for encontrado um tipo de nó diferente de [XmlNodeType::Element](../../xmlnodetype/) ou se o valor **Name** do elemento não coincidir com a string especificada.

## XmlReader::IsStartElement(String, String) método


Chama [XmlReader::MoveToContent](../movetocontent/) e verifica se o nó de conteúdo atual é uma tag de início ou uma tag de elemento vazio e se os valores [XmlReader::get_LocalName](../get_localname/) e [XmlReader::get_NamespaceURI](../get_namespaceuri/) do elemento encontrado correspondem às strings fornecidas.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localname | [String](../../../system/string/) | A string a ser comparada com o valor **LocalName** do elemento encontrado. |
| ns | [String](../../../system/string/) | A string a ser comparada com o valor **NamespaceURI** do elemento encontrado. |

### Valor de Retorno

**true** se o nó resultante for um elemento. **false** se for encontrado um tipo de nó diferente de [XmlNodeType::Element](../../xmlnodetype/) ou se os valores **LocalName** e **NamespaceURI** do elemento não coincidirem com as strings especificadas.

## Veja Também

* Classe [XmlReader](../)
* Classe [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)