---
title: XPathDocument()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicializa una nueva instancia de la clase XPathDocument a partir de los datos XML que se encuentran en el objeto XmlReader especificado.
type: docs
weight: 1
url: /es/system.xml.xpath/xpathdocument/xpathdocument/
---
## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&) constructor

Inicializa una nueva instancia de la clase [XPathDocument](../) a partir de los datos XML que se encuentran en el objeto [XmlReader](../../../system.xml/xmlreader/) especificado.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | El objeto [XmlReader](../../../system.xml/xmlreader/) que contiene los datos XML. |

## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&, XmlSpace) constructor

Inicializa una nueva instancia de la clase [XPathDocument](../) a partir de los datos XML que se encuentran en el objeto [XmlReader](../../../system.xml/xmlreader/) especificado con el manejo de espacios en blanco especificado.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader, XmlSpace space)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | El objeto [XmlReader](../../../system.xml/xmlreader/) que contiene los datos XML. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | Un objeto XmlSpace. |

## XPathDocument::XPathDocument(const SharedPtr\<IO::TextReader\>\&) constructor

Inicializa una nueva instancia de la clase [XPathDocument](../) a partir de los datos XML que se encuentran en el objeto TextReader especificado.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::TextReader> &textReader)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| textReader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | El objeto TextReader que contiene los datos XML. |

## XPathDocument::XPathDocument(const SharedPtr\<IO::Stream\>\&) constructor

Inicializa una nueva instancia de la clase [XPathDocument](../) a partir de los datos XML que se encuentran en el objeto Stream especificado.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::Stream> &stream)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | El objeto Stream que contiene los datos XML. |

## XPathDocument::XPathDocument(const String\&) constructor

Inicializa una nueva instancia de la clase [XPathDocument](../) a partir de los datos XML que se encuentran en el archivo especificado.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | La ruta del archivo que contiene los datos XML. |

## XPathDocument::XPathDocument(const String\&, XmlSpace) constructor

Inicializa una nueva instancia de la clase [XPathDocument](../) a partir de los datos XML que se encuentran en el archivo especificado con el manejo de espacios en blanco especificado.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri, XmlSpace space)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | La ruta del archivo que contiene los datos XML. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | Un objeto XmlSpace. |

## Ver también

* Enum [XmlSpace](../../../system.xml/xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathDocument](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)