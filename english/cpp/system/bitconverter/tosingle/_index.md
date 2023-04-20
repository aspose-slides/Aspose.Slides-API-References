---
title: ToSingle()
second_title: Aspose.Slides for C++ API Reference
description: Converts four bytes from the specified array starting at the specified index to single-precision floating point value.
type: docs
weight: 131
url: /cpp/system/bitconverter/tosingle/
---
## BitConverter::ToSingle(const System::ArrayPtr\<uint8_t\>\&, int) method


Converts four bytes from the specified array starting at the specified index to single-precision floating point value.

```cpp
static float System::BitConverter::ToSingle(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) that contains bytes to convert |
| startIndex | int | Index in the array at which to start taking bytes for conversion |

### Return Value

Single-precision floating-point value resulting from conversion

## BitConverter::ToSingle(const System::Details::ArrayView\<uint8_t\>\&, int) method


Converts four bytes from the specified array starting at the specified index to single-precision floating point value.

```cpp
static float System::BitConverter::ToSingle(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView that contains bytes to convert |
| startIndex | int | Index in the array at which to start taking bytes for conversion |

### Return Value

Single-precision floating-point value resulting from conversion

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)