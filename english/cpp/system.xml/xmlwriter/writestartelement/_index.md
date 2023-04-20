---
title: WriteStartElement()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, writes the specified start tag and associates it with the given namespace.
type: docs
weight: 92
url: /cpp/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String\&, const String\&) method


When overridden in a derived class, writes the specified start tag and associates it with the given namespace.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | The local name of the element. |
| ns | const [String](../../../system/string/)\& | The namespace URI to associate with the element. If this namespace is already in scope and has an associated prefix, the writer automatically writes that prefix also. |

## XmlWriter::WriteStartElement(const String\&, const String\&, const String\&) method


When overridden in a derived class, writes the specified start tag and associates it with the given namespace and prefix.

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | The namespace prefix of the element. |
| localName | const [String](../../../system/string/)\& | The local name of the element. |
| ns | const [String](../../../system/string/)\& | The namespace URI to associate with the element. |

## XmlWriter::WriteStartElement(const String\&) method


When overridden in a derived class, writes out a start tag with the specified local name.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | The local name of the element. |

## See Also

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)