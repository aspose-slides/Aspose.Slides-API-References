---
title: AsCast()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แคสต์ประเภทต้นแบบเป็นประเภทผลลัพธ์โดยใช้การแคสต์ด้วยตัวดำเนินการ 'as' ใช้เมื่อจำเป็นต้องทำการแคสต์แบบคล้ายคอนสตรัคเตอร์อย่างง่าย.
type: docs
weight: 2640
url: /th/system/ascast/
---
## System::AsCast(const Source\&) function

แคสต์ประเภทต้นแบบเป็นประเภทผลลัพธ์โดยใช้การแคสต์ด้วยตัวดำเนินการ 'as' ใช้เมื่อจำเป็นต้องแคสต์แบบคล้ายคอนสตรัคเตอร์อย่างง่าย

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อแคสต์. |

### ค่าที่คืน

ผลลัพธ์การแคสต์

## System::AsCast(const Source\&) function

แคสต์ประเภทต้นแบบเป็นประเภทผลลัพธ์โดยใช้การแคสต์ด้วยตัวดำเนินการ 'as' ใช้เมื่อประเภทต้นแบบและประเภทผลลัพธ์เหมือนกัน

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อแคสต์. |

### ค่าที่คืน

ผลลัพธ์การแคสต์

## System::AsCast(const Source\&) function

แคสต์ประเภทต้นแบบเป็นประเภทผลลัพธ์โดยใช้การแคสต์ด้วยตัวดำเนินการ 'as' ใช้สำหรับตัวห่อข้อยกเว้น

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อแคสต์. |

### ค่าที่คืน

ผลลัพธ์การแคสต์

## System::AsCast(const Source\&) function

แคสต์ประเภทต้นแบบเป็นประเภทผลลัพธ์โดยใช้การแคสต์ด้วยตัวดำเนินการ 'as' ใช้สำหรับแคสต์อ็อบเจ็กต์เป็นข้อยกเว้น

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อแคสต์. |

### ค่าที่คืน

ผลลัพธ์การแคสต์

## System::AsCast(const Source\&) function

แคสต์ประเภทต้นแบบเป็นประเภทผลลัพธ์โดยใช้การแคสต์ด้วยตัวดำเนินการ 'as' ใช้เมื่อประเภทต้นแบบและผลลัพธ์เป็นสมาร์ทพอยน์เตอร์ทั้งคู่

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อแคสต์. |

### ค่าที่คืน

ผลลัพธ์การแคสต์ คืนค่า nullptr หากไม่มีการแปลง

## System::AsCast(const Source\&) function

แคสต์ประเภทต้นแบบเป็นประเภทผลลัพธ์โดยใช้การแคสต์ด้วยตัวดำเนินการ 'as' ใช้เมื่อประเภทต้นแบบและผลลัพธ์เป็นสมาร์ทพอยน์เตอร์ทั้งคู่ (โดยมี SmartPtr<...> อย่างชัดเจนในประเภทผลลัพธ์)

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อแคสต์. |

### ค่าที่คืน

ผลลัพธ์การแคสต์ คืนค่า nullptr หากไม่มีการแปลง

## System::AsCast(const Source\&) function

แคสต์ประเภทต้นแบบเป็นประเภทผลลัพธ์โดยใช้การแคสต์ด้วยตัวดำเนินการ 'as' ใช้สำหรับการถอดกล่องอ็อบเจ็กต์เป็น nullable

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อแคสต์. |

### ค่าที่คืน

ผลลัพธ์การแคสต์ คืนค่า nullable ว่างเปล่าหากไม่มีการแปลง

## System::AsCast(const Source\&) function

แคสต์ประเภทต้นแบบเป็นประเภทผลลัพธ์โดยใช้การแคสต์ด้วยตัวดำเนินการ 'as' การถอดกล่องที่ไม่ถูกต้องเป็นประเภทที่ไม่ใช่อ็อบเจ็กต์

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxingToNullable, Result> System::AsCast(const Source &value)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อแคสต์. |

### ค่าที่คืน

จะคืนค่า null เสมอ

## System::AsCast(const Source\&) function

การถอดกล่องที่ไม่ถูกต้องเป็นประเภทที่ไม่ใช่อ็อบเจ็กต์

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อแคสต์. |

### ค่าที่คืน

จะคืนค่า null เสมอ

## System::AsCast(const Source\&) function

แคสต์ประเภทต้นแบบเป็นประเภทผลลัพธ์โดยใช้การแคสต์ด้วยตัวดำเนินการ 'as' ใช้สำหรับการบ็อกซ์อ็อบเจ็กต์ nullable

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อแคสต์. |

### ค่าที่คืน

ผลลัพธ์การแคสต์

## System::AsCast(const Source\&) function

แคสต์ประเภทต้นแบบเป็นประเภทผลลัพธ์โดยใช้การแคสต์ด้วยตัวดำเนินการ 'as' ใช้สำหรับการบ็อกซ์อ็อบเจ็กต์ทั่วไป

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อแคสต์. |

### ค่าที่คืน

ผลลัพธ์การแคสต์

## System::AsCast(const Source\&) function

แคสต์ประเภทต้นแบบเป็นประเภทผลลัพธ์โดยใช้การแคสต์ด้วยตัวดำเนินการ 'as' ใช้สำหรับการบ็อกซ์อ็อบเจ็กต์ทั่วไป

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อแคสต์. |

### ค่าที่คืน

ผลลัพธ์การแคสต์

## System::AsCast(const Source\&) function

แคสต์ประเภทต้นแบบเป็นประเภทผลลัพธ์โดยใช้การแคสต์ด้วยตัวดำเนินการ 'as' ใช้สำหรับการถอดกล่องสตริง

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อแคสต์. |

### ค่าที่คืน

ผลลัพธ์การแคสต์

## System::AsCast(const Source\&) function

แคสต์ประเภทต้นแบบเป็นประเภทผลลัพธ์โดยใช้การแคสต์ด้วยตัวดำเนินการ 'as' ใช้สำหรับการแคสต์ nullptr

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อแคสต์. |

### ค่าที่คืน

ผลลัพธ์การแคสต์

## System::AsCast(const Source\&) function

แคสต์ประเภทต้นแบบเป็นประเภทผลลัพธ์โดยใช้การแคสต์ด้วยตัวดำเนินการ 'as' ใช้เพื่อแคสต์ระหว่างอาเรย์

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) เพื่อแคสต์. |

### ค่าที่คืน

ผลลัพธ์การแคสต์ คืนค่า nullptr หากไม่มีการแปลงสำหรับสมาชิกอาเรย์ใด ๆ

## ดูเพิ่มเติม

* Typedef [Exception](../exception/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)