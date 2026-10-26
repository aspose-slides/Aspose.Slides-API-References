---
title: TryParse()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นสตริงเป็นจำนวนเต็มบิตไม่เซ็น 8-bit ที่เทียบเท่า
type: docs
weight: 14
url: /th/system/byte/tryparse/
---
## Byte::TryParse(const String\&, uint8_t\&) method

แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นสตริงเป็นจำนวนเต็มบิตไม่เซ็น 8-bit ที่เทียบเท่า

```cpp
static bool System::Byte::TryParse(const String &value, uint8_t &result)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง |
| result | **uint8_t**\& | การอ้างอิงไปยังตัวแปรจำนวนเต็มบิตไม่เซ็น 8-bit ที่ผลลัพธ์ของการแปลงจะถูกเก็บไว้ |

### Return Value

True หากการแปลงสำเร็จ, มิฉะนั้น - false.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint8_t\&) method

แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นสตริงเป็นจำนวนเต็มบิตไม่เซ็น 8-bit โดยใช้ข้อมูลการจัดรูปแบบและรูปแบบตัวเลขที่ให้มา

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint8_t &result)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | การรวมค่าตามบิตของสมาชิกของ enum NumberStyles ที่ระบุรูปแบบที่อนุญาตของการแทนค่าสตริงของตัวเลข |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ตัวชี้ไปยังอ็อบเจ็กต์ที่บรรจุข้อมูลการจัดรูปแบบสตริง |
| result | **uint8_t**\& | การอ้างอิงไปยังตัวแปรจำนวนเต็มบิตไม่เซ็น 8-bit ที่ผลลัพธ์ของการแปลงจะถูกเก็บไว้ |

### Return Value

True หากการแปลงสำเร็จ, มิฉะนั้น - false.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint8_t\&) method




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint8_t\&) method




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint8_t\&) method




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint8_t &result)
```

## ดูเพิ่มเติม

* อนุกรม [NumberStyles](../../../system.globalization/numberstyles/)
* ประเภทนิยาม [SharedPtr](../../sharedptr/)
* คลาส [String](../../string/)
* คลาส [Byte](../)
* คลาส [IFormatProvider](../../iformatprovider/)
* คลาส [CultureInfo](../../../system.globalization/cultureinfo/)
* คลาส [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)