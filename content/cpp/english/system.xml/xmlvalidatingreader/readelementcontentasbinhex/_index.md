---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides for C++ API Reference
description: Reads the element and decodes the BinHex content.
type: docs
weight: 612
url: /system.xml/xmlvalidatingreader/readelementcontentasbinhex/
---
## XmlValidatingReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) method


Reads the element and decodes the BinHex content.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The buffer into which to copy the resulting text. This value cannot be **nullptr**. |
| index | **int32_t** | The offset into the buffer where to start copying the result. |
| count | **int32_t** | The maximum number of bytes to copy into the buffer. The actual number of bytes copied is returned from this method. |

### Return Value

The number of bytes written to the buffer.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | The **buffer** value is **nullptr**. |
| InvalidOperationException | The current node is not an element node. |
| ArgumentOutOfRangeException | The index into the buffer or index + count is larger than the allocated buffer size. |
| NotSupportedException | The [XmlValidatingReader](../) implementation does not support this method. |
| XmlException | The element contains mixed-content. |
| FormatException | The content cannot be converted to the requested type. |


## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)