---
title: WriteQualifiedName()
second_title: Aspose.Slides for C++ API Reference
description: Writes out the namespace-qualified name. This method looks up the prefix that is in scope for the given namespace.
type: docs
weight: 495
url: /system.xml/xmltextwriter/writequalifiedname/
---
## XmlTextWriter::WriteQualifiedName(const String&, const String&) method


Writes out the namespace-qualified name. This method looks up the prefix that is in scope for the given namespace.

```cpp
void System::Xml::XmlTextWriter::WriteQualifiedName(const String &localName, const String &ns) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)& | The local name to write. |
| ns | const [String](../../../system/string/)& | The namespace URI to associate with the name. |

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentException | **localName** is either **nullptr** or [String::Empty](../../../system/string/empty/). **localName** is not a valid name according to the W3C Namespaces spec. |


## See Also

* Class [String](../../../system/string/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)