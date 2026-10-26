---
title: Array()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างอาร์เรย์เปล่า.
type: docs
weight: 1
url: /th/system/array/array/
---
## Array::Array() คอนสตรัคเตอร์

สร้างอาร์เรย์เปล่า.

```cpp
System::Array<T>::Array()
```

## Array::Array(int, const T\&) คอนสตรัคเตอร์

คอนสตรัคเตอร์เติมค่า.

```cpp
System::Array<T>::Array(int count, const T &init=T())
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| count | int | ขนาดเริ่มต้นของอาร์เรย์ |
| init | const T\& | ค่าเริ่มต้นที่ใช้เติมอาร์เรย์ |

## Array::Array(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) คอนสตรัคเตอร์

คอนสตรัคเตอร์เติมค่า.

```cpp
template<typename ValueType> System::Array<T>::Array(typename std::enable_if<std::is_arithmetic<T>::value &&std::is_arithmetic<ValueType>::value &&std::is_convertible<ValueType, T>::value, int>::type count, ValueType init)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| ValueType | ชนิดของค่าที่เริ่มต้น |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| count | typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](../valuetype/)\>::value\&&std::is_convertible\<[ValueType](../valuetype/), T\>::value, int\>::type | ขนาดเริ่มต้นของอาร์เรย์ |
| init | [ValueType](../valuetype/) | ค่าเริ่มต้นที่ใช้เติมอาร์เรย์ |

## Array::Array(int, const T) คอนสตรัคเตอร์

คอนสตรัคเตอร์เติมค่า.

```cpp
System::Array<T>::Array(int count, const T inits[])
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| count | int | ขนาดเริ่มต้นของอาร์เรย์ |
| inits | const T | ค่าที่ใช้เติมอาร์เรย์ |

## Array::Array(vector_t\&&) คอนสตรัคเตอร์

คอนสตรัคเตอร์ย้าย.

```cpp
System::Array<T>::Array(vector_t &&value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | **vector_t**\&& | std::vector ซึ่งสมาชิกจะถูกย้ายเข้าสู่อาร์เรย์ |

## Array::Array(const vector_t\&) คอนสตรัคเตอร์

คอนสตรัคเตอร์คัดลอก.

```cpp
System::Array<T>::Array(const vector_t &assgn)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| assgn | const **vector_t**\& | std::vector ที่จะคัดลอกค่าเข้ามา |

## Array::Array(const std::vector\<Q\>\&) คอนสตรัคเตอร์

สร้างวัตถุ [Array](../) และเติมมันด้วยค่าที่คัดลอกจากวัตถุ std::vector ที่ประเภทค่าของมันเหมือนกับ **T** แต่ต่างจาก **UnderlyingType**.

```cpp
template<typename Q,typename> System::Array<T>::Array(const std::vector<Q> &value)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Q | ชนิดของสมาชิกในวัตถุ std::vector ที่จะคัดลอกสมาชิกจาก |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const std::vector\<Q\>\& | std::vector ที่จะคัดลอกค่าจาก |

## Array::Array(std::vector\<Q\>\&&) คอนสตรัคเตอร์

สร้างวัตถุ [Array](../) และเติมมันด้วยค่าที่ย้ายมาจากวัตถุ std::vector ที่ประเภทค่าของมันเหมือนกับ **T** แต่ต่างจาก **UnderlyingType**.

```cpp
template<typename Q,typename> System::Array<T>::Array(std::vector<Q> &&value)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Q | ชนิดของสมาชิกในวัตถุ std::vector ที่จะย้ายสมาชิกจาก |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | std::vector\<Q\>\&& | std::vector ที่จะย้ายค่าจาก |

## Array::Array(std::initializer_list\<UnderlyingType\>) คอนสตรัคเตอร์

สร้างวัตถุ [Array](../) และเติมมันด้วยค่าจากรายการ initializer list ที่ระบุซึ่งมีสมาชิกประเภท **UnderlyingType**.

```cpp
System::Array<T>::Array(std::initializer_list<UnderlyingType> init)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| init | std::initializer_list\<[UnderlyingType](../underlyingtype/)\> | รายการ initializer list ที่มีสมาชิกเพื่อเติมอาร์เรย์ |

## Array::Array(const std::array\<UnderlyingType, InitArraySize\>\&) คอนสตรัคเตอร์

สร้างวัตถุ [Array](../) และเติมมันด้วยค่าจากอาร์เรย์ที่ระบุซึ่งมีสมาชิกประเภท **UnderlyingType**.

```cpp
template<std::size_t> System::Array<T>::Array(const std::array<UnderlyingType, InitArraySize> &init)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| InitArraySize | จำนวนสมาชิกของอาร์เรย์ **init** |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| init | const std::array\<[UnderlyingType](../underlyingtype/), InitArraySize\>\& | [Array](../) เพื่อคัดลอกเข้าสู่อาร์เรย์ที่กำลังสร้าง |

## Array::Array(std::initializer_list\<bool\>, int) คอนสตรัคเตอร์

สร้างวัตถุ [Array](../) และเติมมันด้วยค่าจากรายการ initializer list ที่ระบุซึ่งมีสมาชิกประเภท bool.

```cpp
System::Array<T>::Array(std::initializer_list<bool> init, int=0)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| init | std::initializer_list\<**bool**\> | รายการ initializer list ที่มีสมาชิกเพื่อเติมอาร์เรย์ |

## ดูเพิ่มเติม

* Typedef [ValueType](../valuetype/)
* Typedef [UnderlyingType](../underlyingtype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)