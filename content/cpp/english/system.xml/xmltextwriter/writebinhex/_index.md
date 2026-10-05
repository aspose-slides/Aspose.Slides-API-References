---
title: WriteBinHex()
second_title: Aspose.Slides for C++ API Reference
description: Encodes the specified binary bytes as binhex and writes out the resulting text.
type: docs
weight: 443
url: /system.xml/xmltextwriter/writebinhex/
---
## XmlTextWriter::WriteBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) method


Encodes the specified binary bytes as binhex and writes out the resulting text.

```cpp
void System::Xml::XmlTextWriter::WriteBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Byte](../../../system/byte/) array to encode. |
| index | **int32_t** | The position in the buffer indicating the start of the bytes to write. |
| count | **int32_t** | The number of bytes to write. |

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | **buffer** is **nullptr**. |
| ArgumentException | The buffer length minus **index** is less than **count**. |
| ArgumentOutOfRangeException | **index** or **count** is less than zero. |
| InvalidOperationException | The [XmlTextWriter::get_WriteState](../get_writestate/) value is [WriteState::Closed](../../writestate/). |


## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)