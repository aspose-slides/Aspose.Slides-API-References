---
title: StaticCast_noexcept()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ทำการ static cast บนวัตถุ SmartPtr.
type: docs
weight: 2549
url: /th/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) ฟังก์ชัน

ทำการ static cast บนวัตถุ [SmartPtr](../smartptr/) objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TTo | ประเภท pointee ของเป้าหมาย. |
| TFrom | ประเภท pointee ของแหล่ง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | ตัวชี้ของแหล่ง. |

### ค่าที่คืน

Cast result if cast is allowed or nullptr otherwise.

เลิกใช้
:   คงไว้เพื่อความเข้ากันได้ย้อนหลัง. ใช้ AsCast แทน.

## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) ฟังก์ชัน

ทำการ static cast บนวัตถุ [WeakPtr](../weakptr/) objects.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TTo | ประเภท pointee ของเป้าหมาย. |
| TFrom | ประเภท pointee ของแหล่ง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | ตัวชี้ของแหล่ง. |

### ค่าที่คืน

Cast result if cast is allowed or nullptr otherwise.

เลิกใช้
:   คงไว้เพื่อความเข้ากันได้ย้อนหลัง. ใช้ AsCast แทน.

## System::StaticCast_noexcept(const TFrom\&) ฟังก์ชัน

ทำการ static cast บนวัตถุ Exception objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TTo | ประเภท Exception ของเป้าหมาย. |
| TFrom | ประเภท Exception ของแหล่ง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | const TFrom\& | ตัวชี้ของแหล่ง. |

### ค่าที่คืน

Cast result if cast is allowed or nullptr otherwise.

เลิกใช้
:   คงไว้เพื่อความเข้ากันได้ย้อนหลัง. ใช้ AsCast แทน.

## System::StaticCast_noexcept(SmartPtr\<TFrom\>) ฟังก์ชัน

ทำการ static cast บน Objects ไปยังวัตถุ Exception objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TTo | ประเภท Exception ของเป้าหมาย. |
| TFrom | ประเภท [Object](../object/). |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | ตัวชี้ของแหล่ง. |

### ค่าที่คืน

Cast result if cast is allowed or nullptr otherwise.

เลิกใช้
:   คงไว้เพื่อความเข้ากันได้ย้อนหลัง. ใช้ AsCast แทน.

## ดูเพิ่มเติม

* คลาส [SmartPtr](../smartptr/)
* คลาส [WeakPtr](../weakptr/)
* คลาส [Object](../object/)
* โครงสร้าง [IsExceptionWrapper](../isexceptionwrapper/)
* โครงสร้าง [CastResult](../castresult/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)