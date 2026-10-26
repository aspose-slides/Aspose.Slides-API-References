---
title: DynamicCast_noexcept()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: การแคสที่ล้าสมัยเก่า จะถูกลบในเวอร์ชันอนาคต.
type: docs
weight: 2523
url: /th/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) ฟังก์ชัน

การแคสที่ล้าสมัยเก่า จะถูกลบในเวอร์ชันอนาคต.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TTo | ประเภท Exception เป้าหมาย. |
| TFrom | ประเภท Exception แหล่งที่มา. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | const TFrom\& | พอยน์เตอร์แหล่งที่มา. |

### ค่าที่คืนกลับ

ผลลัพธ์การแคสหากการแคสได้รับอนุญาตหรือ nullptr หากไม่เช่นนั้น.

## หมายเหตุ

ทำการแคสแบบไดนามิกบนวัตถุ Exception. Deprecated
:   ปล่อยไว้เพื่อความเข้ากันได้กับรุ่นก่อนหน้า ใช้ AsCast แทน

## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) ฟังก์ชัน

ทำการแคสแบบไดนามิกบน [SmartPtr](../smartptr/) วัตถุ.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TTo | ประเภท pointee เป้าหมาย. |
| TFrom | ประเภท pointee แหล่งที่มา. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | พอยน์เตอร์แหล่งที่มา. |

### ค่าที่คืนกลับ

ผลลัพธ์การแคสหากการแคสได้รับอนุญาตหรือ nullptr หากไม่เช่นนั้น.

Deprecated
:   ปล่อยไว้เพื่อความเข้ากันได้กับรุ่นก่อนหน้า ใช้ AsCast แทน

## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) ฟังก์ชัน

ทำการแคสแบบไดนามิกบนวัตถุเพื่อวัตถุ Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TTo | ประเภท Exception เป้าหมาย. |
| TFrom | [Object](../object/) ประเภท. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | พอยน์เตอร์แหล่งที่มา. |

### ค่าที่คืนกลับ

ผลลัพธ์การแคสหากการแคสได้รับอนุญาตหรือ nullptr หากไม่เช่นนั้น.

Deprecated
:   ปล่อยไว้เพื่อความเข้ากันได้กับรุ่นก่อนหน้า ใช้ AsCast แทน

## ดูเพิ่มเติม

* คลาส [SmartPtr](../smartptr/)
* คลาส [Object](../object/)
* โครงสร้าง [IsExceptionWrapper](../isexceptionwrapper/)
* เนมส페ซ [System](../)
* ไลบรารี [Aspose.Slides](../../)