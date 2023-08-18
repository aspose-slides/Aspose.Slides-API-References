---
title: ToBoolean()
second_title: Aspose.Slides for C++ API Reference
description: Converts one byte from the specified array starting at the specified index to boolean value.
type: docs
weight: 27
url: /system/bitconverter/toboolean/
---
## BitConverter::ToBoolean(const System::ArrayPtr\<uint8_t\>\&, int) method


Converts one byte from the specified array starting at the specified index to boolean value.

```cpp
static bool System::BitConverter::ToBoolean(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) that contains bytes to convert |
| startIndex | int | Index in the array at which to start taking bytes for conversion |

### Return Value

[Boolean](../../boolean/) value resulting from conversion

## BitConverter::ToBoolean(const System::Details::ArrayView\<uint8_t\>\&, int) method


Converts one byte from the specified array starting at the specified index to boolean value.

```cpp
static bool System::BitConverter::ToBoolean(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView that contains bytes to convert |
| startIndex | int | Index in the array at which to start taking bytes for conversion |

### Return Value

[Boolean](../../boolean/) value resulting from conversion

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)