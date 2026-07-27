---
title: GetElementsByTagName()
second_title: Referência da API Aspose.Slides para C++
description: "Retorna um XmlNodeList contendo uma lista de todos os elementos descendentes que correspondem ao XmlElement::get_Name especificado."
type: docs
weight: 287
url: /pt/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String) método


Retorna um [XmlNodeList](../../xmlnodelist/) contendo uma lista de todos os elementos descendentes que correspondem ao [XmlElement::get_Name](../get_name/) especificado.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | A tag de nome a ser correspondida. Este é um nome qualificado. Ele é comparado ao valor **get_Name** do nó correspondente. O asterisco (*) é um valor especial que corresponde a todas as tags. |

### Valor de Retorno

Um [XmlNodeList](../../xmlnodelist/) contendo uma lista de todos os nós correspondentes. A lista está vazia se não houver nós correspondentes.

## XmlElement::GetElementsByTagName(String, String) método


Retorna um [XmlNodeList](../../xmlnodelist/) contendo uma lista de todos os elementos descendentes que correspondem aos valores [XmlElement::get_LocalName](../get_localname/) e [XmlElement::get_NamespaceURI](../get_namespaceuri/) especificados.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | [String](../../../system/string/) | O nome local a ser correspondido. O asterisco (*) é um valor especial que corresponde a todas as tags. |
| namespaceURI | [String](../../../system/string/) | O URI do espaço de nomes a ser correspondido. |

### Valor de Retorno

Um [XmlNodeList](../../xmlnodelist/) contendo uma lista de todos os nós correspondentes. A lista está vazia se não houver nós correspondentes.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNodeList](../../xmlnodelist/)
* Classe [String](../../../system/string/)
* Classe [XmlElement](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)