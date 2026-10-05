---
title: WriteRaw()
second_title: Aspose.Slides for C++ API Reference
description: Writes raw markup manually from a character buffer.
type: docs
weight: 417
url: /system.xml/xmltextwriter/writeraw/
---
## XmlTextWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) method


Writes raw markup manually from a character buffer.

```cpp
void System::Xml::XmlTextWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Character array containing the text to write. |
| index | **int32_t** | The position within the buffer indicating the start of the text to write. |
| count | **int32_t** | The number of characters to write. |

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | **buffer** is **nullptr**. |
| ArgumentOutOfRangeException | **index** or **count** is less than zero. The buffer length minus **index** is less than **count**. |


## XmlTextWriter::WriteRaw(const String&) method


Writes raw markup manually from a string.

```cpp
void System::Xml::XmlTextWriter::WriteRaw(const String &data) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [String](../../../system/string/)& | [String](../../../system/string/) containing the text to write. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextWriter](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)