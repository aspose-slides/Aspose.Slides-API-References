---
title: ReadStartElement()
second_title: Referência da API Aspose.Slides para C++
description: Verifica se o nó atual é um elemento e avança o leitor para o próximo nó.
type: docs
weight: 846
url: /pt/system.xml/xmlreader/readstartelement/
---
## XmlReader::ReadStartElement() método

Verifica se o nó atual é um elemento e avança o leitor para o próximo nó.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement()
```

## XmlReader::ReadStartElement(String) método

Verifica se o nó de conteúdo atual é um elemento com o valor [XmlReader::get_Name](../get_name/) fornecido e avança o leitor para o próximo nó.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String name)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome qualificado do elemento. |

## XmlReader::ReadStartElement(String, String) método

Verifica se o nó de conteúdo atual é um elemento com os valores [XmlReader::get_LocalName](../get_localname/) e [XmlReader::get_NamespaceURI](../get_namespaceuri/) fornecidos e avança o leitor para o próximo nó.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String localname, String ns)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| localname | [String](../../../system/string/) | O nome local do elemento. |
| ns | [String](../../../system/string/) | O URI do namespace do elemento. |

## Veja Também

* Classe [XmlReader](../)
* Classe [String](../../../system/string/)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)