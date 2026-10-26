---
title: XPathDocument()
second_title: Référence de l'API Aspose.Slides pour C++
description: Initialise une nouvelle instance de la classe XPathDocument à partir des données XML contenues dans l'objet XmlReader spécifié.
type: docs
weight: 1
url: /fr/system.xml.xpath/xpathdocument/xpathdocument/
---
## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&) constructor

Initialise une nouvelle instance de la classe [XPathDocument](../) à partir des données XML contenues dans l'objet [XmlReader](../../../system.xml/xmlreader/) spécifié.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | L'objet [XmlReader](../../../system.xml/xmlreader/) qui contient les données XML. |

## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&, XmlSpace) constructor

Initialise une nouvelle instance de la classe [XPathDocument](../) à partir des données XML contenues dans l'objet [XmlReader](../../../system.xml/xmlreader/) spécifié avec le traitement des espaces blancs indiqué.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader, XmlSpace space)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | L'objet [XmlReader](../../../system.xml/xmlreader/) qui contient les données XML. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | Un objet XmlSpace. |

## XPathDocument::XPathDocument(const SharedPtr\<IO::TextReader\>\&) constructor

Initialise une nouvelle instance de la classe [XPathDocument](../) à partir des données XML contenues dans l'objet TextReader spécifié.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::TextReader> &textReader)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| textReader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | L'objet TextReader qui contient les données XML. |

## XPathDocument::XPathDocument(const SharedPtr\<IO::Stream\>\&) constructor

Initialise une nouvelle instance de la classe [XPathDocument](../) à partir des données XML contenues dans l'objet Stream spécifié.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::Stream> &stream)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | L'objet Stream qui contient les données XML. |

## XPathDocument::XPathDocument(const String\&) constructor

Initialise une nouvelle instance de la classe [XPathDocument](../) à partir des données XML du fichier spécifié.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | Le chemin du fichier qui contient les données XML. |

## XPathDocument::XPathDocument(const String\&, XmlSpace) constructor

Initialise une nouvelle instance de la classe [XPathDocument](../) à partir des données XML du fichier spécifié avec le traitement des espaces blancs indiqué.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri, XmlSpace space)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | Le chemin du fichier qui contient les données XML. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | Un objet XmlSpace. |

## See Also

* Enum [XmlSpace](../../../system.xml/xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathDocument](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)