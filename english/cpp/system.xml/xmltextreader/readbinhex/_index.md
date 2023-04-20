---
title: ReadBinHex()
second_title: Aspose.Slides for C++ API Reference
description: Decodes BinHex and returns the decoded binary bytes.
type: docs
weight: 781
url: /cpp/system.xml/xmltextreader/readbinhex/
---
## XmlTextReader::ReadBinHex(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Decodes **BinHex** and returns the decoded binary bytes.

```cpp
int32_t System::Xml::XmlTextReader::ReadBinHex(const ArrayPtr<uint8_t> &array, int32_t offset, int32_t len)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | The byte array that serves as the buffer to which the decoded binary bytes are written. |
| offset | **int32_t** | The zero-based index into the array specifying where the method can begin to write to the buffer. |
| len | **int32_t** | The number of bytes to write into the buffer. |

### Return Value

The number of bytes written to your buffer.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)