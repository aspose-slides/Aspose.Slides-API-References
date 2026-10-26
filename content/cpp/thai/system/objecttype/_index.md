---
title: ObjectType
second_title: Aspose.Slides สำหรับ C++ API เอกสารอ้างอิง
description: ให้เมธอดแบบสแตติกที่ทำการเรียกข้อมูลประเภทของอ็อบเจกต์. นี้เป็นประเภทสแตติกที่ไม่มีบริการอินสแตนซ์. คุณไม่ควรสร้างอินสแตนซ์ของมันด้วยวิธีใดๆ.
type: docs
weight: 1158
url: /th/system/objecttype/
---
## ObjectType คลาส

จัดหาเมธอดแบบสแตติกที่ทำการเรียกข้อมูลประเภทของอ็อบเจกต์. นี้เป็นประเภทสแตติกที่ไม่มีบริการอินสแตนซ์. คุณไม่ควรสร้างอินสแตนซ์ของมันด้วยวิธีใดๆ.

```cpp
class ObjectType
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | ทำการแปล typeof() โอเวอร์โหลดสำหรับตัวชี้อัจฉริยะ. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | ทำการแปล typeof() โอเวอร์โหลดสำหรับโครงสร้าง. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | ทำการแปล typeof() โอเวอร์โหลดสำหรับข้อยกเว้น. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | ทำการแปล typeof() โอเวอร์โหลดสำหรับประเภทพื้นฐาน. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | ทำการแปล typeof() โอเวอร์โหลดสำหรับประเภท [Nullable](../nullable/). |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | ทำการแปล typeof() โอเวอร์โหลดสำหรับประเภทพื้นฐาน. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | ทำการแปล typeof() โอเวอร์โหลดสำหรับประเภท enum. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | ทำการแปล typeof() โอเวอร์โหลดสำหรับโครงสร้างและตัวชี้. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | ทำการแปล typeof() โอเวอร์โหลดสำหรับ [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | ทำการแปล typeof() โอเวอร์โหลดสำหรับ MutlicastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | ทำการแปล typeof() โอเวอร์โหลดสำหรับโครงสร้างและตัวชี้. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)(const [String](../string/)\&) | ทำการแปล typeof() โอเวอร์โหลดสำหรับประเภทสตริง. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | ทำการแปล typeof() โอเวอร์โหลดสำหรับ **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | ทำการแปล typeof() โอเวอร์โหลดสำหรับ **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | ทำการแปล typeof() โอเวอร์โหลดสำหรับ **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | ทำการแปล typeof() โอเวอร์โหลดสำหรับ **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | ทำการแปล typeof() โอเวอร์โหลดสำหรับ **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | ทำการแปล typeof() โอเวอร์โหลดสำหรับ **uint8_t**. |

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)