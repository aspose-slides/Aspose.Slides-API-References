---
title: ToString()
second_title: Aspose.Slides for C++ API Reference
description: Converts all values of the specified byte array into their hexadecimal string representation. Case of letters to use in hexadecimal notation and separator inserted between each pair of neighbouring bytes are specified through corresponding arguments.
type: docs
weight: 157
url: /cpp/system/bitconverter/tostring/
---
## BitConverter::ToString(const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\&, **bool**, const [String](../../string/)\&) method


Converts all values of the specified byte array into their hexadecimal string representation. Case of letters to use in hexadecimal notation and separator inserted between each pair of neighbouring bytes are specified through corresponding arguments.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, bool uppercase=1, const String &separator=u"-")
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) that contains bytes to convert |
| uppercase | **bool** | Specifies the case of letters to use in resulting hexadecimal representation |
| separator | const [String](../../string/)\& | A string used as a separator inserted between each pair of neighbouring bytes in the resulting string |

### Return Value

[String](../../string/) containing hexadecimal representation of the specified byte array

## See Also

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## BitConverter::ToString(const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\&, int) method


Converts values of the specified byte array into their hexadecimal string representation starting at specified index.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) that contains bytes to convert |
| startIndex | int | Index in the specified array at which to start converting |

### Return Value

[String](../../string/) containing hexadecimal representation of the specified range of elements of the specified array

## See Also

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## BitConverter::ToString(const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\&, int, int) method


Converts a range of values of the specified byte array into their hexadecimal string representation.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex, int length)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) that contains bytes to convert |
| startIndex | int | Index in the specified array at which the range of the byte array elements to convert begins |
| length | int | The length of the range the byte array elements to convert |

### Return Value

[String](../../string/) containing hexadecimal representation of the specified range of elements of the specified array

## See Also

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
