---
title: ToBoolean()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืนค่า boolean ที่ระบุ
type: docs
weight: 79
url: /th/system/convert/toboolean/
---
## Convert::ToBoolean(bool) เมธอด


ส่งคืนค่า boolean ที่ระบุ

```cpp
static constexpr bool System::Convert::ToBoolean(bool value)
```

## Convert::ToBoolean(uint8_t) เมธอด


แปลงค่า uint8_t ที่ระบุให้เป็นค่า boolean ที่เทียบเท่า

```cpp
static constexpr bool System::Convert::ToBoolean(uint8_t value)
```

## Convert::ToBoolean(int8_t) เมธอด


แปลงค่า int8_t ที่ระบุให้เป็นค่า boolean ที่เทียบเท่า

```cpp
static constexpr bool System::Convert::ToBoolean(int8_t value)
```

## Convert::ToBoolean(uint16_t) เมธอด


แปลงค่า uint16_t ที่ระบุให้เป็นค่า boolean ที่เทียบเท่า

```cpp
static constexpr bool System::Convert::ToBoolean(uint16_t value)
```

## Convert::ToBoolean(int16_t) เมธอด


แปลงค่า int16_t ที่ระบุให้เป็นค่า boolean ที่เทียบเท่า

```cpp
static constexpr bool System::Convert::ToBoolean(int16_t value)
```

## Convert::ToBoolean(uint32_t) เมธอด


แปลงค่า uint32_t ที่ระบุให้เป็นค่า boolean ที่เทียบเท่า

```cpp
static constexpr bool System::Convert::ToBoolean(uint32_t value)
```

## Convert::ToBoolean(int32_t) เมธอด


แปลงค่า int32_t ที่ระบุให้เป็นค่า boolean ที่เทียบเท่า

```cpp
static constexpr bool System::Convert::ToBoolean(int32_t value)
```

## Convert::ToBoolean(uint64_t) เมธอด


แปลงค่า uint64_t ที่ระบุให้เป็นค่า boolean ที่เทียบเท่า

```cpp
static constexpr bool System::Convert::ToBoolean(uint64_t value)
```

## Convert::ToBoolean(int64_t) เมธอด


แปลงค่า int64_t ที่ระบุให้เป็นค่า boolean ที่เทียบเท่า

```cpp
static constexpr bool System::Convert::ToBoolean(int64_t value)
```

## Convert::ToBoolean(float) เมธอด


แปลงค่า float ที่ระบุให้เป็นค่า boolean ที่เทียบเท่า

```cpp
static constexpr bool System::Convert::ToBoolean(float value)
```

## Convert::ToBoolean(double) เมธอด


แปลงค่า double ที่ระบุให้เป็นค่า boolean ที่เทียบเท่า

```cpp
static constexpr bool System::Convert::ToBoolean(double value)
```

## Convert::ToBoolean(const Decimal\&) เมธอด


แปลงค่า Decimal ที่ระบุให้เป็นค่า boolean ที่เทียบเท่า

```cpp
static bool System::Convert::ToBoolean(const Decimal &value)
```

## Convert::ToBoolean(char_t) เมธอด


การแปลงไม่รองรับ. จะทำให้เกิด InvalidCastException เสมอ

```cpp
static bool System::Convert::ToBoolean(char_t value)
```

## Convert::ToBoolean(DateTime) เมธอด


การแปลงไม่รองรับ. จะทำให้เกิด InvalidCastException เสมอ

```cpp
static bool System::Convert::ToBoolean(DateTime value)
```

## Convert::ToBoolean(std::nullptr_t) เมธอด


แปลงค่า null-string ที่ระบุให้เป็นค่า boolean ที่เทียบเท่า

```cpp
static constexpr bool System::Convert::ToBoolean(std::nullptr_t)
```


### ค่าที่ส่งคืน

False.

## Convert::ToBoolean(const char_t *) เมธอด


แปลงค่า c-string ที่ระบุให้เป็นค่าประเภท bool

```cpp
static bool System::Convert::ToBoolean(const char_t *value)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const char_t * | c-string ที่ต้องการแปลง |

### ค่าที่ส่งคืน

True หากสตริง c-string ที่ระบุเท่ากับ "True" และ false หากสตริง c-string ที่ระบุเท่ากับ "False"

## Convert::ToBoolean(const String\&) เมธอด


แปลงค่า string ที่ระบุให้เป็นค่าประเภท bool

```cpp
static bool System::Convert::ToBoolean(const String &value)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | string ที่ต้องการแปลง |

### ค่าที่ส่งคืน

True หากสตริง c-string ที่ระบุเท่ากับ "True" และ false หาก string ที่ระบุเท่ากับ "False"

## Convert::ToBoolean(const String\&, const SharedPtr\<IFormatProvider\>\&) เมธอด


แปลงค่า string ที่ระบุให้เป็นค่าประเภท bool

```cpp
static bool System::Convert::ToBoolean(const String &value, const SharedPtr<IFormatProvider> &)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../string/)\& | string ที่ต้องการแปลง |

### ค่าที่ส่งคืน

True หากสตริง c-string ที่ระบุเท่ากับ "True" และ false หาก string ที่ระบุเท่ากับ "False"

## Convert::ToBoolean(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) เมธอด


แปลงค่า boxed value ที่ระบุให้เป็นค่า boolean ที่เทียบเท่า

```cpp
static bool System::Convert::ToBoolean(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | SharedPtr ไปยัง object ที่บรรจุค่าต้องการแปลง |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ฟอร์แมตสตริงที่จะใช้หากประเภทของ boxed value คือ [String](../../string/) |

### ค่าที่ส่งคืน

ค่าประเภท boolean ที่เทียบเท่ากับ boxed value ที่ระบุ

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)