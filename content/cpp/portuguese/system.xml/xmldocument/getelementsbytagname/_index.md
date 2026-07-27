---
title: GetElementsByTagName()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um XmlNodeList contendo uma lista de todos os elementos descendentes que correspondem ao nome especificado.
type: docs
weight: 443
url: /pt/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String) método


Retorna um [XmlNodeList](../../xmlnodelist/) contendo uma lista de todos os elementos descendentes que correspondem ao nome especificado.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome qualificado a ser comparado. É comparado ao valor **get_Name** do nó correspondente. O valor especial **\"*\"** corresponde a todas as tags. |

### Valor de retorno

Um [XmlNodeList](../../xmlnodelist/) contendo uma lista de todos os nós correspondentes. Se nenhum nó corresponder a **name**, a coleção retornada será vazia.

## XmlDocument::GetElementsByTagName(String, String) método


Retorna um [XmlNodeList](../../xmlnodelist/) contendo uma lista de todos os elementos descendentes que correspondem ao [XmlDocument::get_LocalName](../get_localname/) e [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) especificados.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | [String](../../../system/string/) | O LocalName a ser comparado. O valor especial **\"*\"** corresponde a todas as tags. |
| namespaceURI | [String](../../../system/string/) | NamespaceURI a ser comparado. |

### Valor de retorno

Um [XmlNodeList](../../xmlnodelist/) contendo uma lista de todos os nós correspondentes. Se nenhum nó corresponder ao **localName** e **namespaceURI** especificados, a coleção retornada será vazia.

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNodeList](../../xmlnodelist/)
* Classe [String](../../../system/string/)
* Classe [XmlDocument](../)
* Espaço de nomes [System::Xml](../../)
* Library [Aspose.Slides](../../../)