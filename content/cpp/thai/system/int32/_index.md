---
title: Int32
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: มีเมธอดสำหรับทำงานกับจำนวนเต็ม 32-บิต.
type: docs
weight: 1041
url: /th/system/int32/
---
## Int32 คลาส

มีเมธอดสำหรับทำงานกับจำนวนเต็ม 32-บิต.

```cpp
class Int32
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&) | แปลงสตริงที่กำหนดซึ่งมีการแสดงผลของตัวเลขเป็นจำนวนเต็ม 32-บิตที่มีเครื่องหมายเท่ากัน. |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่กำหนดซึ่งมีการแสดงผลของตัวเลขเป็นจำนวนเต็ม 32-บิตที่มีเครื่องหมายโดยใช้ข้อมูลการจัดรูปแบบที่ให้มา. |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่กำหนดซึ่งมีการแสดงผลของตัวเลขเป็นจำนวนเต็ม 32-บิตที่มีเครื่องหมายโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ตัวเลขที่ให้มา. |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [Parse](./parse/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&, std::nullptr_t) |  |
| static **int32_t** [Parse](./parse/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int32_t**\&) | แปลงสตริงที่กำหนดซึ่งมีการแสดงผลของตัวเลขเป็นจำนวนเต็ม 32-บิตที่มีเครื่องหมาย. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int32_t**\&) | แปลงสตริงที่กำหนดซึ่งมีการแสดงผลของตัวเลขเป็นจำนวนเต็ม 32-บิตที่มีเครื่องหมายโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ตัวเลขที่ให้มา. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int32_t**\&) |  |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | ค่าที่เป็นไปได้มากที่สุด. |
| static constexpr [MinValue](./minvalue/) | ค่าที่เป็นไปได้น้อยที่สุด. |

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)