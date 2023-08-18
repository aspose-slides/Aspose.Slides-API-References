---
title: BitConverter
second_title: Aspose.Slides for C++ API Reference
description: Contains methods that perform conversions of sequence of bytes to a value type and vice-versa. This is a static type with no instance services. You should never create instances of it by any means.
type: docs
weight: 40
url: /system/bitconverter/
---
## BitConverter class


Contains methods that perform conversions of sequence of bytes to a value type and vice-versa. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class BitConverter
```

## Methods

| Method | Description |
| --- | --- |
| static **bool** [_IsLittleEndian](./_islittleendian/)() | Indicates the endianness of the current architecture. |
| static **int64_t** [DoubleToInt64Bits](./doubletoint64bits/)(**double**) | Returns a 64-bit integer value whose binary representation is equal to binary representation of the specified double-precision floating point value. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**bool**) | Converts the specified boolean value into an array of bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(char_t) | Converts the specified char_t value into an array of bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int16_t**) | Converts the specified 16-bit integer value into an array of bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(int) | Converts the specified 32-bit integer value into an array of bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int64_t**) | Converts the specified 64-bit integer value into an array of bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint16_t**) | Converts the specified unsigned 16-bit integer value into an array of bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint32_t**) | Converts the specified unsigned 32-bit integer value into an array of bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint64_t**) | Converts the specified unsigned 64-bit integer value into an array of bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**float**) | Converts the specified single-precision floating-point value into an array of bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**double**) | Converts the specified double-precision floating-point value into an array of bytes. |
| static **double** [Int64BitsToDouble](./int64bitstodouble/)(**int64_t**) | Returns a double-precision floating point value whose value is equivalent to value. |
| static **bool** [ToBoolean](./toboolean/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converts one byte from the specified array starting at the specified index to boolean value. |
| static **bool** [ToBoolean](./toboolean/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converts one byte from the specified array starting at the specified index to boolean value. |
| static char_t [ToChar](./tochar/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converts two bytes from the specified array starting at the specified index to char_t value. |
| static char_t [ToChar](./tochar/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converts two bytes from the specified array starting at the specified index to char_t value. |
| static **double** [ToDouble](./todouble/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converts eight bytes from the specified array starting at the specified index to double-precision floating point value. |
| static **double** [ToDouble](./todouble/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converts eight bytes from the specified array starting at the specified index to double-precision floating point value. |
| static **int16_t** [ToInt16](./toint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converts two bytes from the specified array starting at the specified index to 16-bit integer value. |
| static **int16_t** [ToInt16](./toint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converts two bytes from the specified array starting at the specified index to 16-bit integer value. |
| static int [ToInt32](./toint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converts four bytes from the specified array starting at the specified index to 32-bit integer value. |
| static int [ToInt32](./toint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converts four bytes from the specified array starting at the specified index to 32-bit integer value. |
| static **int64_t** [ToInt64](./toint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converts eight bytes from the specified array starting at the specified index to 64-bit integer value. |
| static **int64_t** [ToInt64](./toint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converts eight bytes from the specified array starting at the specified index to 64-bit integer value. |
| static **float** [ToSingle](./tosingle/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converts four bytes from the specified array starting at the specified index to single-precision floating point value. |
| static **float** [ToSingle](./tosingle/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converts four bytes from the specified array starting at the specified index to single-precision floating point value. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**, const [String](../string/)\&) | Converts all values of the specified byte array into their hexadecimal string representation. Case of letters to use in hexadecimal notation and separator inserted between each pair of neighbouring bytes are specified through corresponding arguments. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converts values of the specified byte array into their hexadecimal string representation starting at specified index. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int) | Converts a range of values of the specified byte array into their hexadecimal string representation. |
| static **uint16_t** [ToUInt16](./touint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converts two bytes from the specified array starting at the specified index to unsigned 16-bit integer value. |
| static **uint16_t** [ToUInt16](./touint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converts two bytes from the specified array starting at the specified index to unsigned 16-bit integer value. |
| static **uint32_t** [ToUInt32](./touint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converts four bytes from the specified array starting at the specified index to unsigned 32-bit integer value. |
| static **uint32_t** [ToUInt32](./touint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converts four bytes from the specified array starting at the specified index to unsigned 32-bit integer value. |
| static **uint64_t** [ToUInt64](./touint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converts eight bytes from the specified array starting at the specified index to unsigned 64-bit integer value. |
| static **uint64_t** [ToUInt64](./touint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converts eight bytes from the specified array starting at the specified index to unsigned 64-bit integer value. |
## Fields

| Field | Description |
| --- | --- |
| static [IsLittleEndian](./islittleendian/) | Indicates the endianness of the current architecture. true if the architecture is little endian, false otherwise. |
## Remarks



```cpp
#include <system/bit_converter.h>
#include <system/smart_ptr.h>

using namespace System;

template <typename T>
void Print(T arg)
{
  std::cout << arg << ' ';

  for (const auto byte: BitConverter::GetBytes(arg))
  {
    std::cout << std::hex << static_cast<int>(byte);
  }

  std::cout << std::endl;
}

int main()
{
  // Create values to print.
  int anInt = 1234567890;
  double aDouble = 0.123456789;

  // Print value and its bytes.
  Print(anInt);
  Print(aDouble);

  return 0;
}
/*
This code example produces the following output:
1234567890 d229649
0.123457 5f633937dd9abf3f
*/
```

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)