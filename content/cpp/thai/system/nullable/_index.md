---
title: Nullable
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: การประกาศล่วงหน้า.
type: docs
weight: 1106
url: /th/system/nullable/
---
## คลาส Nullable

การประกาศล่วงหน้า.

```cpp
template<typename T>class Nullable
```

### พารามิเตอร์ของแม่แบบ

| Parameter | Description |
| --- | --- |
| T | The underlying value type which is extended by the [Nullable](./) class |

## เมธอด

| Method | Description |
| --- | --- |
| std::enable_if\<[IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [Equals](./equals/)(const T1\&) const | กำหนดว่าค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันเทียบเท่ากับค่าที่แสดงโดยอ็อบเจกต์ [Nullable](./) ที่ระบุหรือไม่ |
| **bool** [get_HasValue](./get_hasvalue/)() const | กำหนดว่าอ็อบเจกต์ปัจจุบันแสดงค่าบางค่าอยู่หรือไม่ |
| T [get_Value](./get_value/)() const | ส่งกลับสำเนาของค่าที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| int [GetHashCode](./gethashcode/)() const | ส่งกลับค่าแฮชโค้ดของอ็อบเจกต์ปัจจุบัน |
| T [GetValueOrDefault](./getvalueordefault/)(T) | ส่งกลับค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันหรือค่าที่ระบุหากค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันเป็น null |
| T [GetValueOrDefault](./getvalueordefault/)() |  |
| **bool** [IsNull](./isnull/)() const | กำหนดว่าอ็อบเจกต์ปัจจุบันแสดงค่า null หรือไม่ |
|  [Nullable](./nullable/)() | สร้างอินสแตนซ์ที่แสดงค่า null |
|  [Nullable](./nullable/)(std::nullptr_t) | สร้างอินสแตนซ์ที่แสดงค่า null |
|  [Nullable](./nullable/)(const T1\&) | สร้างอินสแตนซ์ของคลาส [Nullable](./) ที่แสดงค่าที่ระบุโดยแปลง (หากจำเป็น) เป็นค่าของชนิดพื้นฐาน T |
|  [Nullable](./nullable/)(const [Nullable](./)\<T1\>\&) | สร้างอินสแตนซ์ที่แสดงค่าที่แสดงโดยอ็อบเจกต์ [Nullable](./) ที่ระบุ วัตถุ nullable ที่ระบุอาจแสดงค่าที่มีชนิดต่างจากชนิดพื้นฐานของอินสแตนซ์ที่สร้าง ซึ่งในกรณีนั้นค่าที่แสดงจะถูกแปลงเป็นชนิด T |
| **bool** [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<**bool**()>\&, **bool**) const | ฟังก์ชันช่วยตรวจสอบว่าทั้งอ็อบเจกต์นี้และ **other** ไม่เป็น null ทั้งสองและเรียก lambda หากเป็นเช่นนั้น ใช้ใน implementation.s |
|  [operator const T &](./operator_const_t__and/)() const | ส่งกลับการอ้างอิงแบบคงที่ไปยังค่าที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | กำหนดว่าค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันไม่ได้เป็น null |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&) const | กำหนดว่าค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันไม่เท่ากับค่าที่ระบุ |
| **bool** [operator!=](./operator_not_equal/)(const [Nullable](./)\<T1\>\&) const | กำหนดว่าค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันไม่เท่ากับค่าที่แสดงโดยอ็อบเจกต์ [Nullable](./) ที่ระบุ |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator&=](./operator_and_equal/)(**bool**) | นำ [operator&=()](./operator_and_equal/) ไปใช้กับค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันโดยใช้ค่าที่ระบุเป็นอากิวเมนต์ด้านขวา |
| [Nullable](./)\<T\> [operator+](./operator_plus/)(std::nullptr_t) const | ส่งกลับอินสแตนซ์ที่สร้างโดยค่าเริ่มต้นของคลาส Nullable<T> |
| auto [operator+](./operator_plus/)(const T1\&) const | บวกค่าที่ nullable และค่าที่ไม่ nullable |
| auto [operator+](./operator_plus/)(const [Nullable](./)\<T1\>\&) const | บวกค่าที่ nullable |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(std::nullptr_t) | รีเซ็ตอ็อบเจกต์ปัจจุบันให้แสดงค่า null |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator+=](./operator_plus_equal/)(const T1\&) | นำ [operator+=()](./operator_plus_equal/) ไปใช้กับค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันโดยใช้ค่าที่ระบุเป็นอากิวเมนต์ด้านขวา |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(const [Nullable](./)\<T1\>\&) | นำ [operator+=()](./operator_plus_equal/) ไปใช้กับค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันโดยใช้ค่าที่แสดงโดยอ็อบเจกต์ [Nullable](./) ที่ระบุเป็นอากิวเมนต์ด้านขวา |
| [Nullable](./)\<T\> [operator-](./operator_minus/)(T1) const | ลบค่าที่ nullable และค่าที่ชี้เป็น null |
| auto [operator-](./operator_minus/)(const T1\&) const | ลบค่าที่ nullable และค่าที่ไม่ nullable |
| auto [operator-](./operator_minus/)(const [Nullable](./)\<T1\>\&) const | ลบค่าที่ nullable |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(T1) | ส่งกลับอินสแตนซ์ของคลาส [Nullable](./) ที่แสดงค่า null |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator-=](./operator_minus_equal/)(const T1\&) | นำ [operator-=()](./operator_minus_equal/) ไปใช้กับค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันโดยใช้ค่าที่ระบุเป็นอากิวเมนต์ด้านขวา |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(const [Nullable](./)\<T1\>\&) | นำ [operator-=()](./operator_minus_equal/) ไปใช้กับค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันโดยใช้ค่าที่แสดงโดยอ็อบเจกต์ [Nullable](./) ที่ระบุเป็นอากิวเมนต์ด้านขวา |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const | จะคืนค่า false เสมอ |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&) const | กำหนดว่าค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันน้อยกว่าค่าที่ระบุโดยใช้ [operator<()](./operator_less/) กับค่าทั้งสอง |
| **bool** [operator<](./operator_less/)(const [Nullable](./)\<T1\>\&) const | กำหนดว่าค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันน้อยกว่าค่าที่แสดงโดยอ็อบเจกต์ [Nullable](./) ที่ระบุโดยใช้ [operator<()](./operator_less/) กับค่าทั้งสอง |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const | จะคืนค่า false เสมอ |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&) const | กำหนดว่าค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันน้อยกว่าหรือเท่ากับค่าที่ระบุโดยใช้ [operator<=()](./operator_less_equal/) กับค่าทั้งสอง |
| **bool** [operator<=](./operator_less_equal/)(const [Nullable](./)\<T1\>\&) const | กำหนดว่าค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันน้อยกว่าหรือเท่ากับค่าที่แสดงโดยอ็อบเจกต์ [Nullable](./) ที่ระบุโดยใช้ [operator<=()](./operator_less_equal/) กับค่าทั้งสอง |
| [Nullable](./)\<T\> [operator=](./operator_equal/)(std::nullptr_t) | กำหนดค่า null ให้กับอ็อบเจกต์ปัจจุบัน |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value\&&\!std::is_null_pointer\<T1\>::value, [Nullable](./)\<T\>\&\>::type [operator=](./operator_equal/)(const T1\&) | แทนค่าที่อ็อบเจกต์แสดงอยู่ในปัจจุบันด้วยค่าที่ระบุ |
| [Nullable](./)\<T\>\& [operator=](./operator_equal/)(const [Nullable](./)\<T1\>\&) | แทนค่าที่อ็อบเจกต์แสดงอยู่ในปัจจุบันด้วยค่าที่ระบุ |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | กำหนดว่าค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันเป็น null หรือไม่ |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&) const | กำหนดว่าค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันเท่ากับค่าที่ระบุหรือไม่ |
| **bool** [operator==](./operator_equal_equal/)(const [Nullable](./)\<T1\>\&) const | กำหนดว่าค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันเท่ากับค่าที่แสดงโดยอ็อบเจกต์ [Nullable](./) ที่ระบุหรือไม่ |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const | จะคืนค่า false เสมอ |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&) const | กำหนดว่าค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันมากกว่าค่าที่ระบุโดยใช้ [operator>()](./operator_greater/) กับค่าทั้งสอง |
| **bool** [operator>](./operator_greater/)(const [Nullable](./)\<T1\>\&) const | กำหนดว่าค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันมากกว่าค่าที่แสดงโดยอ็อบเจกต์ [Nullable](./) ที่ระบุโดยใช้ [operator>()](./operator_greater/) กับค่าทั้งสอง |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const | จะคืนค่า false เสมอ |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&) const | กำหนดว่าค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันมากกว่าหรือเท่ากับค่าที่แสดงโดยอ็อบเจกต์ที่ระบุโดยใช้ [operator>=()](./operator_greater_equal/) กับค่าทั้งสอง |
| **bool** [operator>=](./operator_greater_equal/)(const [Nullable](./)\<T1\>\&) const | กำหนดว่าค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันมากกว่าหรือเท่ากับค่าที่แสดงโดยอ็อบเจกต์ [Nullable](./) ที่ระบุโดยใช้ [operator>=()](./operator_greater_equal/) กับค่าทั้งสอง |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator|=](./operator_or_equal/)(**bool**) | นำ [operator|=()](./operator_or_equal/) ไปใช้กับค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันโดยใช้ค่าที่ระบุเป็นอากิวเมนต์ด้านขวา |
| void [reset](./reset/)() | ตั้งค่าที่แสดงอยู่ในปัจจุบันเป็น null |
| void [set_Value](./set_value/)(const T\&) | ตั้งค่าที่ใหม่ให้กับอ็อบเจกต์ nullable |
| [String](../string/) [ToString](./tostring/)() const | แปลงค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันเป็นสตริง |

## การนิยามชนิด

| Typedef | Description |
| --- | --- |
| [ValueType](./valuetype/) | นามแฝงสำหรับชนิดของค่าที่แสดงโดยคลาสนี้ |

## หมายเหตุ

แสดงค่าของชนิดที่ระบุที่สามารถกำหนดเป็น null ได้ ชนิดนี้ควรจัดสรรบนสแตกและส่งผ่านไปยังฟังก์ชันโดยค่า หรือโดยการอ้างอิง ไม่ควรใช้คลาส [System::SmartPtr](../smartptr/) เพื่อจัดการอ็อบเจกต์ของชนิดนี้.

## ดูเพิ่ม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)