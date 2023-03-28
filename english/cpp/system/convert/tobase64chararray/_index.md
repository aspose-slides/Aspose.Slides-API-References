---
title: ToBase64CharArray()
second_title: Aspose.Slides for C++ API Reference
description: Base-64 encodes a range of elements in the specified byte array and stores the encoded data as an array of Unicode characters.
type: docs
weight: 27
url: /cpp/system/convert/tobase64chararray/
---
## Convert::ToBase64CharArray(const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../../arrayptr/)\<char16_t\>\&, int, **bool**) method


Base-64 encodes a range of elements in the specified byte array and stores the encoded data as an array of Unicode characters.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char16_t> &out_array, int offset_out, bool insert_line_breaks=false)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | The array of bytes containing the range of elements to encode |
| offset_in | int | An index of an element in the input array at which the range to encode begins |
| length | int | The length of the range of elements to encode |
| out_array | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | A constant reference to the output array to which the resulting data is to be put |
| offset_out | int | An index in the output array at which to start putting the resulting data |
| insert_line_breaks | **bool** | Specifies whether the line break characters are to be inserted in the output array after every 76 base-64 characters |

### Return Value

The number of characters written to the output array

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Convert::ToBase64CharArray(const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../../arrayptr/)\<char_t\>\&, int, [Base64FormattingOptions](../../base64formattingoptions/)) method


Base-64 encodes a range of elements in the specified byte array and stores the encoded data as an array of Unicode characters.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char_t> &out_array, int offset_out, Base64FormattingOptions options)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | The array of bytes containing the range of elements to encode |
| offset_in | int | An index of an element in the input array at which the range to encode begins |
| length | int | The length of the range of elements to encode |
| out_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | A constant reference to the output array to which the resulting data is to be put |
| offset_out | int | An index in the output array at which to start putting the resulting data |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Specifies formatting options of base-64 encoded data |

### Return Value

The number of characters written to the output array

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
