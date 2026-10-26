---
title: Parse()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นจำนวนเต็มบวก 32-bit ที่เทียบเท่า
type: docs
weight: 1
url: /th/system/uint32/parse/
---
## UInt32::Parse(const String\&) method

แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นจำนวนเต็มบวก 32 บิตที่เทียบเท่า

```cpp
static uint32_t System::UInt32::Parse(const String &value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่ต้องแปลง |

### ค่าที่ส่งกลับ

จำนวนเต็มบวก 32 บิตที่เท่ากับตัวเลขที่แสดงโดยสตริงที่ระบุ

## UInt32::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) method

แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นจำนวนเต็มบวก 32 บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบที่ระบุ

```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่ต้องแปลง |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | พอยน์เตอร์ไปยังอ็อบเจ็กต์ที่มีข้อมูลรูปแบบสตริง |

### ค่าที่ส่งกลับ

จำนวนเต็มบวก 32 บิตที่เท่ากับตัวเลขที่แสดงโดยสตริงที่ระบุ

## UInt32::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) method


```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt32::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method


```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt32::Parse(const String\&, std::nullptr_t) method


```cpp
static uint32_t System::UInt32::Parse(const String &value, std::nullptr_t)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method

แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นจำนวนเต็มบวก 32 บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ตัวเลขที่ระบุ

```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่ต้องแปลง |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | ค่าผสมแบบบิตของ enum NumberStyles ที่ระบุสไตล์ที่อนุญาตของการแสดงสตริงของตัวเลข |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | พอยน์เตอร์ไปยังอ็อบเจ็กต์ที่มีข้อมูลรูปแบบสตริง |

### ค่าที่ส่งกลับ

จำนวนเต็มบวก 32 บิตที่เท่ากับตัวเลขที่แสดงโดยสตริงที่ระบุ

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) method


```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method


```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) method


```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## ดูเพิ่มเติม

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* คลาส [String](../../string/)
* คลาส [IFormatProvider](../../iformatprovider/)
* คลาส [CultureInfo](../../../system.globalization/cultureinfo/)
* คลาส [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt32](../)
* เนมสเปซ [System](../../)
* Library [Aspose.Slides](../../../)