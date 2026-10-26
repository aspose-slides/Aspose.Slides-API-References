---
title: Sign()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดสัญญาณของค่าจำนวนเต็มที่มีเครื่องหมายที่ระบุ
type: docs
weight: 274
url: /th/system/math/sign/
---
## Math::Sign(T) เมธอด

กำหนดสัญลักษณ์ของค่าจำนวนเต็มที่มีเครื่องหมายที่ระบุ

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::Math::Sign(T value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทจำนวนเต็มมีเครื่องหมาย |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | T | ค่าที่ต้องการกำหนดสัญลักษณ์ของมัน |

### ค่าที่คืนกลับ

- 1 ถ้า **value** น้อยกว่า 0; 0 ถ้า **value** เท่ากับ 0; 1 ถ้า **value** มากกว่า 0

## Math::Sign(T) เมธอด

กำหนดสัญลักษณ์ของค่าจุดลอยที่ระบุ

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::Math::Sign(T value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของจุดลอยของอากิวเมนต์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | T | ค่าที่ต้องการกำหนดสัญลักษณ์ของมัน |

### ค่าที่คืนกลับ

- 1 ถ้า **value** น้อยกว่า 0; 0 ถ้า **value** เท่ากับ 0; 1 ถ้า **value** มากกว่า 0

## Math::Sign(const Decimal\&) เมธอด

กำหนดสัญลักษณ์ของค่าทศนิยมที่ระบุ

```cpp
static int System::Math::Sign(const Decimal &value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | ค่าที่ต้องการกำหนดสัญลักษณ์ของมัน |

### ค่าที่คืนกลับ

- 1 ถ้า **value** น้อยกว่า 0; 0 ถ้า **value** เท่ากับ 0; 1 ถ้า **value** มากกว่า 0

## ดูเพิ่มเติม

* คลาส [Decimal](../../decimal/)
* โครงสร้าง [Math](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)