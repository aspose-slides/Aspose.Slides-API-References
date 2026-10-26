---
title: Parse()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แปลงสตริงที่ระบุซึ่งมีการแสดงผลของจำนวนให้เป็นค่าลอยจุดความแม่นยำคู่ที่เทียบเท่า
type: docs
weight: 1
url: /th/system/double/parse/
---
## Double::Parse(const String\&) method

แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขให้เป็นค่า floating-point ความแม่นยำคู่ที่เท่ากับค่าในสตริง

```cpp
static double System::Double::Parse(const String &value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง |

### ค่าที่คืนกลับ

ค่าที่เป็น floating-point ความแม่นยำคู่ที่เท่ากับตัวเลขที่แสดงในสตริงที่ระบุ

## Double::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) method

แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขให้เป็นค่า floating-point ความแม่นยำคู่โดยใช้ข้อมูลการจัดรูปแบบที่ให้มา

```cpp
static double System::Double::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | พอยน์เตอร์ไปยังอ็อบเจ็กต์ที่มีข้อมูลรูปแบบสตริง |

### ค่าที่คืนกลับ

ค่าที่เป็น floating-point ความแม่นยำคู่ที่เท่ากับตัวเลขที่แสดงในสตริงที่ระบุ

## Double::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, std::nullptr_t) method




```cpp
static double System::Double::Parse(const String &value, std::nullptr_t)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method

แปลงสตริงที่ระบุซึ่งมีการแสดงผลของตัวเลขให้เป็นค่า floating-point ความแม่นยำคู่โดยใช้ข้อมูลการจัดรูปแบบและสไตล์ตัวเลขที่ให้มา

```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | การรวมค่าแบบบิตของ enum NumberStyles ที่ระบุตัวเลือกสไตล์ที่อนุญาตสำหรับการแสดงผลของตัวเลขในสตริง |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | พอยน์เตอร์ไปยังอ็อบเจ็กต์ที่มีข้อมูลรูปแบบสตริง |

### ค่าที่คืนกลับ

ค่าที่เป็น floating-point ความแม่นยำคู่ที่เท่ากับตัวเลขที่แสดงในสตริงที่ระบุ

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) method




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## ดูเพิ่มเติม

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Double](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)