---
title: Sign()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดเครื่องหมายของค่าตัวเลขจำนวนเต็มที่มีเครื่องหมายที่ระบุ
type: docs
weight: 274
url: /th/system/mathf/sign/
---
## MathF::Sign(T) เมธอด

กำหนดเครื่องหมายของค่าตัวเลขจำนวนเต็มที่มีเครื่องหมายที่ระบุ

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::MathF::Sign(T value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทจำนวนเต็มที่มีเครื่องหมาย |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | T | ค่าที่จะกำหนดเครื่องหมาย |

### ค่าที่คืนมา

- 1 ถ้า **value** น้อยกว่า 0; 0 ถ้า **value** เท่ากับ 0; 1 ถ้า **value** มากกว่า 0

## MathF::Sign(T) เมธอด

กำหนดเครื่องหมายของค่าตัวเลขจุดลอยที่ระบุ

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::MathF::Sign(T value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทเลขทศนิยมของอาร์กิวเมนต์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | T | ค่าที่จะกำหนดเครื่องหมาย |

### ค่าที่คืนมา

- 1 ถ้า **value** น้อยกว่า 0; 0 ถ้า **value** เท่ากับ 0; 1 ถ้า **value** มากกว่า 0

## ดูเพิ่มเติม

* โครงสร้าง [MathF](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)