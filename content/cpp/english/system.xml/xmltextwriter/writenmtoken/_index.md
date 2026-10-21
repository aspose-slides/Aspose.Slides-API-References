---
title: WriteNmToken()
second_title: Aspose.Slides for C++ API Reference
description: Writes out the specified name, ensuring it is a valid NmToken according to the .
type: docs
weight: 521
url: /system.xml/xmltextwriter/writenmtoken/
---
## XmlTextWriter::WriteNmToken(const String&) method


Writes out the specified name, ensuring it is a valid **NmToken** according to the [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name).

```cpp
void System::Xml::XmlTextWriter::WriteNmToken(const String &name) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)& | Name to write. |

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentException | **name** is not a valid **NmToken**; or **name** is either **nullptr** or [String::Empty](../../../system/string/empty/). |


## See Also

* Class [String](../../../system/string/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)