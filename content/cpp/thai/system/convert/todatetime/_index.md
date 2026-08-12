---
title: ToDateTime()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: การแปลงไม่ได้รับการสนับสนุน. จะทำให้เกิด InvalidCastException เสมอ.
type: docs
weight: 248
url: /th/system/convert/todatetime/
---
## Convert::ToDateTime(bool) เมธอด


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(bool value)
```

## Convert::ToDateTime(uint8_t) เมธอด


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint8_t value)
```

## Convert::ToDateTime(int8_t) เมธอด


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int8_t value)
```

## Convert::ToDateTime(uint16_t) เมธอด


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint16_t value)
```

## Convert::ToDateTime(int16_t) เมธอด


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int16_t value)
```

## Convert::ToDateTime(uint32_t) เมธอด


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint32_t value)
```

## Convert::ToDateTime(int32_t) เมธอด


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int32_t value)
```

## Convert::ToDateTime(uint64_t) เมธอด


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint64_t value)
```

## Convert::ToDateTime(int64_t) เมธอด


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int64_t value)
```

## Convert::ToDateTime(float) เมธอด


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(float value)
```

## Convert::ToDateTime(double) เมธอด


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(double value)
```

## Convert::ToDateTime(const Decimal\&) เมธอด


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(const Decimal &value)
```

## Convert::ToDateTime(char_t) เมธอด


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(char_t value)
```

## Convert::ToDateTime(DateTime) เมธอด


ส่งคืนวันที่และเวลาที่ระบุ

```cpp
static constexpr DateTime System::Convert::ToDateTime(DateTime value)
```

## Convert::ToDateTime(const String\&) เมธอด


แปลงสตริงที่ระบุเป็นอินสแตนซ์ของคลาส [DateTime](../../datetime/)

```cpp
static DateTime System::Convert::ToDateTime(const String &value)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง |

### ค่าที่คืน

อินสแตนซ์ของคลาส [DateTime](../../datetime/) ที่แสดงข้อมูลวันที่และเวลาที่ระบุโดยสตริงที่กำหนด

## Convert::ToDateTime(const String\&, const SharedPtr\<IFormatProvider\>\&) เมธอด


แปลงสตริงที่ระบุเป็นอินสแตนซ์ของคลาส [DateTime](../../datetime/) โดยใช้ข้อมูลการจัดรูปแบบที่ให้มา

```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<IFormatProvider> &fp)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะทำการแปลง |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ตัวชี้ไปยังอ็อบเจกต์ที่มีข้อมูลรูปแบบสตริง |

### ค่าที่คืน

อินสแตนซ์ของคลาส [DateTime](../../datetime/) ที่แสดงข้อมูลวันที่และเวลาที่ระบุโดยสตริงที่กำหนด

## Convert::ToDateTime(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) เมธอด




```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDateTime(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) เมธอด




```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## Convert::ToDateTime(const String\&, std::nullptr_t) เมธอด




```cpp
static DateTime System::Convert::ToDateTime(const String &value, std::nullptr_t)
```

## Convert::ToDateTime(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) เมธอด


แปลงค่าที่บรรจุไว้ที่ระบุให้เป็นค่า [DateTime](../../datetime/) ที่เทียบเท่า

```cpp
static DateTime System::Convert::ToDateTime(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | SharedPtr ของอ็อบเจกต์ที่บรรจุค่าที่ต้องการแปลง |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | รูปแบบสตริงที่จะใช้หากประเภทของค่าที่บรรจุเป็น [String](../../string/) |

### ค่าที่คืน

ค่า [DateTime](../../datetime/) ที่เทียบเท่ากับค่าที่บรรจุที่ระบุ

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../../datetime/)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)