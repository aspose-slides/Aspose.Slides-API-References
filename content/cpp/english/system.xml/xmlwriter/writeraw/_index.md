---
title: WriteRaw()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, writes raw markup manually from a character buffer.
type: docs
weight: 287
url: /system.xml/xmlwriter/writeraw/
---
## XmlWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) method


When overridden in a derived class, writes raw markup manually from a character buffer.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Character array containing the text to write. |
| index | **int32_t** | The position within the buffer indicating the start of the text to write. |
| count | **int32_t** | The number of characters to write. |

## XmlWriter::WriteRaw(const String\&) method


When overridden in a derived class, writes raw markup manually from a string.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(const String &data)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) containing the text to write. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlWriter](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)