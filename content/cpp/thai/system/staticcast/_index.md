---
title: StaticCast()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ทำการแคสต์แบบสแตติกบนวัตถุ SmartPtr.
type: docs
weight: 2562
url: /th/system/staticcast/
---
## System::StaticCast(SmartPtr\<TFrom\> const\&) ฟังก์ชัน


ทำการแคสต์แบบสแตติกบนวัตถุ [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TTo | ประเภท pointee ปลายทาง. |
| TFrom | ประเภท pointee ต้นทาง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | พอยน์เตอร์ต้นทาง. |

### ค่าที่ส่งกลับ

ผลลัพธ์การแคสต์หากการแคสต์ได้รับอนุญาต.

เลิกใช้
:   ไว้เพื่อความเข้ากันได้กับรุ่นก่อน ใช้ ExplicitCast แทน.

## System::StaticCast(WeakPtr\<TFrom\> const\&) ฟังก์ชัน


ทำการแคสต์แบบสแตติกบนวัตถุ [WeakPtr](../weakptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TTo | ประเภท pointee ปลายทาง. |
| TFrom | ประเภท pointee ต้นทาง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | พอยน์เตอร์ต้นทาง. |

### ค่าที่ส่งกลับ

ผลลัพธ์การแคสต์หากการแคสต์ได้รับอนุญาต.

เลิกใช้
:   ไว้เพื่อความเข้ากันได้กับรุ่นก่อน ใช้ ExplicitCast แทน.

## System::StaticCast(std::nullptr_t) ฟังก์ชัน


ทำการแคสต์แบบสแตติกของวัตถุ null.

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TTo | ประเภท pointee ปลายทาง. |

### ค่าที่ส่งกลับ

nullptr.

เลิกใช้
:   ไว้เพื่อความเข้ากันได้กับรุ่นก่อน ใช้ ExplicitCast แทน.

## System::StaticCast(TFrom) ฟังก์ชัน


การทำพิเศษสำหรับชนิดตัวเลข.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## System::StaticCast(TTo) ฟังก์ชัน


ประมวลผลการแคสต์จาก [String](../string/) ไปยัง [String](../string/).

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## System::StaticCast(const TFrom *) ฟังก์ชัน


การทำพิเศษสำหรับชนิดตัวเลข.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## System::StaticCast(const TFrom\&) ฟังก์ชัน


ทำการแคสต์แบบสแตติกบนวัตถุที่ไม่ใช้พอยน์เตอร์.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TTo | ประเภทปลายทาง. |
| TFrom | ประเภทต้นทาง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | const TFrom\& | อ็อบเจ็กต์ต้นทาง. |

### ค่าที่ส่งกลับ

ผลลัพธ์การแคสต์หากการแคสต์ได้รับอนุญาต.

เลิกใช้
:   ไว้เพื่อความเข้ากันได้กับรุ่นก่อน ใช้ ExplicitCast แทน.

## System::StaticCast(const TFrom\&) ฟังก์ชัน


ทำการแคสต์แบบสแตติกบนวัตถุ Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TTo | ประเภท Exception ปลายทาง. |
| TFrom | ประเภท Exception ต้นทาง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | const TFrom\& | พอยน์เตอร์ต้นทาง. |

### ค่าที่ส่งกลับ

ผลลัพธ์การแคสต์หากการแคสต์ได้รับอนุญาต.

เลิกใช้
:   ไว้เพื่อความเข้ากันได้กับรุ่นก่อน ใช้ ExplicitCast แทน.

## System::StaticCast(SmartPtr\<TFrom\>) ฟังก์ชัน


ทำการแคสต์แบบสแตติกบนอ็อบเจ็กต์ไปยังวัตถุ Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TTo | ประเภท Exception ปลายทาง. |
| TFrom | ประเภท [Object](../object/). |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | พอยน์เตอร์ต้นทาง. |

### ค่าที่ส่งกลับ

ผลลัพธ์การแคสต์หากการแคสต์ได้รับอนุญาต.

เลิกใช้
:   ไว้เพื่อความเข้ากันได้กับรุ่นก่อน ใช้ ExplicitCast แทน.

## ดูเพิ่มเติม

* คลาส [SmartPtr](../smartptr/)
* คลาส [WeakPtr](../weakptr/)
* คลาส [String](../string/)
* คลาส [Object](../object/)
* โครงสร้าง [IsExceptionWrapper](../isexceptionwrapper/)
* โครงสร้าง [CastResult](../castresult/)
* โครงสร้าง [IsSmartPtr](../issmartptr/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)