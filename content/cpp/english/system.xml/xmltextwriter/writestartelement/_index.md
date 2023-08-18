---
title: WriteStartElement()
second_title: Aspose.Slides for C++ API Reference
description: Writes the specified start tag and associates it with the given namespace and prefix.
type: docs
weight: 235
url: /system.xml/xmltextwriter/writestartelement/
---
## XmlTextWriter::WriteStartElement(const String\&, const String\&, const String\&) method


Writes the specified start tag and associates it with the given namespace and prefix.

```cpp
void System::Xml::XmlTextWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | The namespace prefix of the element. |
| localName | const [String](../../../system/string/)\& | The local name of the element. |
| ns | const [String](../../../system/string/)\& | The namespace URI to associate with the element. If this namespace is already in scope and has an associated prefix then the writer automatically writes that prefix also. |

## See Also

* Class [String](../../../system/string/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)