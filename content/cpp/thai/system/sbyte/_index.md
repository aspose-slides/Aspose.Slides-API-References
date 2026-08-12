---
title: SByte
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ประกอบด้วยเมธอดเพื่อทำงานกับจำนวนเต็ม 8 บิต.
type: docs
weight: 1873
url: /th/system/sbyte/
---
## SByte โครงสร้าง

ประกอบด้วยเมธอดเพื่อทำงานกับจำนวนเต็ม 8 บิต.

```cpp
class SByte
```

## เมธอด

| Method | Description |
| --- | --- |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&) | แปลงสตริงที่ระบุซึ่งมีการแสดงผลเป็นสตริงของตัวเลขให้เป็นจำนวนเต็มมีเครื่องหมาย 8 บิตที่เทียบเท่า |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่ระบุซึ่งมีการแสดงผลเป็นสตริงของตัวเลขให้เป็นจำนวนเต็มมีเครื่องหมาย 8 บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบที่ระบุ |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่ระบุซึ่งมีการแสดงผลเป็นสตริงของตัวเลขให้เป็นจำนวนเต็มมีเครื่องหมาย 8 บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ตัวเลขที่ระบุ |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int8_t**\&) | แปลงสตริงที่ระบุซึ่งมีการแสดงผลเป็นสตริงของตัวเลขให้เป็นจำนวนเต็มมีเครื่องหมาย 8 บิตที่เทียบเท่า |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int8_t**\&) | แปลงสตริงที่ระบุซึ่งมีการแสดงผลเป็นสตริงของตัวเลขให้เป็นจำนวนเต็มมีเครื่องหมาย 8 บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ตัวเลขที่ระบุ |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int8_t**\&) |  |

## ฟิลด์

| Field | Description |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | ค่าที่เป็นไปได้สูงสุด |
| static constexpr [MinValue](./minvalue/) | ค่าที่เป็นไปได้ต่ำสุด |

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)