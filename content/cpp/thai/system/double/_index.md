---
title: Double
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: มีเมธอดสำหรับทำงานกับตัวเลขแบบทศนิยมจุดลอยตัวความแม่นยำคู่
type: docs
weight: 1574
url: /th/system/double/
---
## โครงสร้าง Double

มีเมธอดสำหรับทำงานกับเลขแบบทศนิยมจุดลอยตัวความแม่นยำคู่

```cpp
class Double
```

## เมธอด

| Method | Description |
| --- | --- |
| static **double** [Parse](./parse/)(const [String](../string/)\&) | แปลงสตริงที่ระบุซึ่งบรรจุการแสดงผลของตัวเลขเป็นค่าจำนวนแบบ double-precision floating-point ที่เทียบเท่า |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่ระบุซึ่งบรรจุการแสดงผลของตัวเลขเป็นค่าจำนวนแบบ double-precision floating-point ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบที่ให้ไว้ |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่ระบุซึ่งบรรจุการแสดงผลของตัวเลขเป็นค่าจำนวนแบบ double-precision floating-point ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ของตัวเลขที่ให้ไว้ |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **double**\&) | แปลงสตริงที่ระบุซึ่งบรรจุการแสดงผลของตัวเลขเป็นค่าจำนวนแบบ double-precision floating-point ที่เทียบเท่า |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **double**\&) | แปลงสตริงที่ระบุซึ่งบรรจุการแสดงผลของตัวเลขเป็นค่าจำนวนแบบ double-precision floating-point ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ของตัวเลขที่ให้ไว้ |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **double**\&) |  |

## ฟิลด์

| Field | Description |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | ค่าบวกที่เล็กที่สุดที่มากกว่าศูนย์ |
| static constexpr [MaxValue](./maxvalue/) | ค่าที่ใหญ่ที่สุดที่เป็นไปได้ |
| static constexpr [MinValue](./minvalue/) | ค่าน้อยที่สุดที่เป็นไปได้ |
| static constexpr [NaN](./nan/) | ค่าที่ไม่ใช่ตัวเลข |
| static constexpr [NegativeInfinity](./negativeinfinity/) | อินฟินิตี้เชิงลบ |
| static constexpr [PositiveInfinity](./positiveinfinity/) | อินฟินิตี้เชิงบวก |

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)