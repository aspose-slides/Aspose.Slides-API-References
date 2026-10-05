---
title: WriteName()
second_title: Aspose.Slides for C++ API Reference
description: Writes out the specified name, ensuring it is a valid name according to the .
type: docs
weight: 482
url: /system.xml/xmltextwriter/writename/
---
## XmlTextWriter::WriteName(const String&) method


Writes out the specified name, ensuring it is a valid name according to the [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name).

```cpp
void System::Xml::XmlTextWriter::WriteName(const String &name) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)& | Name to write. |

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentException | **name** is not a valid XML name; or **name** is either **nullptr** or [String::Empty](../../../system/string/empty/). |


## See Also

* Class [String](../../../system/string/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)