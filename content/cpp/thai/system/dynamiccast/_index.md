---
title: DynamicCast()
second_title: Aspose.Slides สำหรับ API อ้างอิง C++
description: ทำการแปลงประเภทแบบไดนามิกบนอ็อบเจ็กต์ Exception.
type: docs
weight: 2536
url: /th/system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) ฟังก์ชัน

ทำการแปลงประเภทแบบไดนามิกบนอ็อบเจ็กต์ Exception

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | Source Exception type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | ตัวชี้แหล่งที่มา. |

### ค่าที่ส่งกลับ

ผลลัพธ์การแคสต์หากการแคสต์ได้รับอนุญาต.

ล้าสมัย
:   ทิ้งไว้เพื่อความเข้ากันได้ย้อนหลัง. ใช้ ExplicitCast แทน.

## System::DynamicCast(SmartPtr\<TFrom\> const\&) ฟังก์ชัน

ทำการแปลงประเภทแบบไดนามิกบนอ็อบเจ็กต์ [SmartPtr](../smartptr/)

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | ตัวชี้แหล่งที่มา. |

### ค่าที่ส่งกลับ

ผลลัพธ์การแคสต์หากการแคสต์ได้รับอนุญาต.

ล้าสมัย
:   ทิ้งไว้เพื่อความเข้ากันได้ย้อนหลัง. ใช้ ExplicitCast แทน.

## System::DynamicCast(SmartPtr\<TFrom\>) ฟังก์ชัน

แตก enum ที่บรรจุด้วยการแคสต์

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| TTo | Target enum type. |
| TFrom | Source pointee type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | ตัวชี้ไปยังอ็อบเจ็กต์เพื่อดึงข้อมูลที่บรรจุ. |

### ค่าที่ส่งกลับ

ค่า enum ที่แตกแล้ว.

ล้าสมัย
:   ทิ้งไว้เพื่อความเข้ากันได้ย้อนหลัง. ใช้ ExplicitCast แทน.

## System::DynamicCast(std::nullptr_t) ฟังก์ชัน

ทำการแปลงประเภทแบบไดนามิกของอ็อบเจ็กต์ null

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| TTo | Target pointee type. |

### ค่าที่ส่งกลับ

nullptr.

ล้าสมัย
:   ทิ้งไว้เพื่อความเข้ากันได้ย้อนหลัง. ใช้ ExplicitCast แทน.

## System::DynamicCast(TFrom\&) ฟังก์ชัน

ทำการแปลงประเภทแบบไดนามิกบนอ็อบเจ็กต์ที่ไม่ใช่ตัวชี้

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| TTo | Target type. |
| TFrom | Source type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| obj | TFrom\& | อ็อบเจ็กต์แหล่งที่มา. |

### ค่าที่ส่งกลับ

ผลลัพธ์การแคสต์.

ล้าสมัย
:   ทิ้งไว้เพื่อความเข้ากันได้ย้อนหลัง. ใช้ ExplicitCast แทน.

## System::DynamicCast(SmartPtr\<TFrom\>) ฟังก์ชัน

ทำการแปลงประเภทแบบไดนามิกบน Objects ไปยังอ็อบเจ็กต์ Exception

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | [Object](../object/) type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | ตัวชี้แหล่งที่มา. |

### ค่าที่ส่งกลับ

ผลลัพธ์การแคสต์หากการแคสต์ได้รับอนุญาต.

ล้าสมัย
:   ทิ้งไว้เพื่อความเข้ากันได้ย้อนหลัง. ใช้ ExplicitCast แทน.

## System::DynamicCast(TFrom) ฟังก์ชัน

ทำการแปลงประเภทแบบไดนามิกจาก IntPtr ไปยังตัวชี้

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| TTo | Target type. |
| TFrom | Source type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | TFrom | ค่ารูปแบบ IntPtr แหล่งที่มา. |

### ค่าที่ส่งกลับ

ผลลัพธ์การแคสต์.

ล้าสมัย
:   ทิ้งไว้เพื่อความเข้ากันได้ย้อนหลัง. ใช้ ExplicitCast แทน.

## ดูเพิ่มเติม

* คลาส [SmartPtr](../smartptr/)
* คลาส [Object](../object/)
* โครงสร้าง [IsExceptionWrapper](../isexceptionwrapper/)
* โครงสร้าง [CastResult](../castresult/)
* โครงสร้าง [IsSmartPtr](../issmartptr/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)