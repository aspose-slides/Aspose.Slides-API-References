---
title: WriteChars()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, writes text one buffer at a time.
type: docs
weight: 274
url: /system.xml/xmlwriter/writechars/
---
## XmlWriter::WriteChars(ArrayPtr\<char16_t\>, int32_t, int32_t) method


When overridden in a derived class, writes text one buffer at a time.

```cpp
virtual void System::Xml::XmlWriter::WriteChars(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
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
| ArgumentOutOfRangeException | **index** or **count** is less than zero. or The buffer length minus **index** is less than **count**; the call results in surrogate pair characters being split or an invalid surrogate pair being written. |
| ArgumentException | The **buffer** parameter value is not valid. |


## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)