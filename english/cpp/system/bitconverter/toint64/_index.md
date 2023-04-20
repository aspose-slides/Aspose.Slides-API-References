---
title: ToInt64()
second_title: Aspose.Slides for C++ API Reference
description: Converts eight bytes from the specified array starting at the specified index to 64-bit integer value.
type: docs
weight: 79
url: /cpp/system/bitconverter/toint64/
---
## BitConverter::ToInt64(const System::ArrayPtr\<uint8_t\>\&, int) method


Converts eight bytes from the specified array starting at the specified index to 64-bit integer value.

```cpp
static int64_t System::BitConverter::ToInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) that contains bytes to convert |
| startIndex | int | Index in the array at which to start taking bytes for conversion |

### Return Value

64-bit integer value resulting from conversion

## BitConverter::ToInt64(const System::Details::ArrayView\<uint8_t\>\&, int) method


Converts eight bytes from the specified array starting at the specified index to 64-bit integer value.

```cpp
static int64_t System::BitConverter::ToInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView that contains bytes to convert |
| startIndex | int | Index in the array at which to start taking bytes for conversion |

### Return Value

64-bit integer value resulting from conversion

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)