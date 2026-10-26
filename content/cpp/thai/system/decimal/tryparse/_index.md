---
title: TryParse()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แปลงสตริงที่ระบุซึ่งประกอบด้วยการแสดงผลของตัวเลขให้เป็นค่า Decimal ที่เทียบเท่า
type: docs
weight: 482
url: /th/system/decimal/tryparse/
---
## Decimal::TryParse(const String\&, Decimal\&) เมธอด

แปลงสตริงที่ระบุซึ่งประกอบด้วยการแสดงผลของตัวเลขเป็นค่าที่เทียบเท่า [Decimal](../) value

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง |
| result | [Decimal](../)\& | อ้างอิงถึงตัวแปร [Decimal](../) ที่ผลลัพธ์ของการแปลงจะถูกเก็บไว้ |

### Return Value

true หากการแปลงสำเร็จ, มิฉะนั้น - false

## Decimal::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) เมธอด

แปลงสตริงที่ระบุซึ่งประกอบด้วยการแสดงผลของตัวเลขเป็นค่าที่เทียบเท่า [Decimal](../) โดยใช้ข้อมูลการจัดรูปแบบและรูปแบบตัวเลขที่ให้มา

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | การรวมค่าตามบิตของ enum NumberStyles ที่ระบุรูปแบบที่อนุญาตของการแสดงผลของตัวเลข |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ตัวชี้ไปยังอ็อบเจ็กต์ที่บรรจุข้อมูลรูปแบบสตริง |
| result | [Decimal](../)\& | อาร์กิวเมนต์ผลลัพธ์; ประกอบด้วยผลลัพธ์ของการแปลง |

### Return Value

true หากการแปลงสำเร็จ, มิฉะนั้น - false

## ดูเพิ่มเติม

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* คลาส [String](../../string/)
* คลาส [Decimal](../)
* คลาส [IFormatProvider](../../iformatprovider/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)