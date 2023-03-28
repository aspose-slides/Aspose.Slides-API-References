---
title: ReadContentAsBase64()
second_title: Aspose.Slides for C++ API Reference
description: Reads the content and returns the Base64 decoded binary bytes.
type: docs
weight: 638
url: /cpp/system.xml/xmltextreader/readcontentasbase64/
---
## XmlTextReader::ReadContentAsBase64([ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) method


Reads the content and returns the **Base64** decoded binary bytes.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The buffer into which to copy the resulting text. This value cannot be **nullptr**. |
| index | **int32_t** | The offset into the buffer where to start copying the result. |
| count | **int32_t** | The maximum number of bytes to copy into the buffer. The actual number of bytes copied is returned from this method. |

### Return Value

The number of bytes written to the buffer.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
