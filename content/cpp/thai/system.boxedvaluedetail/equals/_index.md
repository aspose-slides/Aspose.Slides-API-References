---
title: Equals()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดความเท่ากันของค่าที่ระบุโดยใช้ตัวดำเนินการ ==().
type: docs
weight: 66
url: /th/system.boxedvaluedetail/equals/
---
## System::BoxedValueDetail::Equals(T, T) ฟังก์ชัน

กำหนดความเท่ากันของค่าที่ระบุโดยใช้ [operator==()](../../system/operator_equal_equal/).

```cpp
template<typename T> std::enable_if<detail::has_operator_equal<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| ประเภท | ชนิดของค่าที่เปรียบเทียบ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value1 | T | ค่าตัวเปรียบเทียบแรก |
| value2 | T | ค่าตัวเปรียบเทียบที่สอง |

### ค่าที่คืน

เป็นจริงหากค่าที่ระบุเท่ากันตามที่กำหนดโดย [operator==()](../../system/operator_equal_equal/) มิฉะนั้น - เท็จ

## System::BoxedValueDetail::Equals(T, T) ฟังก์ชัน

กำหนดความเท่ากันของค่าที่ระบุโดยใช้ method [System::Object::Equals()](../../system/object/equals/).

```cpp
template<typename T> std::enable_if<detail::has_only_method_equals<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| ประเภท | ชนิดของค่าที่เปรียบเทียบ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value1 | T | ค่าตัวเปรียบเทียบแรก |
| value2 | T | ค่าตัวเปรียบเทียบที่สอง |

### ค่าที่คืน

เป็นจริงหากค่าที่ระบุเท่ากันตามที่กำหนดโดย method [Equals()](./) มิฉะนั้น - เท็จ

## ดูเพิ่มเติม

* เนมสเปซ [System::BoxedValueDetail](../)
* ไลบรารี [Aspose.Slides](../../)