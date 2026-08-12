---
title: ToChar()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: การแปลงไม่รองรับ เสมอจะโยน InvalidCastException.
type: docs
weight: 118
url: /th/system/convert/tochar/
---
## Convert::ToChar(bool) เมธอด

การแปลงค่าไม่ได้รับการสนับสนุน เสมอจะโยน InvalidCastException.

```cpp
static char_t System::Convert::ToChar(bool value)
```

## Convert::ToChar(uint8_t) เมธอด

แปลงจำนวนเต็มบวก 8 บิตที่ระบุให้เป็นอักขระยูนิโค้ดที่เทียบเท่า.

```cpp
static constexpr char_t System::Convert::ToChar(uint8_t value)
```

## Convert::ToChar(int8_t) เมธอด

แปลงจำนวนเต็มลบ 8 บิตที่ระบุให้เป็นอักขระยูนิโค้ดที่เทียบเท่า.

```cpp
static char_t System::Convert::ToChar(int8_t value)
```

## Convert::ToChar(uint16_t) เมธอด

แปลงจำนวนเต็มบวก 16 บิตที่ระบุให้เป็นอักขระยูนิโค้ดที่เทียบเท่า.

```cpp
static constexpr char_t System::Convert::ToChar(uint16_t value)
```

## Convert::ToChar(int16_t) เมธอด

แปลงจำนวนเต็มลบ 16 บิตที่ระบุให้เป็นอักขระยูนิโค้ดที่เทียบเท่า.

```cpp
static char_t System::Convert::ToChar(int16_t value)
```

## Convert::ToChar(uint32_t) เมธอด

แปลงจำนวนเต็มบวก 32 บิตที่ระบุให้เป็นอักขระยูนิโค้ดที่เทียบเท่า.

```cpp
static char_t System::Convert::ToChar(uint32_t value)
```

## Convert::ToChar(int32_t) เมธอด

แปลงจำนวนเต็มลบ 32 บิตที่ระบุให้เป็นอักขระยูนิโค้ดที่เทียบเท่า.

```cpp
static char_t System::Convert::ToChar(int32_t value)
```

## Convert::ToChar(uint64_t) เมธอด

แปลงจำนวนเต็มบวก 64 บิตที่ระบุให้เป็นอักขระยูนิโค้ดที่เทียบเท่า.

```cpp
static char_t System::Convert::ToChar(uint64_t value)
```

## Convert::ToChar(int64_t) เมธอด

แปลงจำนวนเต็มลบ 64 บิตที่ระบุให้เป็นอักขระยูนิโค้ดที่เทียบเท่า.

```cpp
static char_t System::Convert::ToChar(int64_t value)
```

## Convert::ToChar(float) เมธอด

การแปลงค่าไม่ได้รับการสนับสนุน เสมอจะโยน InvalidCastException.

```cpp
static char_t System::Convert::ToChar(float value)
```

## Convert::ToChar(double) เมธอด

การแปลงค่าไม่ได้รับการสนับสนุน เสมอจะโยน InvalidCastException.

```cpp
static char_t System::Convert::ToChar(double value)
```

## Convert::ToChar(const Decimal\&) เมธอด

การแปลงค่าไม่ได้รับการสนับสนุน เสมอจะโยน InvalidCastException.

```cpp
static char_t System::Convert::ToChar(const Decimal &value)
```

## Convert::ToChar(char_t) เมธอด

ส่งคืนอักขระยูนิโค้ดที่ระบุ.

```cpp
static constexpr char_t System::Convert::ToChar(char_t value)
```

## Convert::ToChar(DateTime) เมธอด

การแปลงค่าไม่ได้รับการสนับสนุน เสมอจะโยน InvalidCastException.

```cpp
static char_t System::Convert::ToChar(DateTime value)
```

## Convert::ToChar(const char_t *) เมธอด

แปลงอักขระแรกและอักขระเดียวของ c-string ที่ระบุเป็นค่า char_t.

```cpp
static char_t System::Convert::ToChar(const char_t *value)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | c-string ที่จะทำการแปลง; คาดว่า c-string จะมีความยาวเท่ากับ 1 อักขระ |

### Return Value

อักขระแรกและอักขระเดียวของ c-string ที่ระบุหากมีความยาวเท่ากับ 1 อักขระ, มิฉะนั้น - 0

## Convert::ToChar(const String\&) เมธอด

แปลงอักขระแรกและอักขระเดียวของ string ที่ระบุเป็นค่า char_t.

```cpp
static char_t System::Convert::ToChar(const String &value)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | string ที่จะทำการแปลง; คาดว่า string จะมีความยาวเท่ากับ 1 อักขระ |

### Return Value

อักขระแรกและอักขระเดียวของ string ที่ระบุหากมีความยาวเท่ากับ 1 อักขระ, มิฉะนั้น - 0

## Convert::ToChar(const String\&, const SharedPtr\<IFormatProvider\>\&) เมธอด

แปลงอักขระแรกและอักขระเดียวของ string ที่ระบุเป็นค่า char_t.

```cpp
static char_t System::Convert::ToChar(const String &value, const SharedPtr<IFormatProvider> &)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | string ที่จะทำการแปลง; คาดว่า string จะมีความยาวเท่ากับ 1 อักขระ |

### Return Value

อักขระแรกและอักขระเดียวของ string ที่ระบุหากมีความยาวเท่ากับ 1 อักขระ, มิฉะนั้น - 0

## Convert::ToChar(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) เมธอด

แปลงค่า boxed ที่ระบุให้เป็นอักขระยูนิโค้ดที่เทียบเท่า.

```cpp
static char_t System::Convert::ToChar(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | ตัวชี้ SharedPtr ไปยังวัตถุที่บรรจุค่าที่จะทำการแปลง |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ฟอร์แมตของสตริงที่จะใช้หากประเภทของค่าที่บรรจุเป็น [String](../../string/) |

### Return Value

อักขระยูนิโค้ดที่เทียบเท่ากับค่า boxed ที่ระบุ

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