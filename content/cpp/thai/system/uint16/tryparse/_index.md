---
title: TryParse()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขเป็นจำนวนเต็มบวก 16 บิตที่เทียบเท่า
type: docs
weight: 14
url: /th/system/uint16/tryparse/
---
## UInt16::TryParse(const String\&, uint16_t\&) method

แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขเป็นจำนวนเต็มบวก 16 บิตที่เทียบเท่า

```cpp
static bool System::UInt16::TryParse(const String &value, uint16_t &result)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่ต้องการแปลง |
| result | **uint16_t**\& | ตัวแปรจำนวนเต็มบวก 16 บิตที่ผลลัพธ์ของการแปลงจะถูกบันทึกไว้ |

### Return Value

True หากการแปลงสำเร็จ, มิฉะนั้น - false

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint16_t\&) method

แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขเป็นจำนวนเต็มบวก 16 บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ของตัวเลขที่ให้มา

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint16_t &result)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่ต้องการแปลง |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | การรวมค่าตามบิตของ enum NumberStyles ที่ระบุสไตล์ที่อนุญาตของการแสดงผลตัวเลข |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ตัวชี้ไปยังวัตถุที่มีข้อมูลรูปแบบสตริง |
| result | **uint16_t**\& | ตัวแปรจำนวนเต็มบวก 16 บิตที่ผลลัพธ์ของการแปลงจะถูกบันทึกไว้ |

### Return Value

True หากการแปลงสำเร็จ, มิฉะนั้น - false

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint16_t\&) method




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint16_t\&) method




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint16_t\&) method




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint16_t &result)
```

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt16](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)