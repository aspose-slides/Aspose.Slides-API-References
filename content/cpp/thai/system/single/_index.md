---
title: Single
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ประกอบด้วยเมธอดเพื่อทำงานกับตัวเลขทศนิยมแบบความแม่นยำเดี่ยว
type: docs
weight: 1899
url: /th/system/single/
---
## โครงสร้างเดี่ยว

มีเมธอดเพื่อทำงานกับตัวเลขทศนิยมแบบความแม่นยำเดี่ยว.

```cpp
class Single
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| static **float** [Parse](./parse/)(const [String](../string/)\&) | แปลงสตริงที่กำหนดซึ่งมีการแทนค่าตัวเลขเป็นค่า floating-point แบบความแม่นยำเดี่ยวที่เทียบเท่า |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่กำหนดซึ่งมีการแทนค่าตัวเลขเป็นค่า floating-point แบบความแม่นยำเดี่ยวที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบที่ให้มา |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่กำหนดซึ่งมีการแทนค่าตัวเลขเป็นค่า floating-point แบบความแม่นยำเดี่ยวที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ตัวเลขที่ให้มา |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **float**\&) | แปลงสตริงที่กำหนดซึ่งมีการแทนค่าตัวเลขเป็นค่า floating-point แบบความแม่นยำเดี่ยวที่เทียบเท่า |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **float**\&) | แปลงสตริงที่กำหนดซึ่งมีการแทนค่าตัวเลขเป็นค่า floating-point แบบความแม่นยำเดี่ยวที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ตัวเลขที่ให้มา |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **float**\&) |  |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | ค่าบวกที่เล็กที่สุดที่มากกว่าศูนย์ |
| static constexpr [MaxValue](./maxvalue/) | ค่าสูงสุดที่เป็นไปได้ |
| static constexpr [MinValue](./minvalue/) | ค่าต่ำสุดที่เป็นไปได้ |
| static constexpr [NaN](./nan/) | ค่าที่ไม่ใช่ตัวเลข |
| static constexpr [NegativeInfinity](./negativeinfinity/) | ลบอนันต์ |
| static constexpr [PositiveInfinity](./positiveinfinity/) | บวกอนันต์ |

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)