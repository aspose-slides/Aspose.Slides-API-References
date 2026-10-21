---
title: WriteChars()
second_title: Aspose.Slides for C++ API Reference
description: Writes text one buffer at a time.
type: docs
weight: 404
url: /system.xml/xmltextwriter/writechars/
---
## XmlTextWriter::WriteChars(ArrayPtr\<char16_t\>, int32_t, int32_t) method


Writes text one buffer at a time.

```cpp
void System::Xml::XmlTextWriter::WriteChars(ArrayPtr<char16_t> buffer, int32_t index, int32_t count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Character array containing the text to write. |
| index | **int32_t** | The position in the buffer indicating the start of the text to write. |
| count | **int32_t** | The number of characters to write. |

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | **buffer** is **nullptr**. |
| ArgumentOutOfRangeException | **index** or **count** is less than zero. The buffer length minus **index** is less than **count**; the call results in surrogate pair characters being split or an invalid surrogate pair being written. |
| InvalidOperationException | The [XmlTextWriter::get_WriteState](../get_writestate/) value is [WriteState::Closed](../../writestate/). |


## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)