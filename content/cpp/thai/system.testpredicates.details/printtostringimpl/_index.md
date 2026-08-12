---
title: PrintToStringImpl()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "พิมพ์คลาสย่อยของ System::Object เป็นสตริงโดยใช้เมธอด ToString()"
type: docs
weight: 14
url: /th/system.testpredicates.details/printtostringimpl/
---
## System::TestPredicates::Details::PrintToStringImpl(const SharedPtr\<T\>\&, long long) ฟังก์ชัน

พิมพ์ [System::Object](../../system/object/) คลาสย่อยเป็นสตริงโดยใช้เมธอด ToString().

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const SharedPtr<T> &value, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทคลาสสุดท้าย |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [SharedPtr](../../system/sharedptr/)\<T\>\& | ตัวชี้ไปยังอ็อบเจ็กต์ที่ต้องพิมพ์ |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการโอเวอร์โหลดฟังก์ชันโดยอิงจากประเภทของพารามิเตอร์นี้; ค่าของพารามิเตอร์จะถูกละเว้น |

### ค่าที่ส่งคืน

[String](../../system/string/) การแสดงผลของอ็อบเจ็กต์ที่ส่งเข้ามาหรือ "nullptr", หาก **value** เป็น null.

## System::TestPredicates::Details::PrintToStringImpl(const WeakPtr\<T\>\&, long long) ฟังก์ชัน

พิมพ์ [System::Object](../../system/object/) คลาสย่อยเป็นสตริงโดยใช้เมธอด ToString().

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const WeakPtr<T> &value, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทคลาสสุดท้าย |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [WeakPtr](../../system/weakptr/)\<T\>\& | ตัวชี้ไปยังอ็อบเจ็กต์ที่ต้องพิมพ์ |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการโอเวอร์โหลดฟังก์ชันโดยอิงจากประเภทของพารามิเตอร์นี้; ค่าของพารามิเตอร์จะถูกละเว้น |

### ค่าที่ส่งคืน

[String](../../system/string/) การแสดงผลของอ็อบเจ็กต์ที่ส่งเข้ามาหรือ "nullptr", หาก **value** เป็น null.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) ฟังก์ชัน

พิมพ์อ็อบเจ็กต์เป็นสตริงโดยใช้เมธอด ToString().

```cpp
template<typename T> std::enable_if<!TypeTraits::has_print_to_method<T>::value &&System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | [Object](../../system/object/) ประเภท |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) ที่ต้องพิมพ์ |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการโอเวอร์โหลดฟังก์ชันโดยอิงจากประเภทของพารามิเตอร์นี้; ค่าของพารามิเตอร์จะถูกละเว้น |

### ค่าที่ส่งคืน

[String](../../system/string/) การแสดงผลของอ็อบเจ็กต์ที่ส่งเข้ามา.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) ฟังก์ชัน

พิมพ์อ็อบเจ็กต์เป็นสตริงโดยใช้เมธอด PrintTo.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&!TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | [Object](../../system/object/) ประเภท |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) ที่ต้องพิมพ์ |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการโอเวอร์โหลดฟังก์ชันโดยอิงจากประเภทของพารามิเตอร์นี้; ค่าของพารามิเตอร์จะถูกละเว้น |

### ค่าที่ส่งคืน

[String](../../system/string/) การแสดงผลของอ็อบเจ็กต์ที่ส่งเข้ามา.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) ฟังก์ชัน

พิมพ์อ็อบเจ็กต์เป็นสตริงโดยใช้เมธอด PrintTo.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | [Object](../../system/object/) ประเภท |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) ที่ต้องพิมพ์ |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการโอเวอร์โหลดฟังก์ชันโดยอิงจากประเภทของพารามิเตอร์นี้; ค่าของพารามิเตอร์จะถูกละเว้น |

### ค่าที่ส่งคืน

[String](../../system/string/) การแสดงผลของอ็อบเจ็กต์ที่ส่งเข้ามา.

## System::TestPredicates::Details::PrintToStringImpl(const std::pair\<T1, T2\>\&, long long) ฟังก์ชัน

พิมพ์คู่เป็นสตริง.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const std::pair<T1, T2> &value, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | อาร์กิวเมนต์ประเภทของคู่แรก |
| T2 | อาร์กิวเมนต์ประเภทของคู่ที่สอง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const std::pair\<T1, T2\>\& | [Object](../../system/object/) ที่ต้องพิมพ์ |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการโอเวอร์โหลดฟังก์ชันโดยอิงจากประเภทของพารามิเตอร์นี้; ค่าของพารามิเตอร์จะถูกละเว้น |

### ค่าที่ส่งคืน

การแสดงผลสตริงร่วมของส่วนประกอบของคู่แรกและคู่ที่สอง.

## System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair\<T1, T2\>\&, long long) ฟังก์ชัน

พิมพ์คู่เป็นสตริง.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair<T1, T2> &value, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | อาร์กิวเมนต์ประเภทของคู่แรก |
| T2 | อาร์กิวเมนต์ประเภทของคู่ที่สอง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<T1, T2\>\& | [Object](../../system/object/) ที่ต้องพิมพ์ |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการโอเวอร์โหลดฟังก์ชันโดยอิงจากประเภทของพารามิเตอร์นี้; ค่าของพารามิเตอร์จะถูกละเว้น |

### ค่าที่ส่งคืน

การแสดงผลสตริงร่วมของส่วนประกอบของคู่แรกและคู่ที่สอง.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) ฟังก์ชัน

พิมพ์คอนเทนเนอร์สไตล์ STL เป็นสตริงโดยพิมพ์สมาชิกของมัน (ไม่เกิน 32 รายการ).

```cpp
template<typename T> std::enable_if<TypeTraits::IsCppContainer<T>::value &&!std::is_base_of<Object, T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &container, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิ터 | คำอธิบาย |
| --- | --- |
| T | [Object](../../system/object/) ประเภท |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| container | const T\& | [Object](../../system/object/) ที่ต้องพิมพ์ |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการโอเวอร์โหลดฟังก์ชันโดยอิงจากประเภทของพารามิเตอร์นี้; ค่าของพารามิเตอร์จะถูกละเว้น |

### ค่าที่ส่งคืน

การแสดงผลสตริงร่วมของสมาชิกที่บรรจุอยู่.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, int) ฟังก์ชัน

พิมพ์ประเภทอื่นเป็นสตริงโดยใช้ฟังก์ชันที่ gtest จัดให้.

```cpp
template<typename T> std::string System::TestPredicates::Details::PrintToStringImpl(const T &value, int s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | [Object](../../system/object/) ประเภท |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) ที่ต้องพิมพ์ |
| s | int | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการโอเวอร์โหลดฟังก์ชันโดยอิงจากประเภทของพารามิเตอร์นี้; ค่าของพารามิเตอร์จะถูกละเว้น |

### ค่าที่ส่งคืน

[String](../../system/string/) การแสดงผลของอ็อบเจ็กต์ที่ส่งเข้ามา.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../system/sharedptr/)
* คลาส [WeakPtr](../../system/weakptr/)
* คลาส [KeyValuePair](../../system.collections.generic/keyvaluepair/)
* คลาส [Object](../../system/object/)
* โครงสร้าง [has_print_to_method](../../system.testpredicates.typetraits/has_print_to_method/)
* โครงสร้าง [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* โครงสร้าง [IsCppContainer](../../system.testpredicates.typetraits/iscppcontainer/)
* เนมสเปซ [System::TestPredicates::Details](../)
* ไลบรารี [Aspose.Slides](../../)