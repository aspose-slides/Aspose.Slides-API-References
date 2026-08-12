---
title: Parse()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แปลงการแทนค่าข้อความของตัวเลขทศนิยมให้เป็นอินสแตนซ์ที่เทียบเท่าของคลาส Decimal.
type: docs
weight: 469
url: /th/system/decimal/parse/
---
## Decimal::Parse(const String\&) เมธอด

แปลงการแทนค่าข้อความของตัวเลขทศนิยมให้เป็นอินสแตนซ์ที่เทียบเท่าของคลาส [Decimal](../).

```cpp
static Decimal System::Decimal::Parse(const String &s)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | การแทนค่าข้อความของตัวเลข |

### ค่าที่คืน

อินสแตนซ์ใหม่ของคลาส [Decimal](../) ที่แสดงค่าที่เทียบเท่ากับค่าที่แสดงโดยสตริงที่ระบุ

## Decimal::Parse(const String\&, Globalization::NumberStyles) เมธอด

แปลงการแทนค่าข้อความของตัวเลขทศนิยมให้เป็นอินสแตนซ์ที่เทียบเท่าของคลาส [Decimal](../) โดยใช้รูปแบบที่ระบุ.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | การแทนค่าข้อความของค่าทศนิยมที่จะแปลง |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | การผสมแบบบิตวายซ์ของค่าตัวเลขใน enumeration ที่ให้ข้อมูลเพิ่มเติมเกี่ยวกับ **s**, เกี่ยวกับส่วนของรูปแบบที่อาจปรากฎใน **s**, หรือเกี่ยวกับการแปลงจาก **s** เป็นวัตถุ [Decimal](../) |

### ค่าที่คืน

อินสแตนซ์ใหม่ของคลาส [Decimal](../) ที่แสดงค่าที่เทียบเท่ากับค่าที่แสดงโดยสตริงที่ระบุ

## Decimal::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) เมธอด

แปลงการแทนค่าข้อความของตัวเลขทศนิยมให้เป็นอินสแตนซ์ที่เทียบเท่าของคลาส [Decimal](../) โดยใช้ผู้ให้รูปแบบที่ระบุ.

```cpp
static Decimal System::Decimal::Parse(const String &s, const SharedPtr<IFormatProvider> &provider)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | การแทนค่าข้อความของค่าทศนิยมที่จะแปลง |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ผู้ให้รูปแบบ |

### ค่าที่คืน

อินสแตนซ์ใหม่ของคลาส [Decimal](../) ที่แสดงค่าที่เทียบเท่ากับค่าที่แสดงโดยสตริงที่ระบุ

## Decimal::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) เมธอด

แปลงการแทนค่าข้อความของตัวเลขทศนิยมให้เป็นอินสแตนซ์ที่เทียบเท่ของคลาส [Decimal](../) โดยใช้รูปแบบและผู้ให้รูปแบบที่ระบุ.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | การแทนค่าข้อความของค่าทศนิยมที่จะแปลง |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | การผสมแบบบิตวายซ์ของค่าตัวเลขใน enumeration ที่ให้ข้อมูลเพิ่มเติมเกี่ยวกับ **s**, เกี่ยวกับส่วนของรูปแบบที่อาจปรากฎใน **s**, หรือเกี่ยวกับการแปลงจาก **s** เป็นวัตถุ [Decimal](../) |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ผู้ให้รูปแบบ |

### ค่าที่คืน

อินสแตนซ์ใหม่ของคลาส [Decimal](../) ที่แสดงค่าที่เทียบเท่ากับค่าที่แสดงโดยสตริงที่ระบุ

## ดูเพิ่มเติม

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)