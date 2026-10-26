---
title: GetType()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ดำเนินการแปล typeof(). การโอเวอร์โหลดสำหรับตัวชี้อัจฉริยะ.
type: docs
weight: 1
url: /th/system/objecttype/gettype/
---
## ObjectType::GetType(const T\&) method

ดำเนินการแปล typeof() . การโอเวอร์โหลดสำหรับตัวชี้อัจฉริยะ

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### พารามิเตอร์ต้นแบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | Pointer object type. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) เพื่อให้ได้ [TypeInfo](../../typeinfo/) สำหรับ. |

### ค่าที่ส่งคืน

อ้างอิงคงที่ไปยังโครงสร้าง [TypeInfo](../../typeinfo/) ที่อธิบายคลาสสุดท้ายของอ็อบเจ็กต์ที่ส่งเข้ามา

## ObjectType::GetType(const T\&) method

ดำเนินการแปล typeof() . การโอเวอร์โหลดสำหรับโครงสร้าง

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### พารามิเตอร์ต้นแบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | Structure type. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) เพื่อให้ได้ [TypeInfo](../../typeinfo/) สำหรับ. |

### ค่าที่ส่งคืน

อ้างอิงคงที่ไปยังโครงสร้าง [TypeInfo](../../typeinfo/) ที่อธิบายคลาสสุดท้ายของอ็อบเจ็กต์ที่ส่งเข้ามา

## ObjectType::GetType(const T\&) method

ดำเนินการแปล typeof() . การโอเวอร์โหลดสำหรับข้อยกเว้น

```cpp
template<typename T> static std::enable_if<IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### พารามิเตอร์ต้นแบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | Exception type. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) เพื่อให้ได้ [TypeInfo](../../typeinfo/) สำหรับ. |

### ค่าที่ส่งคืน

อ้างอิงคงที่ไปยังโครงสร้าง [TypeInfo](../../typeinfo/) ที่อธิบายคลาสสุดท้ายของอ็อบเจ็กต์ที่ส่งเข้ามา

## ObjectType::GetType(const T) method

ดำเนินการแปล typeof() . การโอเวอร์โหลดสำหรับประเภทพื้นฐาน

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value||std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### พารามิเตอร์ต้นแบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | Primitive type. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | const T | ละเว้น |

### ค่าที่ส่งคืน

อ้างอิงคงที่ไปยังโครงสร้าง [TypeInfo](../../typeinfo/) ที่อธิบายประเภทของอ็อบเจ็กต์ที่ส่งเข้ามา

## ObjectType::GetType(const T) method

ดำเนินการแปล typeof() . การโอเวอร์โหลดสำหรับประเภท [Nullable](../../nullable/)

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### พารามิเตอร์ต้นแบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | [Nullable](../../nullable/) type. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | const T | ละเว้น |

### ค่าที่ส่งคืน

อ้างอิงคงที่ไปยังโครงสร้าง [TypeInfo](../../typeinfo/) ที่อธิบายประเภทของอ็อบเจ็กต์ที่ส่งเข้ามา

## ObjectType::GetType() method

ดำเนินการแปล typeof() . การโอเวอร์โหลดสำหรับประเภทพื้นฐาน

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value &&!std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### พารามิเตอร์ต้นแบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | Primitive type. |

### ค่าที่ส่งคืน

อ้างอิงคงที่ไปยังโครงสร้าง [TypeInfo](../../typeinfo/) ที่อธิบายประเภทที่ระบุ

## ObjectType::GetType() method

ดำเนินการแปล typeof() . การโอเวอร์โหลดสำหรับประเภท enumeration

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### พารามิเตอร์ต้นแบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | Primitive type. |

### ค่าที่ส่งคืน

อ้างอิงคงที่ไปยังโครงสร้าง [TypeInfo](../../typeinfo/) ที่อธิบายประเภทที่ระบุ

## ObjectType::GetType() method

ดำเนินการแปล typeof() . การโอเวอร์โหลดสำหรับโครงสร้างและตัวชี้

```cpp
template<typename T> static std::enable_if<(!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsBoxable<T>::value)||IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### พารามิเตอร์ต้นแบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | Primitive type. |

### ค่าที่ส่งคืน

อ้างอิงคงที่ไปยังโครงสร้าง [TypeInfo](../../typeinfo/) ที่อธิบายโครงสร้างที่ระบุ

## ObjectType::GetType() method

ดำเนินการแปล typeof() . การโอเวอร์โหลดสำหรับ [Nullable](../../nullable/)

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### พารามิเตอร์ต้นแบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | [Nullable](../../nullable/) type. |

### ค่าที่ส่งคืน

อ้างอิงคงที่ไปยังโครงสร้าง [TypeInfo](../../typeinfo/) ที่อธิบายโครงสร้างที่ระบุ

## ObjectType::GetType() method

ดำเนินการแปล typeof() . การโอเวอร์โหลดสำหรับ MutlicastDelegate

```cpp
template<typename T> static std::enable_if<detail::is_a<T, MulticastDelegate>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### พารามิเตอร์ต้นแบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | MutlicastDelegate type. |

### ค่าที่ส่งคืน

อ้างอิงคงที่ไปยังโครงสร้าง [TypeInfo](../../typeinfo/) ที่อธิบายโครงสร้างที่ระบุ

## ObjectType::GetType() method

ดำเนินการแปล typeof() . การโอเวอร์โหลดสำหรับโครงสร้างและตัวชี้

```cpp
template<typename T> static std::enable_if<!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&IsBoxable<T>::value &&!detail::is_a<T, MulticastDelegate>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### พารามิเตอร์ต้นแบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | Primitive type. |

### ค่าที่ส่งคืน

อ้างอิงคงที่ไปยังโครงสร้าง [TypeInfo](../../typeinfo/) ที่อธิบายโครงสร้างที่ระบุหรือประเภท pointee หากเรียกใช้สำหรับ [SmartPtr](../../smartptr/)

## ObjectType::GetType(const String\&) method

ดำเนินการแปล typeof() . การโอเวอร์โหลดสำหรับประเภทสตริง

```cpp
static const System::TypeInfo & System::ObjectType::GetType(const String &obj)
```

### พารามิเตอร์ต้นแบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | Primitive type. |

### ค่าที่ส่งคืน

อ้างอิงคงที่ไปยังโครงสร้าง [TypeInfo](../../typeinfo/) ที่อธิบายประเภท [String](../../string/)

## ObjectType::GetType() method

ดำเนินการแปล typeof() . การโอเวอร์โหลดสำหรับ **uint8_t**

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() method

ดำเนินการแปล typeof() . การโอเวอร์โหลดสำหรับ char16_t

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() method

ดำเนินการแปล typeof() . การโอเวอร์โหลดสำหรับ **int32_t**

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() method

ดำเนินการแปล typeof() . การโอเวอร์โหลดสำหรับ **int64_t**

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() method

ดำเนินการแปล typeof() . การโอเวอร์โหลดสำหรับ bool

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() method

ดำเนินการแปล typeof() . การโอเวอร์โหลดสำหรับ [Void](../../void/)

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ดูเพิ่มเติม

* คลาส [ObjectType](../)
* คลาส [TypeInfo](../../typeinfo/)
* คลาส [String](../../string/)
* โครงสร้าง [IsSmartPtr](../../issmartptr/)
* โครงสร้าง [IsExceptionWrapper](../../isexceptionwrapper/)
* โครงสร้าง [IsNullable](../../isnullable/)
* โครงสร้าง [IsBoxable](../../isboxable/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)