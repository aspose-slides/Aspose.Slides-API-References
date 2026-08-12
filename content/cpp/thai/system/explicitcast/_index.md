---
title: ExplicitCast()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: แปลงประเภทแหล่งข้อมูลเป็นประเภทผลลัพธ์โดยใช้การแคสต์อย่างชัดเจน ใช้เมื่อประเภทแหล่งและประเภทผลลัพธ์เหมือนกัน
type: docs
weight: 2627
url: /th/system/explicitcast/
---
## System::ExplicitCast(const Source\&) ฟังก์ชัน

แปลงประเภทแหล่งข้อมูลเป็นประเภทผลลัพธ์โดยใช้การแคสต์แบบชัดเจน ใช้เมื่อประเภทแหล่งและประเภทผลลัพธ์เหมือนกัน

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทแหล่งข้อมูล |
| Result | ประเภทผลลัพธ์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อทำการแคสต์ |

### ค่าที่คืน

ผลลัพธ์ของการแคสต์

## System::ExplicitCast(const Source\&) ฟังก์ชัน

แปลงประเภทแหล่งข้อมูลเป็นประเภทผลลัพธ์โดยใช้การแคสต์แบบชัดเจน ใช้เมื่อจำเป็นต้องทำการแคสต์แบบคล้ายคอนสตรัคเตอร์ธรรมดา

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทแหล่งข้อมูล |
| Result | ประเภทผลลัพธ์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อทำการแคสต์ |

### ค่าที่คืน

ผลลัพธ์ของการแคสต์

## System::ExplicitCast(const Source\&) ฟังก์ชัน

แปลงประเภทแหล่งข้อมูลเป็นประเภทผลลัพธ์โดยใช้การแคสต์แบบชัดเจน ใช้สำหรับห่อหุ้มข้อยกเว้น

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทแหล่งข้อมูล |
| Result | ประเภทผลลัพธ์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อทำการแคสต์ |

### ค่าที่คืน

ผลลัพธ์ของการแคสต์

## System::ExplicitCast(const Source\&) ฟังก์ชัน

แปลงประเภทแหล่งข้อมูลเป็นประเภทผลลัพธ์โดยใช้การแคสต์แบบชัดเจน ใช้สำหรับแคสต์อ็อบเจ็กต์เป็นข้อยกเว้น

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทแหล่งข้อมูล |
| Result | ประเภทผลลัพธ์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อทำการแคสต์ |

### ค่าที่คืน

ผลลัพธ์ของการแคสต์

## System::ExplicitCast(const Source\&) ฟังก์ชัน

แปลงประเภทแหล่งข้อมูลเป็นประเภทผลลัพธ์โดยใช้การแคสต์แบบชัดเจน ใช้เมื่อแหล่งและผลลัพธ์เป็นตัวชี้อัจฉริยะ (โดยไม่มี SmartPtr<...> อย่างชัดเจนในประเภทผลลัพธ์)

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทแหล่งข้อมูล |
| Result | ประเภทผลลัพธ์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อทำการแคสต์ |

### ค่าที่คืน

ผลลัพธ์ของการแคสต์

## System::ExplicitCast(Source) ฟังก์ชัน

แปลงประเภทแหล่งข้อมูลเป็นประเภทผลลัพธ์โดยใช้การแคสต์แบบชัดเจน ใช้เมื่อทำการแคสต์ตัวชี้ดิบเป็นตัวชี้อัจฉริยะ

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทแหล่งข้อมูล |
| Result | ประเภทผลลัพธ์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | Source | [Object](../object/) เพื่อทำการแคสต์ |

### ค่าที่คืน

ผลลัพธ์ของการแคสต์

## System::ExplicitCast(const Source\&) ฟังก์ชัน

แปลงประเภทแหล่งข้อมูลเป็นประเภทผลลัพธ์โดยใช้การแคสต์แบบชัดเจน ใช้เมื่อแหล่งและผลลัพธ์เป็นตัวชี้อัจฉริยะ (โดยมี SmartPtr<...> อย่างชัดเจนในประเภทผลลัพธ์)

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทแหล่งข้อมูล |
| Result | ประเภทผลลัพธ์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อทำการแคสต์ |

### ค่าที่คืน

ผลลัพธ์ของการแคสต์

## System::ExplicitCast(const Source\&) ฟังก์ชัน

แปลงประเภทแหล่งข้อมูลเป็นประเภทผลลัพธ์โดยใช้การแคสต์แบบชัดเจน ใช้สำหรับการถอดกล่องอ็อบเจ็กต์เป็นค่า nullable

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทแหล่งข้อมูล |
| Result | ประเภทผลลัพธ์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อทำการแคสต์ |

### ค่าที่คืน

ผลลัพธ์ของการแคสต์

## System::ExplicitCast(const Source\&) ฟังก์ชัน

แปลงประเภทแหล่งข้อมูลเป็นประเภทผลลัพธ์โดยใช้การแคสต์แบบชัดเจน ใช้เพื่อบรรจุค่า nullable

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทแหล่งข้อมูล |
| Result | ประเภทผลลัพธ์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อทำการแคสต์ |

### ค่าที่คืน

ผลลัพธ์ของการแคสต์

## System::ExplicitCast(const Source\&) ฟังก์ชัน

แปลงประเภทแหล่งข้อมูลเป็นประเภทผลลัพธ์โดยใช้การแคสต์แบบชัดเจน ใช้สำหรับการถอดกล่อง nullable object

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทแหล่งข้อมูล |
| Result | ประเภทผลลัพธ์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อทำการแคสต์ |

### ค่าที่คืน

ผลลัพธ์ของการแคสต์

## System::ExplicitCast(const Source\&) ฟังก์ชัน

แปลงประเภทแหล่งข้อมูลเป็นประเภทผลลัพธ์โดยใช้การแคสต์แบบชัดเจน ใช้สำหรับบรรจุ enum

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทแหล่งข้อมูล |
| Result | ประเภทผลลัพธ์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อทำการแคสต์ |

### ค่าที่คืน

ผลลัพธ์ของการแคสต์

## System::ExplicitCast(const Source\&) ฟังก์ชัน

แปลงประเภทแหล่งข้อมูลเป็นประเภทผลลัพธ์โดยใช้การแคสต์แบบชัดเจน ใช้สำหรับคัดลอกประเภทค่าไปยัง heap เมื่อประเภทค่าต้องอ้างอิงเป็นตัวชี้อัจฉริยะ (ใน generic ที่จำกัดด้วยประเภทอินเทอร์เฟซแต่เฉพาะเจาะจงด้วยโครงสร้างที่ทำการติดตั้งอินเทอร์เฟซนี้)

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::HeapifyBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทแหล่งข้อมูล |
| Result | ประเภทผลลัพธ์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อทำการแคสต์ |

### ค่าที่คืน

ผลลัพธ์ของการแคสต์

## System::ExplicitCast(const Source\&) ฟังก์ชัน

แปลงประเภทแหล่งข้อมูลเป็นประเภทผลลัพธ์โดยใช้การแคสต์แบบชัดเจน ใช้สำหรับดึงอินเทอร์เฟซจากประเภทค่า

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทแหล่งข้อมูล |
| Result | ประเภทผลลัพธ์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อทำการแคสต์ |

### ค่าที่คืน

ผลลัพธ์ของการแคสต์

## System::ExplicitCast(const Source\&) ฟังก์ชัน

แปลงประเภทแหล่งข้อมูลเป็นประเภทผลลัพธ์โดยใช้การแคสต์แบบชัดเจน ใช้สำหรับการบรรจุทั่วไป

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทแหล่งข้อมูล |
| Result | ประเภทผลลัพธ์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อทำการแคสต์ |

### ค่าที่คืน

ผลลัพธ์ของการแคสต์

## System::ExplicitCast(const Source\&) ฟังก์ชัน

แปลงประเภทแหล่งข้อมูลเป็นประเภทผลลัพธ์โดยใช้การแคสต์แบบชัดเจน ใช้สำหรับการบรรจุ [System::String](../string/)

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทแหล่งข้อมูล |
| Result | ประเภทผลลัพธ์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อทำการแคสต์ |

### ค่าที่คืน

ผลลัพธ์ของการแคสต์

## System::ExplicitCast(const Source\&) ฟังก์ชัน

แปลงประเภทแหล่งข้อมูลเป็นประเภทผลลัพธ์โดยใช้การแคสต์แบบชัดเจน ใช้สำหรับการถอดกล่องอินเทอร์เฟซ

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxing, Result> System::ExplicitCast(const Source &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทแหล่งข้อมูล |
| Result | ประเภทผลลัพธ์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อทำการแคสต์ |

### ค่าที่คืน

ผลลัพธ์ของการแคสต์

## System::ExplicitCast(const Source\&) ฟังก์ชัน

แปลงประเภทแหล่งข้อมูลเป็นประเภทผลลัพธ์โดยใช้การแคสต์แบบชัดเจน ใช้สำหรับการถอดกล่องทั่วไป

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทแหล่งข้อมูล |
| Result | ประเภทผลลัพธ์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อทำการแคสต์ |

### ค่าที่คืน

ผลลัพธ์ของการแคสต์

## System::ExplicitCast(const Source\&) ฟังก์ชัน

แปลงประเภทแหล่งข้อมูลเป็นประเภทผลลัพธ์โดยใช้การแคสต์แบบชัดเจน ใช้สำหรับการแคสต์ nullptr

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทแหล่งข้อมูล |
| Result | ประเภทผลลัพธ์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อทำการแคสต์ |

### ค่าที่คืน

ผลลัพธ์ของการแคสต์

## System::ExplicitCast(const Source\&) ฟังก์ชัน

แปลงประเภทแหล่งข้อมูลเป็นประเภทผลลัพธ์โดยใช้การแคสต์แบบชัดเจน ใช้สำหรับการแคสต์ระหว่างอาร์เรย์

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทแหล่งข้อมูล |
| Result | ประเภทผลลัพธ์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อทำการแคสต์ |

### ค่าที่คืน

ผลลัพธ์ของการแคสต์

## ดูเพิ่มเติม

* Typedef [Exception](../exception/)
* Class [SmartPtr](../smartptr/)
* Class [BoxedValueBase](../boxedvaluebase/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)