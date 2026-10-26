---
title: ReadElementString()
second_title: Referência da API Aspose.Slides para C++
description: "Lê um elemento somente de texto. Entretanto, recomenda-se usar o método XmlReader::ReadElementContentAsString em vez disso, pois ele fornece uma maneira mais direta de lidar com esta operação."
type: docs
weight: 859
url: /pt/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() método

Lê um elemento somente de texto. Entretanto, recomenda-se usar o método [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) em vez disso, pois ele fornece uma maneira mais direta de lidar com esta operação.

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```

### Valor de Retorno

O texto contido no elemento que foi lido. Uma string vazia se o elemento estiver vazio.

## XmlReader::ReadElementString(String) método

Verifica se o valor [XmlReader::get_Name](../get_name/) do elemento encontrado corresponde à string fornecida antes de ler um elemento somente de texto. Entretanto, recomenda-se usar o método [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) em vez disso, pois ele fornece uma maneira mais direta de lidar com esta operação.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome a ser verificado. |

### Valor de Retorno

O texto contido no elemento que foi lido. Uma string vazia se o elemento estiver vazio.

## XmlReader::ReadElementString(String, String) método

Verifica se os valores [XmlReader::get_LocalName](../get_localname/) e [XmlReader::get_NamespaceURI](../get_namespaceuri/) do elemento encontrado correspondem às strings fornecidas antes de ler um elemento somente de texto. Entretanto, recomenda-se usar o método [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) em vez disso, pois ele fornece uma maneira mais direta de lidar com esta operação.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localname | [String](../../../system/string/) | O nome local a ser verificado. |
| ns | [String](../../../system/string/) | O URI do namespace a ser verificado. |

### Valor de Retorno

O texto contido no elemento que foi lido. Uma string vazia se o elemento estiver vazio.

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)