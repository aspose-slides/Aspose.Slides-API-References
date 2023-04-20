---
title: WriteAttributeString()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, writes an attribute with the specified local name, namespace URI, and value.
type: docs
weight: 131
url: /cpp/system.xml/xmlwriter/writeattributestring/
---
## XmlWriter::WriteAttributeString(const String\&, const String\&, const String\&) method


When overridden in a derived class, writes an attribute with the specified local name, namespace URI, and value.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &localName, const String &ns, const String &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | The local name of the attribute. |
| ns | const [String](../../../system/string/)\& | The namespace URI to associate with the attribute. |
| value | const [String](../../../system/string/)\& | The value of the attribute. |

## XmlWriter::WriteAttributeString(const String\&, const String\&) method


When overridden in a derived class, writes out the attribute with the specified local name and value.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &localName, const String &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | The local name of the attribute. |
| value | const [String](../../../system/string/)\& | The value of the attribute. |

## XmlWriter::WriteAttributeString(const String\&, const String\&, const String\&, const String\&) method


When overridden in a derived class, writes out the attribute with the specified prefix, local name, namespace URI, and value.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &prefix, const String &localName, const String &ns, const String &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | The namespace prefix of the attribute. |
| localName | const [String](../../../system/string/)\& | The local name of the attribute. |
| ns | const [String](../../../system/string/)\& | The namespace URI of the attribute. |
| value | const [String](../../../system/string/)\& | The value of the attribute. |

## See Also

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)