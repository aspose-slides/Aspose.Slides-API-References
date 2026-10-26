---
title: XPathDocument()
second_title: Aspose.Slides para C++ - Referência da API
description: Inicializa uma nova instância da classe XPathDocument a partir dos dados XML contidos no objeto XmlReader especificado.
type: docs
weight: 1
url: /pt/system.xml.xpath/xpathdocument/xpathdocument/
---
## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&) construtor


Inicializa uma nova instância da classe [XPathDocument](../) a partir dos dados XML contidos no objeto [XmlReader](../../../system.xml/xmlreader/) especificado.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | O objeto [XmlReader](../../../system.xml/xmlreader/) que contém os dados XML. |

## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&, XmlSpace) construtor


Inicializa uma nova instância da classe [XPathDocument](../) a partir dos dados XML contidos no objeto [XmlReader](../../../system.xml/xmlreader/) especificado, com o tratamento de espaço em branco especificado.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader, XmlSpace space)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | O objeto [XmlReader](../../../system.xml/xmlreader/) que contém os dados XML. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | Um objeto XmlSpace. |

## XPathDocument::XPathDocument(const SharedPtr\<IO::TextReader\>\&) construtor


Inicializa uma nova instância da classe [XPathDocument](../) a partir dos dados XML contidos no objeto TextReader especificado.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::TextReader> &textReader)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| textReader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | O objeto TextReader que contém os dados XML. |

## XPathDocument::XPathDocument(const SharedPtr\<IO::Stream\>\&) construtor


Inicializa uma nova instância da classe [XPathDocument](../) a partir dos dados XML no objeto Stream especificado.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::Stream> &stream)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | O objeto Stream que contém os dados XML. |

## XPathDocument::XPathDocument(const String\&) construtor


Inicializa uma nova instância da classe [XPathDocument](../) a partir dos dados XML no arquivo especificado.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | O caminho do arquivo que contém os dados XML. |

## XPathDocument::XPathDocument(const String\&, XmlSpace) construtor


Inicializa uma nova instância da classe [XPathDocument](../) a partir dos dados XML no arquivo especificado, com o tratamento de espaço em branco definido.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri, XmlSpace space)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | O caminho do arquivo que contém os dados XML. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | Um objeto XmlSpace. |

## Veja Também

* Enum [XmlSpace](../../../system.xml/xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlReader](../../../system.xml/xmlreader/)
* Classe [XPathDocument](../)
* Classe [TextReader](../../../system.io/textreader/)
* Classe [Stream](../../../system.io/stream/)
* Classe [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)