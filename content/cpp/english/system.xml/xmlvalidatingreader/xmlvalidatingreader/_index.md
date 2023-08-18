---
title: XmlValidatingReader()
second_title: Aspose.Slides for C++ API Reference
description: Initializes a new instance of the XmlValidatingReader class that validates the content returned from the given XmlReader.
type: docs
weight: 430
url: /system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) constructor


Initializes a new instance of the [XmlValidatingReader](../) class that validates the content returned from the given [XmlReader](../../xmlreader/).

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\>\& | The [XmlReader](../../xmlreader/) to read from while validating. The current implementation supports only [XmlTextReader](../../xmltextreader/). |

## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


Initializes a new instance of the [XmlValidatingReader](../) class with the specified values.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | The string containing the XML fragment to parse. |
| fragType | [XmlNodeType](../../xmlnodetype/) | The XmlNodeType of the XML fragment. This also determines what the fragment string can contain (see table below). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | The [XmlParserContext](../../xmlparsercontext/) in which the XML fragment is to be parsed. This includes the [NameTable](../../nametable/) to use, encoding, namespace scope, current **xml:lang**, and **xml:space** scope. |
## Remarks



The following table lists valid values for **fragType** and how the reader parses each of the different node types. 

| XmlNodeType | Fragment May Contain |
| --- | --- |
| Element| Any valid element content (for example, any combination of elements, comments, processing instructions, cdata, text, and entity references). |
| [Attribute](../../../system/attribute/)| The value of an attribute (the part inside the quotes). |
| Document| The contents of an entire XML document; this enforces document level rules. |


## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


Initializes a new instance of the [XmlValidatingReader](../) class with the specified values.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | The stream containing the XML fragment to parse. |
| fragType | [XmlNodeType](../../xmlnodetype/) | The XmlNodeType of the XML fragment. This determines what the fragment can contain (see table below). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | The [XmlParserContext](../../xmlparsercontext/) in which the XML fragment is to be parsed. This includes the [XmlNameTable](../../xmlnametable/) to use, encoding, namespace scope, current **xml:lang**, and **xml:space** scope. |
## Remarks



The following table lists valid values for **fragType** and how the reader parses each of the different node types. 

| XmlNodeType | Fragment May Contain |
| --- | --- |
| Element| Any valid element content (for example, any combination of elements, comments, processing instructions, cdata, text, and entity references). |
| [Attribute](../../../system/attribute/)| The value of an attribute (the part inside the quotes). |
| Document| The contents of an entire XML document; this enforces document level rules. |


## See Also

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlValidatingReader](../)
* Class [String](../../../system/string/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)