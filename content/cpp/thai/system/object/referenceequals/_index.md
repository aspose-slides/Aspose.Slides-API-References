---
title: ReferenceEquals()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: "การจำลองพิเศษของ Object::ReferenceEquals สำหรับกรณีของ string และ nullptr."
type: docs
weight: 261
url: /th/system/object/referenceequals/
---
## Object::ReferenceEquals(String const\&, std::nullptr_t) เมธอด

การจำลองพิเศษของ [Object::ReferenceEquals](./) สำหรับกรณีของ string และ nullptr.

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | [String](../../string/) const\& | [String](../../string/) เพื่อเปรียบเทียบกับ nullptr. |

### ค่าที่ส่งกลับ

true หาก string เป็น null, false มิฉะนั้น.

## Object::ReferenceEquals(String const\&, String const\&) เมธอด

การจำลองพิเศษของ [Object::ReferenceEquals](./) สำหรับกรณีของ strings.

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str1 | [String](../../string/) const\& | สตริงแรกเพื่อเปรียบเทียบ. |
| str2 | [String](../../string/) const\& | สตริงที่สองเพื่อเปรียบเทียบ. |

### ค่าที่ส่งกลับ

true หาก strings ตรงกัน, false มิฉะนั้น.

## Object::ReferenceEquals(ptr const\&, ptr const\&) เมธอด

เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง.

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| objA | [ptr](../ptr/) const\& | พอยน์เตอร์แรกเพื่อเปรียบเทียบ. |
| objB | [ptr](../ptr/) const\& | พอยน์เตอร์ที่สองเพื่อเปรียบเทียบ. |

### ค่าที่ส่งกลับ

True หาก pointers ตรงกันและ false มิฉะนั้น.

## Object::ReferenceEquals(T const\&, T const\&) เมธอด

เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของอ็อบเจ็กต์ที่ต้องการเปรียบเทียบ. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| objA | T const\& | อ็อบเจ็กต์แรกเพื่อเปรียบเทียบ. |
| objB | T const\& | อ็อบเจ็กต์ที่สองเพื่อเปรียบเทียบ. |

### ค่าที่ส่งกลับ

True หากที่อยู่ของอ็อบเจ็กต์ตรงกันและ false มิฉะนั้น.

## Object::ReferenceEquals(T const\&, std::nullptr_t) เมธอด

เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่ากับ nullptr.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของอ็อบเจ็กต์เพื่อเปรียบเทียบ. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| objA | T const\& | อ็อบเจ็กต์แรกเพื่อเปรียบเทียบ. |

### ค่าที่ส่งกลับ

จะคืนค่า false เสมอเนื่องจากประเภทค่าที่ไม่สามารถเป็น null ได้.

## ดูเพิ่มเติม

* Typedef [ptr](../ptr/)
* Class [String](../../string/)
* Class [Object](../)
* Struct [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)