---
title: ExceptionWrapper
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: เทมเพลตที่เป็นตัวห่อของข้อยกเว้นที่สืบทอดมาจากคลาส Exception.
type: docs
weight: 833
url: /th/system/exceptionwrapper/
---
## ExceptionWrapper คลาส

เทมเพลตที่แสดงถึงตัวห่อของข้อยกเว้นที่สืบทอดจาก Exception คลาส.

```cpp
template<typename T>class ExceptionWrapper
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
|  [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | สร้างอินสแตนซ์เป็น null ของคลาส [ExceptionWrapper](./) ที่ไม่แสดงถึงข้อยกเว้นใด ๆ. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionPtr](../exceptionptr/)\&) | สร้างอินสแตนซ์ของคลาส [ExceptionWrapper](./) ที่มีตัวชี้ที่ส่งเข้ามา. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionWrapper](./)\&) | คอนสตรัคเตอร์สำเนา. |
|  [ExceptionWrapper](./exceptionwrapper/)([ExceptionWrapper](./)\&&) | คอนสตรัคเตอร์การย้าย. |
| explicit  [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | คอนสตรัคเตอร์ที่ส่งต่อพารามิเตอร์ไปยังคอนสตรัคเตอร์ของ Exception คลาสและสร้างสมาร์ทพอยน์เตอร์ที่ถืออินสแตนซ์ใหม่ของ Exception คลาส. |
| static void * [operator new](./operator_new/)(std::size_t) |  |
| static void * [operator new[]](./operator_new[]/)(std::size_t) |  |
|  [operator SharedPtr< Object >](./operator_sharedptr_less_object__greater/)() | โอเปอเรเตอร์การแคสโดยอัตโนมัติไปยัง SharedPtr<Object> |
| T * [operator->](./operator_minus_greater/)() const | อนุญาตให้เข้าถึงสมาชิกของอ็อบเจกต์ Exception. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)(const [ExceptionWrapper](./)\&) | โอเปอเรเตอร์การกำหนดค่า. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)([ExceptionWrapper](./)\&&) | โอเปอเรเตอร์การกำหนดค่าการย้าย. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | ทางลัดเพื่อรับอ็อบเจกต์ [System::TypeInfo](../typeinfo/) สำหรับชนิด Exception. |

## Typedefs

| Typedef | คำอธิบาย |
| --- | --- |
| [ExceptionType](./exceptiontype/) | ใช้สำหรับฟังก์ชันการแคส. |

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)