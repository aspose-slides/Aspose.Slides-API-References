---
title: ToSingle()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แปลงค่า boolean ที่ระบุให้เป็นเลขจุดลอยแบบ single-precision ที่เท่ากัน.
type: docs
weight: 209
url: /th/system/convert/tosingle/
---
## Convert::ToSingle(bool) เมธอด

แปลงค่า **boolean** ที่ระบุให้เป็นเลขทศนิยมจุดลอยแบบ single-precision ที่เท่ากัน

```cpp
static constexpr float System::Convert::ToSingle(bool value)
```

## Convert::ToSingle(uint8_t) เมธอด

แปลงค่า **uint8_t** ที่ระบุให้เป็นเลขทศนิยมจุดลอยแบบ single-precision ที่เท่ากัน

```cpp
static constexpr float System::Convert::ToSingle(uint8_t value)
```

## Convert::ToSingle(int8_t) เมธอด

แปลงค่า **int8_t** ที่ระบุให้เป็นเลขทศนิยมจุดลอยแบบ single-precision ที่เท่ากัน

```cpp
static constexpr float System::Convert::ToSingle(int8_t value)
```

## Convert::ToSingle(uint16_t) เมธอด

แปลงค่า **uint16_t** ที่ระบุให้เป็นเลขทศนิยมจุดลอยแบบ single-precision ที่เท่ากัน

```cpp
static constexpr float System::Convert::ToSingle(uint16_t value)
```

## Convert::ToSingle(int16_t) เมธอด

แปลงค่า **int16_t** ที่ระบุให้เป็นเลขทศนิยมจุดลอยแบบ single-precision ที่เท่ากัน

```cpp
static constexpr float System::Convert::ToSingle(int16_t value)
```

## Convert::ToSingle(uint32_t) เมธอด

แปลงค่า **uint32_t** ที่ระบุให้เป็นเลขทศนิยมจุดลอยแบบ single-precision ที่เท่ากัน

```cpp
static constexpr float System::Convert::ToSingle(uint32_t value)
```

## Convert::ToSingle(int32_t) เมธอด

แปลงค่า **int32_t** ที่ระบุให้เป็นเลขทศนิยมจุดลอยแบบ single-precision ที่เท่ากัน

```cpp
static constexpr float System::Convert::ToSingle(int32_t value)
```

## Convert::ToSingle(uint64_t) เมธอด

แปลงค่า **uint64_t** ที่ระบุให้เป็นเลขทศนิยมจุดลอยแบบ single-precision ที่เท่ากัน

```cpp
static constexpr float System::Convert::ToSingle(uint64_t value)
```

## Convert::ToSingle(int64_t) เมธอด

แปลงค่า **int64_t** ที่ระบุให้เป็นเลขทศนิยมจุดลอยแบบ single-precision ที่เท่ากัน

```cpp
static constexpr float System::Convert::ToSingle(int64_t value)
```

## Convert::ToSingle(float) เมธอด

คืนค่าตัวเลข **float** ที่ระบุ

```cpp
static constexpr float System::Convert::ToSingle(float value)
```

## Convert::ToSingle(double) เมธอด

แปลงค่า **double** ที่ระบุให้เป็นเลขทศนิยมจุดลอยแบบ single-precision ที่เท่ากัน

```cpp
static constexpr float System::Convert::ToSingle(double value)
```

## Convert::ToSingle(const Decimal\&) เมธอด

แปลงค่า **Decimal** ที่ระบุให้เป็นเลขทศนิยมจุดลอยแบบ single-precision ที่เท่ากัน

```cpp
static float System::Convert::ToSingle(const Decimal &value)
```

## Convert::ToSingle(char_t) เมธอด

ไม่รองรับการแปลง จะทำให้เกิด **InvalidCastException** เสมอ

```cpp
static float System::Convert::ToSingle(char_t value)
```

## Convert::ToSingle(DateTime) เมธอด

ไม่รองรับการแปลง จะทำให้เกิด **InvalidCastException** เสมอ

```cpp
static float System::Convert::ToSingle(DateTime value)
```

## Convert::ToSingle(std::nullptr_t) เมธอด

แปลงค่าสตริง null ที่ระบุให้เป็นค่าเลขจุดลอยแบบ single-precision ที่เท่ากัน

```cpp
static constexpr float System::Convert::ToSingle(std::nullptr_t)
```

### ค่าที่ส่งกลับ

ศูนย์

## Convert::ToSingle(const char_t *) เมธอด

แปลง **c-string** ที่มีการแสดงตัวเลขเป็นสตริงให้เป็นค่าเลขจุดลอยแบบ single-precision ที่เท่ากัน

```cpp
static float System::Convert::ToSingle(const char_t *value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const char_t * | c-string ที่จะทำการแปลง |

### ค่าที่ส่งกลับ

ค่าเลขจุดลอยแบบ single-precision ที่เท่ากับตัวเลขที่แสดงใน **c-string** ที่ระบุ

## Convert::ToSingle(const String\&) เมธอด

แปลง **string** ที่มีการแสดงตัวเลขเป็นสตริงให้เป็นค่าเลขจุดลอยแบบ single-precision ที่เท่ากัน

```cpp
static float System::Convert::ToSingle(const String &value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะแปลง |

### ค่าที่ส่งกลับ

ค่าเลขจุดลอยแบบ single-precision ที่เท่ากับตัวเลขที่แสดงในสตริงที่ระบุ

## Convert::ToSingle(const String\&, const SharedPtr\<IFormatProvider\>\&) เมธอด

แปลง **string** ที่มีการแสดงตัวเลขเป็นสตริงให้เป็นค่าเลขจุดลอยแบบ single-precision ที่เท่ากันโดยใช้ข้อมูลการจัดรูปแบบที่ให้มา

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะแปลง |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ตัวชี้ไปยังออบเจกต์ที่มีข้อมูลรูปแบบสตริง |

### ค่าที่ส่งกลับ

ค่าเลขจุดลอยแบบ single-precision ที่เท่ากับตัวเลขที่แสดงในสตริงที่ระบุ

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) เมธอด

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) เมธอด

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, std::nullptr_t) เมธอด

```cpp
static float System::Convert::ToSingle(const String &value, std::nullptr_t)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) เมธอด

แปลง **string** ที่มีการแสดงตัวเลขเป็นสตริงให้เป็นค่าเลขจุดลอยแบบ single-precision ที่เท่ากันโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ตัวเลขที่ให้มา

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | สตริงที่จะแปลง |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | การรวมแบบบิตของค่าใน enum **NumberStyles** ที่ระบุสไตล์ที่อนุญาตของการแสดงตัวเลขในสตริง |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ตัวชี้ไปยังออบเจกต์ที่มีข้อมูลรูปแบบสตริง |

### ค่าที่ส่งกลับ

ค่าเลขจุดลอยแบบ single-precision ที่เท่ากับตัวเลขที่แสดงในสตริงที่ระบุ

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) เมธอด

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) เมธอด

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, std::nullptr_t) เมธอด

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSingle(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) เมธอด

แปลงค่า **object** ที่ห่อหุ้มไว้ให้เป็นค่าเลขจุดลอยแบบ single-precision

```cpp
static float System::Convert::ToSingle(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | ตัวชี้แชร์ไปยังออบเจกต์ที่บรรจุค่าที่จะทำการแปลง |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | รูปแบบสตริงที่จะใช้หากประเภทของค่าที่บรรจุเป็น [String](../../string/) |

### ค่าที่ส่งกลับ

ค่าเลขจุดลอยแบบ single-precision ที่เท่ากับค่า boxed ที่ระบุ

## ดูเพิ่มเติม

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)