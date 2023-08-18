---
title: FromBase64CharArray()
second_title: Aspose.Slides for C++ API Reference
description: Decodes base-64 encoded data represented as a range in the array of Unicode characters.
type: docs
weight: 53
url: /system/convert/frombase64chararray/
---
## Convert::FromBase64CharArray(const ArrayPtr\<char_t\>\&, int, int) method


Decodes base-64 encoded data represented as a range in the array of Unicode characters.

```cpp
static ArrayPtr<uint8_t> System::Convert::FromBase64CharArray(const ArrayPtr<char_t> &in_array, int offset, int length)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | The array containing the data to decode |
| offset | int | The position in the input array at which the range to decode begins |
| length | int | The length of the range to decode |

### Return Value

A byte-array containing the decoded data

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)