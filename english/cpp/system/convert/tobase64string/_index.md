---
title: ToBase64String()
second_title: Aspose.Slides for C++ API Reference
description: Base-64 encodes elements in the specified byte array and returns the encoded data as a string.
type: docs
weight: 40
url: /cpp/system/convert/tobase64string/
---
## Convert::ToBase64String(const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\&, **bool**) method


Base-64 encodes elements in the specified byte array and returns the encoded data as a string.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, bool insert_line_breaks=false)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | The array of bytes to encode |
| insert_line_breaks | **bool** | Specifies whether line break characters are to be inserted in the output string after every 76 base-64 characters |

### Return Value

The string containing the base-64 encoded representation of the input array

## See Also

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Convert::ToBase64String(const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\&, int, int, **bool**) method


Base-64 encodes a range of elements in the specified byte array and returns the encoded data as a string.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, bool insert_line_breaks=false)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | The array of bytes containing the range of elements to encode |
| offset_in | int | An index of an element in the input array at which the range to encode begins |
| length | int | The length of the range of elements to encode |
| insert_line_breaks | **bool** | Specifies whether line break characters are to be inserted in the output string after every 76 base-64 characters |

### Return Value

The string containing the base-64 encoded representation of the range of elements of the input array

## See Also

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Convert::ToBase64String(const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\&, [Base64FormattingOptions](../../base64formattingoptions/)) method


Base-64 encodes elements in the specified byte array and returns the encoded data as a string.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, Base64FormattingOptions options)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | The array of bytes to encode |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Specifies formatting options of base-64 encoded data |

### Return Value

The string containing the base-64 encoded representation of the input array

## See Also

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Convert::ToBase64String(const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\&, int, int, [Base64FormattingOptions](../../base64formattingoptions/)) method


Base-64 encodes a range of elements in the specified byte array and returns the encoded data as a string.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, Base64FormattingOptions options)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | The array of bytes containing the range of elements to encode |
| offset_in | int | An index of an element in the input array at which the range to encode begins |
| length | int | The length of the range of elements to encode |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Specifies formatting options of base-64 encoded data |

### Return Value

The string containing the base-64 encoded representation of the range of elements of the input array

## See Also

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
