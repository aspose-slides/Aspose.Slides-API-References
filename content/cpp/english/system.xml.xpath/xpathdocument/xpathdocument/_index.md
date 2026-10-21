---
title: XPathDocument()
second_title: Aspose.Slides for C++ API Reference
description: Initializes a new instance of the XPathDocument class from the XML data that is contained in the specified XmlReader object.
type: docs
weight: 1
url: /system.xml.xpath/xpathdocument/xpathdocument/
---
## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>&) constructor


Initializes a new instance of the [XPathDocument](../) class from the XML data that is contained in the specified [XmlReader](../../../system.xml/xmlreader/) object.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>& | The [XmlReader](../../../system.xml/xmlreader/) object that contains the XML data. |

### Exceptions

| Exception | Description |
| --- | --- |
| XmlException | An error was encountered in the XML data. The [XPathDocument](../) remains empty. |
| ArgumentNullException | The [XmlReader](../../../system.xml/xmlreader/) object passed as a parameter is **nullptr**. |


## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>&, XmlSpace) constructor


Initializes a new instance of the [XPathDocument](../) class from the XML data that is contained in the specified [XmlReader](../../../system.xml/xmlreader/) object with the specified white space handling.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader, XmlSpace space)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>& | The [XmlReader](../../../system.xml/xmlreader/) object that contains the XML data. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | An XmlSpace object. |

### Exceptions

| Exception | Description |
| --- | --- |
| XmlException | An error was encountered in the XML data. The [XPathDocument](../) remains empty. |
| ArgumentNullException | The [XmlReader](../../../system.xml/xmlreader/) object parameter or XmlSpace object parameter is **nullptr**. |


## XPathDocument::XPathDocument(const SharedPtr\<IO::TextReader\>&) constructor


Initializes a new instance of the [XPathDocument](../) class from the XML data that is contained in the specified TextReader object.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::TextReader> &textReader)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| textReader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>& | The TextReader object that contains the XML data. |

### Exceptions

| Exception | Description |
| --- | --- |
| XmlException | An error was encountered in the XML data. The [XPathDocument](../) remains empty. |
| ArgumentNullException | The TextReader object passed as a parameter is **nullptr**. |


## XPathDocument::XPathDocument(const SharedPtr\<IO::Stream\>&) constructor


Initializes a new instance of the [XPathDocument](../) class from the XML data in the specified Stream object.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::Stream> &stream)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>& | The Stream object that contains the XML data. |

### Exceptions

| Exception | Description |
| --- | --- |
| XmlException | An error was encountered in the XML data. The [XPathDocument](../) remains empty. |
| ArgumentNullException | The Stream object passed as a parameter is **nullptr**. |


## XPathDocument::XPathDocument(const String&) constructor


Initializes a new instance of the [XPathDocument](../) class from the XML data in the specified file.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uri | const [String](../../../system/string/)& | The path of the file that contains the XML data. |

### Exceptions

| Exception | Description |
| --- | --- |
| XmlException | An error was encountered in the XML data. The [XPathDocument](../) remains empty. |
| ArgumentNullException | The file path parameter is **nullptr**. |


## XPathDocument::XPathDocument(const String&, XmlSpace) constructor


Initializes a new instance of the [XPathDocument](../) class from the XML data in the file specified with the white space handling specified.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri, XmlSpace space)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uri | const [String](../../../system/string/)& | The path of the file that contains the XML data. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | An XmlSpace object. |

### Exceptions

| Exception | Description |
| --- | --- |
| XmlException | An error was encountered in the XML data. The [XPathDocument](../) remains empty. |
| ArgumentNullException | The file path parameter or XmlSpace object parameter is **nullptr**. |


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