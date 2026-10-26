---
title: UInt64
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: มีเมธอดสำหรับทำงานกับจำนวนเต็มแบบไม่มีเครื่องหมาย 64 บิต
type: docs
weight: 1990
url: /th/system/uint64/
---
## UInt64 struct

Contains methods to work with the unsigned 64-bit integer.

```cpp
class UInt64
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&) | แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขเป็นสตริงให้เป็นจำนวนเต็มแบบไม่มีเครื่องหมาย 64 บิตที่เทียบเท่า |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขเป็นสตริงให้เป็นจำนวนเต็มแบบไม่มีเครื่องหมาย 64 บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบที่ให้ไว้ |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขเป็นสตริงให้เป็นจำนวนเต็มแบบไม่มีเครื่องหมาย 64 บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ตัวเลขที่ให้ไว้ |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint64_t**\&) | แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขเป็นสตริงให้เป็นจำนวนเต็มแบบไม่มีเครื่องหมาย 64 บิตที่เทียบเท่า |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint64_t**\&) | แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขเป็นสตริงให้เป็นจำนวนเต็มแบบไม่มีเครื่องหมาย 64 บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ตัวเลขที่ให้ไว้ |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint64_t**\&) |  |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | ค่าที่ใหญ่ที่สุดที่เป็นไปได้ |
| static constexpr [MinValue](./minvalue/) | ค่าที่เล็กที่สุดที่เป็นไปได้ |

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)