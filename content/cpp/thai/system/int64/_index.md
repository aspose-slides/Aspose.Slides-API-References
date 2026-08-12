---
title: Int64
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: มีเมธอดเพื่อทำงานกับจำนวนเต็ม 64-bit.
type: docs
weight: 1054
url: /th/system/int64/
---
## Int64 คลาส

มีเมธอดเพื่อทำงานกับจำนวนเต็ม 64 บิต.

```cpp
class Int64
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&) | แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขเป็นสตริงเป็นจำนวนเต็มแบบ signed 64-bit ที่เทียบเท่า. |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขเป็นสตริงเป็นจำนวนเต็มแบบ signed 64-bit ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบที่ให้ไว้. |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขเป็นสตริงเป็นจำนวนเต็มแบบ signed 64-bit ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ของตัวเลขที่ให้ไว้. |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int64_t**\&) | แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขเป็นสตริงเป็นจำนวนเต็มแบบ signed 64-bit ที่เทียบเท่า. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int64_t**\&) | แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขเป็นสตริงเป็นจำนวนเต็มแบบ signed 64-bit ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ของตัวเลขที่ให้ไว้. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int64_t**\&) |  |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | ค่าที่ใหญ่ที่สุดที่เป็นไปได้. |
| static constexpr [MinValue](./minvalue/) | ค่าที่เล็กที่สุดที่เป็นไปได้. |

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)