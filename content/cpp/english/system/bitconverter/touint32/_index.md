---
title: ToUInt32()
second_title: Aspose.Slides for C++ API Reference
description: Converts four bytes from the specified array starting at the specified index to unsigned 32-bit integer value.
type: docs
weight: 105
url: /system/bitconverter/touint32/
---
## BitConverter::ToUInt32(const System::ArrayPtr\<uint8_t\>\&, int) method


Converts four bytes from the specified array starting at the specified index to unsigned 32-bit integer value.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) that contains bytes to convert |
| startIndex | int | Index in the array at which to start taking bytes for conversion |

### Return Value

Unsigned 32-bit integer value resulting from conversion

## BitConverter::ToUInt32(const System::Details::ArrayView\<uint8_t\>\&, int) method


Converts four bytes from the specified array starting at the specified index to unsigned 32-bit integer value.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView that contains bytes to convert |
| startIndex | int | Index in the array at which to start taking bytes for conversion |

### Return Value

Unsigned 32-bit integer value resulting from conversion

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)