---
title: ToByteArray()
second_title: Aspose.Slides for C++ API Reference
description: Converts string or substring to array of bytes.
type: docs
weight: 482
url: /system/string/tobytearray/
---
## String::ToByteArray(int32_t, int32_t, bool) const method


Converts string or substring to array of bytes.

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=1) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | **int32_t** | Substring start index. |
| length | **int32_t** | Substring length. |
| LE | **bool** | If true, encode characters using little endianness; otherwise, use big endianness. |

### Return Value

[Array](../../array/) containing bytes representing characters of the string.

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)