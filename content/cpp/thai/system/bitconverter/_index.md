---
title: BitConverter
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: มีเมธอดที่ทำการแปลงลำดับของไบต์เป็นชนิดค่าต่าง ๆ และกลับกัน. นี่เป็นชนิดแบบสแตติกที่ไม่มีบริการอินสแตนซ์. คุณไม่ควรสร้างอินสแตนซ์ของมันด้วยวิธีใด ๆ.
type: docs
weight: 66
url: /th/system/bitconverter/
---
## BitConverter คลาส


มีเมธอดที่ทำการแปลงลำดับของไบต์เป็นชนิดค่าและกลับกัน นี่เป็นประเภทแบบสแตติกที่ไม่มีบริการอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันด้วยวิธีใด ๆ

```cpp
class BitConverter
```

## เมธอด

| Method | Description |
| --- | --- |
| static **bool** [_IsLittleEndian](./_islittleendian/)() | ระบุลำดับไบต์ของสถาปัตยกรรมปัจจุบัน |
| static **int64_t** [DoubleToInt64Bits](./doubletoint64bits/)(**double**) | คืนค่าจำนวนเต็ม 64 บิตที่การแสดงผลไบนารีเท่ากับการแสดงผลไบนารีของค่า double-precision floating point ที่ระบุ |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**bool**) | แปลงค่า boolean ที่ระบุเป็นอาร์เรย์ของไบต์ |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(char_t) | แปลงค่า char_t ที่ระบุเป็นอาร์เรย์ของไบต์ |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int16_t**) | แปลงค่าเต็ม 16 บิตที่ระบุเป็นอาร์เรย์ของไบต์ |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(int) | แปลงค่าเต็ม 32 บิตที่ระบุเป็นอาร์เรย์ของไบต์ |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int64_t**) | แปลงค่าเต็ม 64 บิตที่ระบุเป็นอาร์เรย์ของไบต์ |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint16_t**) | แปลงค่า unsigned 16 บิตที่ระบุเป็นอาร์เรย์ของไบต์ |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint32_t**) | แปลงค่า unsigned 32 บิตที่ระบุเป็นอาร์เรย์ของไบต์ |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint64_t**) | แปลงค่า unsigned 64 บิตที่ระบุเป็นอาร์เรย์ของไบต์ |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**float**) | แปลงค่า single-precision floating-point ที่ระบุเป็นอาร์เรย์ของไบต์ |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**double**) | แปลงค่า double-precision floating-point ที่ระบุเป็นอาร์เรย์ของไบต์ |
| static **double** [Int64BitsToDouble](./int64bitstodouble/)(**int64_t**) | คืนค่าดับเบิล-พรีซิชัน floating point ที่ค่ามีความเทียบเท่ากับค่า |
| static **bool** [ToBoolean](./toboolean/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | แปลงไบต์หนึ่งจากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุเป็นค่า boolean |
| static **bool** [ToBoolean](./toboolean/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | แปลงไบต์หนึ่งจากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุเป็นค่า boolean |
| static char_t [ToChar](./tochar/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | แปลงสองไบต์จากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุเป็นค่า char_t |
| static char_t [ToChar](./tochar/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | แปลงสองไบต์จากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุเป็นค่า char_t |
| static **double** [ToDouble](./todouble/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | แปลงแปดไบต์จากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุเป็นค่า double-precision floating point |
| static **double** [ToDouble](./todouble/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | แปลงแปดไบต์จากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุเป็นค่า double-precision floating point |
| static **int16_t** [ToInt16](./toint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | แปลงสองไบต์จากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุเป็นค่าจำนวนเต็ม 16 บิต |
| static **int16_t** [ToInt16](./toint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | แปลงสองไบต์จากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุเป็นค่าจำนวนเต็ม 16 บิต |
| static int [ToInt32](./toint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | แปลงสี่ไบต์จากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุเป็นค่าจำนวนเต็ม 32 บิต |
| static int [ToInt32](./toint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | แปลงสี่ไบต์จากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุเป็นค่าจำนวนเต็ม 32 บิต |
| static **int64_t** [ToInt64](./toint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | แปลงแปดไบต์จากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุเป็นค่าจำนวนเต็ม 64 บิต |
| static **int64_t** [ToInt64](./toint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | แปลงแปดไบต์จากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุเป็นค่าจำนวนเต็ม 64 บิต |
| static **float** [ToSingle](./tosingle/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | แปลงสี่ไบต์จากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุเป็นค่า single-precision floating point |
| static **float** [ToSingle](./tosingle/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | แปลงสี่ไบต์จากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุเป็นค่า single-precision floating point |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**, const [String](../string/)\&) | แปลงค่าทั้งหมดของอาร์เรย์ไบต์ที่ระบุเป็นสตริงแทนค่าในรูปแบบเลขฐานสิบหก ตัวอักษรตัวพิมพ์ใหญ่หรือพิมพ์เล็กที่ใช้ในรูปแบบฐานสิบหกและตัวคั่นที่แทรกระหว่างแต่ละคู่ของไบต์ที่อยู่ติดกันจะระบุผ่านอาร์กิวเมนต์ที่สอดคล้องกัน |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | แปลงค่าของอาร์เรย์ไบต์ที่ระบุเป็นสตริงแทนค่าในรูปแบบเลขฐานสิบหกโดยเริ่มที่ดัชนีที่ระบุ |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int) | แปลงช่วงค่าของอาร์เรย์ไบต์ที่ระบุเป็นสตริงแทนค่าในรูปแบบเลขฐานสิบหก |
| static **uint16_t** [ToUInt16](./touint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | แปลงสองไบต์จากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุเป็นค่าตัวเลข unsigned 16 บิต |
| static **uint16_t** [ToUInt16](./touint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | แปลงสองไบต์จากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุเป็นค่าตัวเลข unsigned 16 บิต |
| static **uint32_t** [ToUInt32](./touint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | แปลงสี่ไบต์จากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุเป็นค่าตัวเลข unsigned 32 บิต |
| static **uint32_t** [ToUInt32](./touint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | แปลงสี่ไบต์จากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุเป็นค่าตัวเลข unsigned 32 บิต |
| static **uint64_t** [ToUInt64](./touint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | แปลงแปดไบต์จากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุเป็นค่าตัวเลข unsigned 64 บิต |
| static **uint64_t** [ToUInt64](./touint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | แปลงแปดไบต์จากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุเป็นค่าตัวเลข unsigned 64 บิต |

## ฟิลด์

| Field | Description |
| --- | --- |
| static [IsLittleEndian](./islittleendian/) | ระบุลำดับไบต์ของสถาปัตยกรรมปัจจุบัน ค่าจะเป็น true หากสถาปัตยกรรมเป็น little endian, false ในกรณีอื่น |

## หมายเหตุ



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
  // สร้างค่าที่จะพิมพ์.
  int anInt = 1234567890;
  double aDouble = 0.123456789;

  // พิมพ์ค่าและไบต์ของมัน.
  Print(anInt);
  Print(aDouble);

  return 0;
}
/*
ตัวอย่างโค้ดนี้สร้างผลลัพธ์ต่อไปนี้:
1234567890 d229649
0.123457 5f633937dd9abf3f
*/
```

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)