---
title: Byte
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: มีเมธอดสำหรับทำงานกับจำนวนเต็มบวกแบบ 8 บิตที่ไม่มีเครื่องหมาย.
type: docs
weight: 157
url: /th/system/byte/
---
## คลาส Byte

มีเมธอดสำหรับทำงานกับจำนวนเต็มบวกแบบ 8 บิตที่ไม่มีเครื่องหมาย.

```cpp
class Byte
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&) | แปลงสตริงที่ระบุซึ่งมีการแทนค่าเป็นสตริงของตัวเลขให้เป็นจำนวนเต็มบวกแบบ 8 บิตที่เท่ากัน |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่ระบุซึ่งมีการแทนค่าเป็นสตริงของตัวเลขให้เป็นจำนวนเต็มบวกแบบ 8 บิตที่เท่ากันโดยใช้ข้อมูลการจัดรูปแบบที่ให้ไว้ |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่ระบุซึ่งมีการแทนค่าเป็นสตริงของตัวเลขให้เป็นจำนวนเต็มบวกแบบ 8 บิตที่เท่ากันโดยใช้ข้อมูลการจัดรูปแบบและรูปแบบตัวเลขที่ให้ไว้ |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint8_t**\&) | แปลงสตริงที่ระบุซึ่งมีการแทนค่าเป็นสตริงของตัวเลขให้เป็นจำนวนเต็มบวกแบบ 8 บิตที่เท่ากัน |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint8_t**\&) | แปลงสตริงที่ระบุซึ่งมีการแทนค่าเป็นสตริงของตัวเลขให้เป็นจำนวนเต็มบวกแบบ 8 บิตที่เท่ากันโดยใช้ข้อมูลการจัดรูปแบบและรูปแบบตัวเลขที่ให้ไว้ |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint8_t**\&) |  |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | ค่ามากที่สุดที่เป็นไปได้ |
| static constexpr [MinValue](./minvalue/) | ค่าน้อยที่สุดที่เป็นไปได้ |

## หมายเหตุ



```cpp
#include <system/byte.h>

using namespace System;

int main()
{
  auto b1 = Byte::Parse(u"123");
  std::cout << static_cast<uint32_t>(b1) << std::endl;

  try
  {
    auto b2 = Byte::Parse(u"345");
    std::cout << static_cast<uint32_t>(b2) << std::endl;
  }
  catch (const OverflowException &ex)
  {
    std::cerr << ex.what() << std::endl;
  }

  uint8_t b3 = 0;
  if (Byte::TryParse(u"10", b3))
  {
    std::cout << static_cast<uint32_t>(b3) << std::endl;
  }
  else
  {
    std::cerr << "Something went wrong." << std::endl;
  }

  return 0;
}
/*
ตัวอย่างโค้ดนี้แสดงผลลัพธ์ต่อไปนี้:
123
System::OverflowException: ค่าใหญ่เกินหรือเล็กเกินสำหรับ UInt8
10
*/
```

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)