---
title: TryParse()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นสตริงให้เป็นจำนวนเต็ม signed 64-bit ที่เทียบเท่า
type: docs
weight: 14
url: /th/system/int64/tryparse/
---
## Int64::TryParse(const String\&, int64_t\&) เมธอด


แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นสตริงให้เป็นจำนวนเต็มแบบ signed 64-bit ที่เทียบเท่า

```cpp
static bool System::Int64::TryParse(const String &value, int64_t &result)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง |
| result | **int64_t**\& | การอ้างอิงไปยังตัวแปรจำนวนเต็มแบบ signed 64-bit ซึ่งผลลัพธ์ของการแปลงจะถูกเก็บไว้ |

### ค่าที่ส่งกลับ

True if the conversion succeeded, otherwise - false.

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int64_t\&) เมธอด


แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นสตริงให้เป็นจำนวนเต็มแบบ signed 64-bit ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ของตัวเลขที่ระบุ

```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int64_t &result)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | การรวมแบบบิตวายส์ของค่าใน enum NumberStyles ที่ระบุรูปแบบที่ยอมรับของสตริงที่แทนค่าตัวเลข |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | พอยน์เตอร์ไปยังอ็อบเจ็กต์ที่มีข้อมูลการจัดรูปแบบสตริง |
| result | **int64_t**\& | การอ้างอิงไปยังตัวแปรจำนวนเต็มแบบ signed 64-bit ซึ่งผลลัพธ์ของการแปลงจะถูกเก็บไว้ |

### ค่าที่ส่งกลับ

True if the conversion succeeded, otherwise - false.

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int64_t\&) เมธอด




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int64_t\&) เมธอด




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int64_t\&) เมธอด




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int64_t &result)
```

## ดูเพิ่มเติม

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* คลาส [String](../../string/)
* คลาส [Int64](../)
* คลาส [IFormatProvider](../../iformatprovider/)
* คลาส [CultureInfo](../../../system.globalization/cultureinfo/)
* คลาส [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* เนมสเปซ [System](../../)
* Library [Aspose.Slides](../../../)