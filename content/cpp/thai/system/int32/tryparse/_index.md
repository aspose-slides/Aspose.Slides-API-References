---
title: TryParse()
second_title: Aspose.Slides สำหรับ C++ – เอกสารอ้างอิง API
description: แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นจำนวนเต็มลายเซ็นต์ 32-bit ที่เทียบเท่า
type: docs
weight: 14
url: /th/system/int32/tryparse/
---
## Int32::TryParse(const String\&, int32_t\&) method


แปลงสตริงที่ระบุซึ่งมีการแทนค่าเป็นตัวเลขเป็นจำนวนเต็มลายเซ็นต์ 32-บิตที่เทียบเท่า

```cpp
static bool System::Int32::TryParse(const String &value, int32_t &result)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง |
| result | **int32_t**\& | ตัวแปรจำนวนเต็มลายเซ็นต์ 32-บิตที่ผลลัพธ์ของการแปลงจะถูกเก็บไว้ |

### ค่าที่ส่งกลับ

True หากการแปลงสำเร็จ, มิฉะนั้น - false.

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int32_t\&) method


แปลงสตริงที่ระบุซึ่งมีการแทนค่าเป็นตัวเลขเป็นจำนวนเต็มลายเซ็นต์ 32-บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ตัวเลขที่ให้มา

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int32_t &result)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | การรวมค่าแบบบิตของ NumberStyles enum ที่ระบุสไตล์ที่อนุญาตของการแทนค่าเป็นสตริงของตัวเลข |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ตัวชี้ไปยังวัตถุที่มีข้อมูลการจัดรูปแบบสตริง |
| result | **int32_t**\& | ตัวแปรจำนวนเต็มลายเซ็นต์ 32-บิตที่ผลลัพธ์ของการแปลงจะถูกเก็บไว้ |

### ค่าที่ส่งกลับ

True หากการแปลงสำเร็จ, มิฉะนั้น - false.

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int32_t\&) method




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int32_t\&) method




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int32_t\&) method




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int32_t &result)
```

## ดูเพิ่มเติม

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int32](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)