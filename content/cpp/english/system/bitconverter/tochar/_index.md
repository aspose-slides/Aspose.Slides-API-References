---
title: ToChar()
second_title: Aspose.Slides for C++ API Reference
description: Converts two bytes from the specified array starting at the specified index to char_t value.
type: docs
weight: 40
url: /system/bitconverter/tochar/
---
## BitConverter::ToChar(const System::ArrayPtr\<uint8_t\>\&, int) method


Converts two bytes from the specified array starting at the specified index to char_t value.

```cpp
static char_t System::BitConverter::ToChar(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) that contains bytes to convert |
| startIndex | int | Index in the array at which to start taking bytes for conversion |

### Return Value

char_t value resulting from conversion

## BitConverter::ToChar(const System::Details::ArrayView\<uint8_t\>\&, int) method


Converts two bytes from the specified array starting at the specified index to char_t value.

```cpp
static char_t System::BitConverter::ToChar(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView that contains bytes to convert |
| startIndex | int | Index in the array at which to start taking bytes for conversion |

### Return Value

char_t value resulting from conversion

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)